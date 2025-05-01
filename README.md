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
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Multimedia-Rich Webpage</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
    }
    table, th, td {
      border: 1px solid #333;
      border-collapse: collapse;
      padding: 8px;
    }
    form {
      margin-top: 20px;
    }
  </style>
</head>
<body>

  <!-- Heading -->
  <h1>Welcome to My Multimedia Page</h1>

  <!-- Ordered List with Roman Numerals -->
  <h2>My Top 3 Hobbies</h2>
  <ol type="I">
    <li>Reading</li>
    <li>Traveling</li>
    <li>Coding</li>
  </ol>

  <!-- Embedded Image -->
  <h2>Featured Image</h2>
  <img src="https://images.pexels.com/photos/414171/pexels-photo-414171.jpeg" alt="Nature Scene" width="400">

  <!-- Table of Contacts -->
  <h2>Contact List</h2>
  <table>
    <tr>
      <th>Name</th>
      <th>Address</th>
      <th>Mobile</th>
      <th>Email</th>
    </tr>
    <tr>
      <td>Alice</td>
      <td>Nairobi</td>
      <td>0712345678</td>
      <td>alice@example.com</td>
    </tr>
    <tr>
      <td>Bob</td>
      <td>Kisumu</td>
      <td>0723456789</td>
      <td>bob@example.com</td>
    </tr>
    <tr>
      <td>Carol</td>
      <td>Mombasa</td>
      <td>0734567890</td>
      <td>carol@example.com</td>
    </tr>
    <tr>
      <td>Dan</td>
      <td>Nakuru</td>
      <td>0745678901</td>
      <td>dan@example.com</td>
    </tr>
    <tr>
      <td>Eva</td>
      <td>Eldoret</td>
      <td>0756789012</td>
      <td>eva@example.com</td>
    </tr>
  </table>

  <!-- Registration Form -->
  <h2>Register Here</h2>
  <form>
    <label for="name">Name:</label><br>
    <input type="text" id="name" name="name" required placeholder="Enter your full name"><br><br>

    <label for="email">Email:</label><br>
    <input type="email" id="email" name="email" required placeholder="Enter your email"><br><br>

    <label for="password">Password:</label><br>
    <input type="password" id="password" name="password" required minlength="6" placeholder="Create a password"><br><br>

    <label for="dob">Date of Birth:</label><br>
    <input type="date" id="dob" name="dob" required><br><br>

    <label for="gender">Gender:</label><br>
    <input type="radio" name="gender" value="Male" required> Male
    <input type="radio" name="gender" value="Female" required> Female<br><br>

    <label for="country">Country:</label><br>
    <select id="country" name="country" required>
      <option value="">--Select--</option>
      <option value="Kenya">Kenya</option>
      <option value="Uganda">Uganda</option>
      <option value="Tanzania">Tanzania</option>
    </select><br><br>

    <label>Interests:</label><br>
    <input type="checkbox" name="interests" value="Music"> Music
    <input type="checkbox" name="interests" value="Sports"> Sports
    <input type="checkbox" name="interests" value="Tech"> Tech<br><br>

    <input type="submit" value="Register">
  </form>

  <!-- Embedded Audio -->
  <h2>Sample Audio</h2>
  <audio controls>
    <source src="https://www.w3schools.com/html/horse.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
  </audio>

  <!-- Embedded Video -->
  <h2>Sample Video</h2>
  <video width="400" controls>
    <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>

</body>
</html>
