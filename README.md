#Why won't my footer go to the bottom of the page?

***

###The symptoms of the problem
***
So I was having a problem today that was quite a thorn in my side, if by thorn I mean a giant wooden stake grinding into my side reminding me that the CSS gods are only appeased by blood sacrifices.

So here was my situation.  I had built out my html and put my footer at the very bottom where all good footers go.  But it wouldn't stay there.  

###What the problem looked like on screen
***


![alt text][logo]

[logo]: https://github.com/trrapp12-ironyard/Why-won-t-my-footer-go-down-to-the-bottom-/blob/master/Screen%20Shot%202016-09-29%20at%209.17.54%20PM.png

That big grey box shouldn't be there.  That's supposed to be a little tiny footer at the bottom of the page.


###Code that caused the problem
***
My html looked like this: 

```html
         <div class="row">
          <div class="">
            <img src="images/pexels-photo-127968.jpeg" alt="pic" class="photos medium"/>
          </div>
          <div class="center">
            <h1>Contact</h1>
            <p>
              This is <a href="mailto:webmaster@example.com">contact info</a>
            </p>
            <p>
              Lorem ipsum dolor sit amet, et ut ut rutrum, interdum tempor aliquet sit, tristique elit. Turpis consectetuer mattis auctor.
            </p>
            <br>
              <ul><h3>List</h3>
                <li>Two</li>
                <li>Keywords</li>
              </ul>
            </div>
          </div>
          <footer class="footer">
            <p>Posted by: Trevor Rapp</p>
          </footer>
    </body>
  </html>
  ```

###What didn't work
***

I tried fumbling around with various things like `positon:fixed` or `postion:absolute` on the `<div>` or inline, but I couldn't get anything to work.  It sucked, like for a long time.


###FINALLY!  What worked.
***

I found this article <a href="http://stackoverflow.com/questions/12933418/footer-wont-go-to-the-bottom"></a>.  It explained that the problem was that the footer needed to be cleared.  Right?!!  That's what I said, just like we learned in class this week.  



###What the solution looks like in code
***


