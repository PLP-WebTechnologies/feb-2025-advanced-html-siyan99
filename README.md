<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Assignment</title>
</head>
<body>
    <!-- Ordered List with Roman Numerals -->
    <h1>Ordered List</h1>
    <ol type="I">
        <li>Introduction to HTML</li>
        <li>CSS Basics</li>
        <li>JavaScript Fundamentals</li>
        <li>Responsive Design</li>
        <li>Web Development Tools</li>
    </ol>

    <!-- External Image from Pexels -->
    <h1>External Image</h1>
    <img src="https://images.pexels.com/photos/414612/pexels-photo-414612.jpeg" alt="Sample Image from Pexels" width="500">

    <!-- Table of Contacts -->
    <h1>Contacts Table</h1>
    <table border="1" cellpadding="10" cellspacing="0">
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
                <td>Stephen lomongin</td>
                <td>123 Main St</td>
                <td>+1234567890</td>
                <td>stephenlomongin99@gmail.com</td>
            </tr>
            <tr>
                <td>Jane Smith</td>
                <td>456 Elm St</td>
                <td>+9876543210</td>
                <td>jane.smith@gmail.com</td>
            </tr>
            <tr>
                <td>Michael Brown</td>
                <td>789 Oak St</td>
                <td>+1122334455</td>
                <td>michael.brown@gmail.com</td>
            </tr>
            <tr>
                <td>Emily Davis</td>
                <td>321 Pine St</td>
                <td>+2233445566</td>
                <td>emily.davis@gmail.com</td>
            </tr>
            <tr>
                <td>Chris Wilson</td>
                <td>654 Maple St</td>
                <td>+3344556677</td>
                <td>chris.wilson@gmail.com</td>
            </tr>
        </tbody>
    </table>

    <!-- Registration Form -->
    <h1>Registration Form</h1>
    <form action="" method="post">
        <!-- Name Field -->
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your name" required>
        <br><br>

        <!-- Email Field -->
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email" required>
        <br><br>

        <!-- Password Field -->
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Enter your password" required minlength="6">
        <br><br>

        <!-- Date Field -->
        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required>
        <br><br>

        <!-- Dropdown -->
        <label for="country">Country:</label>
        <select id="country" name="country" required>
            <option value="">Select your country</option>
            <option value="Kenya">Kenya</option>
            <option value="Uganda">Uganda</option>
            <option value="Tanzania">Tanzania</option>
        </select>
        <br><br>

        <!-- Radio Buttons -->
        <label>Gender:</label>
        <input type="radio" id="male" name="gender" value="male" required>
        <label for="male">Male</label>
        <input type="radio" id="female" name="gender" value="female" required>
        <label for="female">Female</label>
        <br><br>

        <!-- Checkboxes -->
        <label>Hobbies:</label>
        <input type="checkbox" id="sports" name="hobbies" value="sports">
        <label for="sports">Sports</label>
        <input type="checkbox" id="reading" name="hobbies" value="reading">
        <label for="reading">Reading</label>
        <input type="checkbox" id="traveling" name="hobbies" value="traveling">
        <label for="traveling">Traveling</label>
        <br><br>

        <!-- Submit and Reset Buttons -->
        <button type="submit">Register</button>
        <input type="reset" value="Reset">
    </form>
</body>
</html>
