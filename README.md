#Why won't my footer go to the bottom of the page?

***

So I was having a problem today that was quite a thorn in my side, if by thorn I mean a giant wooden stake grinding into my side reminding me that the CSS gods are only appeased by blood sacrifices.

So here was my situation.  I had built out my html and put my footer at the very bottom where all good footers go.  But it wouldn't stay there.  

My code looked like this: 

```html         <div class="row">
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
          <div class="clear">
          </div>
          <footer class="footer">
            <p>Posted by: Trevor Rapp</p>
          </footer>
    </body>
  </html> ```
