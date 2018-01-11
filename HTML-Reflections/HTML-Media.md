### What is the tag you would use to add an image to a webpage?
img tag

### In your own words, explain what the alt attribute is and why it is important.

Alt attribute is important for accessibility purposes as well as hinders search engine optimizations.  

### Describe the similarity and differences between the video and audio tags.

* **similarities**
  * Share similar attributes
    * controls
    * source
    * autoplay
    * loop
    * preload
    * src
  * formats
      * Ogg
  * Global Attribute Support
  * Display incompatability message


* **differences**
  * formats
    * video: MP4, WebM
    * audio: MP3, Wav
  * video only attributes
      * width
      * height
      * muted
      * poster


  ```
  <!DOCTYPE html>
  <html>
  <head>
    <title>
    Epicurus
    </title>
    </head>

    <body>
      <header>
        <h1>HTML</h1>
        <nav>
          <ul>
            <li>
              <a href="index.html">Home			
              </a>
            </li>
            <li>
              <a href ="about.html">About
              </a>
            </li>
            <li>
              <a href="contact.html">Contact Us   
               </a>
            </li>
            <li>
              <a href="/prices.html">Best Prices in Town.
              </a>
            </li>
          </ul>
        </nav>
      </header>
      <aside>
      </aside>
      <section>
        <table>
          <thead>
            <tr>
              <th>
              Item
              </th>
              <th>
              Description
              </th>
              <th>
              Price
              </th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>
              Salad
              </td>
              <td>
                <img src ="menu_pics/salad.jpg" alt="Delicious Salad">
              </td>
              <td>
              Fresh, delicious Cobb Salad
              </td>
              <td>
              $7.99
              </td>
            </tr>
            <tr>
              <td>
              Burger
              </td>
              <td>
                <img src="menu_pics/hamburger.jpg" alt="Hamburger">
              </td>
              <td>
              1/4 lb grass-fed burger with choice of cheese
              </td>
              <td>
              $8.99
              </td>
            </tr>
            <tr>
              <td>
              Chicken Salad Sandwich
              </td>
              <td>
                <img src="menu_pics/chicken_salad_sandwich.jpg" alt="Chicken Salad Sandwich">
              </td>
              <td>
              Our world famous chicken salad on a bagel with homemade pickles
              </td>
              <td>
              $8.99
              </td>
            </tr>
            <tr>
              <td>
              Buffalo Chicken Sandwich
              </td>
              <td>
                <img src="menu_pics/buffalo_chicken_sandwich.jpg" alt="Buffalo Chicken Sandwich">
              </td>
              <td>
              Spicy fried chicken on a brioche bun
              </td>
              <td>
                $10.99
              </td>
            </tr>
            <tr>
              <td>
              Fries
              </td>
              <td>
                <img src="menu_pics/fries.jpeg" alt="French Fries">
              </td>
              <td>
              Hand cut potatoes lightly fried and seasoned.
              </td>
              <td>
              $1.99
              </td>
            </tr>
            <tr>
              <td>
              Soda
              </td>
              <td>
                <img src="menu_pics/soda.jpeg" alt="Soda">
              </td>
              <td>
              Regular, diet, orange, or root beer
              </td>
              <td>
              $1.00
              </td>
            </tr>
          </tbody>
        </table>
      </section>
      <section>
        <form action ="form.php" method="post">
          <fieldset>
            <ledgend>
            Reservation           Form
            </ledgend>
            <label for = "nameInput"> First Name
            <input type = "text", id = "nameInput">
            </label>
            <label for = "lastnameInput">Last Name
            <input type = "text" id = "lastnameInput">
            </label>
            <label for = "emailInput">Email Address
            <input type = "email" id = "emailInput" placeholder = "name@domain.com">
            </label>
            <label for = "telInput">Telephone Number
            <input type = "tel" id = "telInput">
            </label>
            <label for = "timeDin">Time
            <select name = "Time" id = "timeDin">
              <option value = "earlyDinner">5:00pm</option>
              <option value = "custWave1">7:00pm
              </option>
              <option value = "custWave2">8:00pm
              </option>
              <option value = "custWave3">9:00pm
              </option>
              <option value = "lastWave">10:00pm
              </option>
            </select>
            </label>
            <textarea col = "200" row = "200">
              Anything we should know?
            </textarea>
            <input type = "submit" value = "Submit">
          </fieldset>
        </form>
      </section>
  	<footer>
        <p>Copyright Notice
        </p>
      </footer>
    </body>
  </html>

  ```
