# Week-2-Assignment-web-development
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Advanced HTML5 Elements</title>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid black;
            padding: 8px;
            text-align: left;
        }
        th {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>

    <!-- Ordered List with Roman Numerals -->
    <h2>Ordered List with Roman Numerals</h2>
    <ol type="I">
        <li>First Item</li>
        <li>Second Item</li>
        <li>Third Item</li>
        <li>Fourth Item</li>
        <li>Fifth Item</li>
    </ol>

    <!-- External Image from Pexels -->
    <h2>Image from Pexels</h2>
    <img src="https://www.pexels.com/photo/sunset-over-mountains-123123/" alt="Sunset Over Mountains" width="600">

    <!-- Contact Table -->
    <h2>Contact List</h2>
    <table>
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
                <td>Faheem Wesonga</td>
                <td>East Wanga, Kakamega</td>
                <td>+254703682427</td>
                <td>faiwesonga@gmail.com</td>
            </tr>
            <tr>
                <td>Akinyi Otieno</td>
                <td>Kisumu, Kenya</td>
                <td>+254712345678</td>
                <td>akinyi.otieno@example.com</td>
            </tr>
            <tr>
                <td>Kofi Mensah</td>
                <td>Accra, Ghana</td>
                <td>+233501234567</td>
                <td>kofi.mensah@example.com</td>
            </tr>
            <tr>
                <td>Zainab Jalloh</td>
                <td>Freetown, Sierra Leone</td>
                <td>+23278123456</td>
                <td>zainab.jalloh@example.com</td>
            </tr>
            <tr>
                <td>Thabo Dlamini</td>
                <td>Johannesburg, South Africa</td>
                <td>+27712345678</td>
                <td>thabo.dlamini@example.com</td>
            </tr>
        </tbody>
    </table>

    <!-- Registration Form -->
    <h2>Registration Form</h2>
    <form action="#" method="POST">
        <!-- Name Field -->
        <label for="name">Full Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your full name" required>
        <br><br>

        <!-- Email Field -->
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email" required>
        <br><br>

        <!-- Password Field -->
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Enter password" required>
        <br><br>

        <!-- Date of Birth Field -->
        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required>
        <br><br>

        <!-- Dropdown List -->
        <label for="country">Select Country:</label>
        <select id="country" name="country" required>
            <option value="">--Choose--</option>
            <option value="Kenya">Kenya</option>
            <option value="Ghana">Ghana</option>
            <option value="Nigeria">Nigeria</option>
            <option value="South Africa">South Africa</option>
        </select>
        <br><br>

        <!-- Radio Buttons -->
        <label>Gender:</label>
        <input type="radio" id="male" name="gender" value="male" required>
        <label for="male">Male</label>
        <input type="radio" id="female" name="gender" value="female" required>
        <label for="female">Female</label>
        <input type="radio" id="other" name="gender" value="other" required>
        <label for="other">Other</label>
        <br><br>

        <!-- Checkboxes -->
        <label>Interests:</label>
        <input type="checkbox" id="coding" name="interests" value="coding">
        <label for="coding">Coding</label>
        <input type="checkbox" id="sports" name="interests" value="sports">
        <label for="sports">Sports</label>
        <input type="checkbox" id="music" name="interests" value="music">
        <label for="music">Music</label>
        <br><br>

        <!-- Submit Button -->
        <button type="submit">Register</button>
    </form>

</body>
</html>
