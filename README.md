<!DOCTYPE html>
    <html>
        <head>
            <title>HTML Elements & Forms Assignment</title>
        </head>
        <body>
            <h1>Ordered Lists</h1>
            <ol type="i" start="i">
                <li>Software Development</li>
                <li>Python</li>
                <li>Web Development</li>
                <li>Database</li>
                <li>Startup Building</li>
            </ol>
            
            <h1>Image</h1>
            <img src="Mustang.jpg" alt="A black Ford Mustang" width="450" height="350">

            <h1>Table</h1>
            <table border="1">
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
                        <td>Fredrick Maeba</td>
                        <td>Nairobi</td>
                        <td>+254 707 156 485</td>
                        <td>fredmaeba07@gmail.com</td>
                    </tr>
                    <tr>
                        <td>Chakin Oeba</td>
                        <td>Nairobi</td>
                        <td>+254 707 456 485</td>
                        <td>chakin@outlook.com</td>
                    </tr>
                    <tr>
                        <td>Ms. Nelly Odhiambo</td>
                        <td>Casablanca</td>
                        <td>+234 726 909 485</td>
                        <td>nelly@yahoo.com</td>
                    </tr>
                    <tr>
                        <td>Ondugu</td>
                        <td>Mogadishu</td>
                        <td>+256 707 156 673</td>
                        <td>ondugu@hotmail.com</td>
                    </tr>
                    <tr>
                        <td>Junior Developer</td>
                        <td>Pretoria</td>
                        <td>+254 745 123 980</td>
                        <td>developer@gmail.com</td>
                    </tr>
                </tbody>
            </table>
            <br><br>
            <h1>Registration Form</h1>
            <form>
                <label for="name">Name:</label>
                <select name="name" id="name">
                    <option>--Select Name--</option>
                    <option value="Fredrick">Fredrick</option>
                    <option value="Ms. Nelly Odhiambo">Ms. Nelly Odh</option>
                    <option value="Ondugu">Ondugu</option>
                    <option value="Chakin">Chakin</option>
                </select>
                <br><br>
                <label for="email">Email:</label>
                <input type="text" id="email_address" name="email_address" required>
                <br><br>
                <label for="password">Password</label>
                <input type="text" id="password" name="password" required>
                <br><br>
                <label for="date">Notice Period/Date:</label>
                <input type="checkbox" name="day" value="day">Day
                <input type="checkbox" name="week" value="week">Week
                <input type="checkbox" name="month" value="month">Month
                <br><br>
                <button>Register</button>
                <input type="button" value="Cancel">
            </form>
        </body>
    </html>
