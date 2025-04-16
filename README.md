# Advanced-HTML-5-elements web development 2
Lists, forms, tables and images
<!DOCTYPE html>
    <html lang="en">
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>Introduction to the advanced html 5</title>
        </head>
        <body>
            <!--This section is about the lists and types of lists (line 10-35)-->
            <h2>LISTS</h2>
            <P>There are 3 types of lists, they are:</P>
            <p>The ordered lists, the Unordered lists and the Definition lists</p>
            <h3>The Ordered Lists</h3>
            <ol type="I" start="1">
                <li>Name</li>
                <li>Religion</li>
                <li>Gender</li>
                <li>Marital Status</li>
            </ol>
            <h3>The Unordered Lists</h3>
            <ul type="square">
                <li>Name</li>
                <li>Religion</li>
                <li>Gender</li>
                <li>Marital Status</li>
            </ul>
            <h3>The Definition Lists</h3>
            <dl>
                <dt>CIA</dt>
                    <dd>Central Intelligence Agency</dd>
                <dt>FBI</dt>
                    <dd>Federal Bereau of Investigation</dd>
                <dt>NPF</dt>
                    <dd>Nigeria Police Force</dd>
            </dl>
            <!--This is the end of lists-->

            <!--This is the image use section (Line 39-40)-->
            <h3>Image</h3>
            <img src="https://images.pexels.com/photos/2036656/pexels-photo-2036656.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="A you have been hacked message " height="300" weight="400">
            <!--This is the end of the image section-->

            <!--This is the Table creation Section (Line 44-96)-->
            <h3>Tables</h3>
            <table border="4">
                    <caption>Members Info</caption>
                <thead>
                    <tr>
                        <th>Name</th>
                        <th>Address</th>
                        <th>Mobile No.</th>
                        <th>Emails</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Alanwoko</td>
                        <td>23, Adeite Street, Lagos, Nigeria</td>
                        <td>+2348162789938</td>
                        <td>calanwoko@gmail.com</td>
                    </tr>
                    <tr>
                        <td>Marshall</td>
                        <td>8, Adebanwo Street, Lagos, Nigeria</td>
                        <td>+2348032755424</td>
                        <td>alanwokoc@gmail.com</td>
                    </tr>
                    <tr>
                        <td>Stephen</td>
                        <td>10, Otunda Bakare, Lagos, Nigeria</td>
                        <td>+2348038512464</td>
                        <td>Ngozidoris@gmail.com</td>
                    </tr>
                    <tr>
                        <td>Kamal</td>
                        <td>12, Oyegunle Street, Lagos, Nigeria</td>
                        <td>+2348054281600</td>
                        <td>boniface@gmail.com</td>
                    </tr>
                    <tr>
                        <td>Chibundu</td>
                        <td>34, Olorunfunmi, Lagos, Nigeria</td>
                        <td>+2348055640088</td>
                        <td>Chibundu@gmail.com</td>

                    </tr>
                </tbody>
                <tfoot>
                    <tr>
                        <th>Name</th>
                        <th>Address</th>
                        <th>Mobile No.</th>
                        <th>Emails</th>
                    </tr>  
                </tfoot>
            </table>
            <!--This is the end of the table Creation Section-->

            <!--Thia is the Forms Section (Line 99-145)-->
            <h3>Forms</h3>
            <form action="" method="">
                <!--This is for the text field form section -->
                <label for="Full_name">Full name:</label>
                <input type="text" id="Full_name" name="Full_name" placeholder="Please fill in your correct names" required>
            <br><br>
                <label for="Date">DOB:</label>
                <input type="date" id="Date" name="dob"required>
                <br><br>
                <label for="Email">Email:</label>
                <input type="email" id="Email" name="Email" placeholder="Your Email address"required>
            <br><br>
                <label for="Password">Password:</label>
                <input type="Password" id="Password" name="Password" placeholder="Your password here" required>
            <br><br>

                <!--This is for the Radio button form section -->
                <label for="Gender">Gender:</label>
                <input type="radio" name="Gender"  value="Male"required>Male</input>
                <input type="radio" name="Gender"  value="Female"required>Female</input>
            <br><br>

                <!--This is for the Checkboxes form section -->
                <label for="Languages">Languages:</label>
                <input type="checkbox" value="English">English</input>
                <input type="checkbox" value="French">French</input>
                <input type="checkbox" value="Tamil">Tamil</input>
                <input type="checkbox" value="Spanish">Spanish</input>
                <input type="checkbox" value="Pidgin English">Pidgin English</input>
                <input type="checkbox" value="Swahili">Swahili</input>
            <br><br>

                <!--This is for the dropdown form section -->
                <label for="Country">Country:</label>
                <select name="Country" id="Country" name="Country">
                    <option value="America">America</option>
                    <option value="Botswana">Botswana</option>
                    <option value="China">China</option>
                    <option value="Denmark">Denmark</option>
                    <option value="Ethopia">Ethopia</option>
                    <option value="Finland">Finland</option>
                </select>
            <br><br>
            <input type="submit" value="Register">
            <input type="reset" value="Reset">
            <button type="next">next</button>
            <!--This is the end of the Form Section-->
            <br><br>
                
            </form>
        </body>
    </html>
