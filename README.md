# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>HTML5 Multimedia & Form Validation</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

  <!-- Ordered List with Roman Numerals -->
  <section>
    <h2>Ordered List of Tasks</h2>
    <ol type="I">
      <li>Prepare breakfast</li>
      <li>Complete assignment</li>
      <li>Exercise</li>
      <li>Attend meeting</li>
      <li>Relax</li>
    </ol>
  </section>

  <!-- External Image from Pexels -->
  <section>
    <h2>Beautiful Landscape</h2>
    <img src="https://images.pexels.com/photos/207983/pexels-photo-207983.jpeg" alt="Landscape view" style="max-width: 100%; height: auto;">
  </section>

  <!-- Table of Contacts -->
  <section>
    <h2>Contact List</h2>
    <table border="1" cellpadding="10">
      <thead>
        <tr>
          <th>Name</th>
          <th>Address</th>
          <th>Mobile</th>
          <th>Email</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>John Doe</td>
          <td>123 Elm St, City</td>
          <td>555-1234</td>
          <td>johndoe@example.com</td>
        </tr>
        <tr>
          <td>Jane Smith</td>
          <td>456 Oak St, Town</td>
          <td>555-5678</td>
          <td>janesmith@example.com</td>
        </tr>
        <tr>
          <td>Mike Johnson</td>
          <td>789 Pine St, Village</td>
          <td>555-9876</td>
          <td>mikejohnson@example.com</td>
        </tr>
        <tr>
          <td>Emily Davis</td>
          <td>101 Maple St, Suburb</td>
          <td>555-3456</td>
          <td>emilydavis@example.com</td>
        </tr>
        <tr>
          <td>Chris Lee</td>
          <td>202 Birch St, City</td>
          <td>555-6543</td>
          <td>chrislee@example.com</td>
        </tr>
      </tbody>
    </table>
  </section>

  <!-- Registration Form -->
  <section>
    <h2>Registration Form</h2>
    <form action="/submit" method="POST" novalidate>
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" placeholder="Enter your name" required><br><br>

      <label for="email">Email:</label>
      <input type="email" id="email" name="email" placeholder="Enter your email" required><br><br>

      <label for="password">Password:</label>
      <input type="password" id="password" name="password" placeholder="Enter your password" required><br><br>

      <label for="dob">Date of Birth:</label>
      <input type="date" id="dob" name="dob" required><br><br>

      <!-- Dropdown Menu -->
      <label for="country">Country:</label>
      <select id="country" name="country" required>
        <option value="us">United States</option>
        <option value="ca">Canada</option>
        <option value="uk">United Kingdom</option>
      </select><br><br>

      <!-- Radio Buttons -->
      <label>Gender:</label>
      <input type="radio" id="male" name="gender" value="male" required>
      <label for="male">Male</label>
      <input type="radio" id="female" name="gender" value="female">
      <label for="female">Female</label><br><br>

      <!-- Checkboxes -->
      <label for="subscribe">Subscribe to newsletter:</label>
      <input type="checkbox" id="subscribe" name="subscribe" value="yes"><br><br>

      <!-- Submit Button -->
      <button type="submit">Register</button>
    </form>
  </section>

  <!-- Audio Element -->
  <section>
    <h2>Audio Example</h2>
    <audio controls>
      <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mp3">
      Your browser does not support the audio element.
    </audio>
  </section>

  <!-- Video Element -->
  <section>
    <h2>Video Example</h2>
    <video controls width="600">
      <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
      Your browser does not support the video element.
    </video>
  </section>

</body>
</html>

