### What is a good use of the <form> tag, what are its available methods?
The form tag creates an HTML form for user input, tells the browser where the form starts and ends. This tag specifies where to send the for data when it is submitted: absolute or relative URL.

* post-anything such as storing or updating data, ordering product, sending an email, etc...

* get-getting or retrieving data. Should only be used when the form processing is idempotent (no change on self-operation).

#### elements:
* input
* textarea
* button
* select
* option
* optgroup
* fieldset
* label


### List and explain of at least 3 different <input> types.

* button - clickable button, mostly used to activate a script in JavaScript.
* checkbox - used to check something or leave unchecked, useful in list format.
* color-used to take input of color with Hue, Saturation, Luminosity, and RGB scale.
* date-defines a date. Year, month and day. No time.
* email-defines a field for an email address
* file-defines a choose file field that takes to local file search a display chosen file name field.
* hidden-defines a hidden input field. Lets Web Devs include data that is hidden from users, can't be seen or modified. EX: Order id or unique security token.
* image-defines an image and a submit button.
* month-defines a month and year with no time zone. Dropdown choose from calendar.
* number-defines a field for entering a number. The field has scroll option to choose integers that are negative or positive.
* password-defines a field to enter a password, characters entered are masked.
* radio-creates a radio button.
* range-creates a slider or slider control range. default number range 0-100.
* reset-creates a button to reset all form values to default values.
* search-defines a search box for entering a search, will convert everything entered to string.
* submit-defines a submit button.
* tel-defines a field for entering a phone number.
* **text-defines a field for entering text. Default width is 20 char. Default input.**
* time-input time, no time zone.
* url-defines field to enter a URL.
* week-choose a day and month on calendar and define a week. no time zone.

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
            <a href="index.html">Home			</a>
          </li>
          <li>
            <a href ="about.html">About
            </a>
          </li>
          <li>
            <a href="contact.html">Contact Us    </a>
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
            Our world famous chicken salad on a bagel with homemade pickles - $8.99
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
