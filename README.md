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
- 

Happy Coding! 💻✨
<!doctype html>
<html lang="en">
<html>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>index2</title>
    <body>
        <h1>Advanced HTML Elements and Forms Assignment</h1>
        <!--Ordered List With Roman Numerals-->
        <h2>Ordered List</h2>
        <ol start="i">
            <p>Below is an ordered list of my daily routine:</p>
            <li>Wake up ,make bed and brush teeth</li>
            <li>Workout in the gym</li>
            <li>Take breakfast and do dishes</li>
            <li>Walk to school</li>
            <li>Attend classes</li>
            </ol>
<!--adding an image--> 
<h2>Sample Image</h2>           
<img source src="https://images.pexels.com/photos/1108099/pexels-photo-1108099.jpeg"alt="Cute Puppies" width="300" height="200">
<!--creating a table-->
<h2>Table</h2>
        <table border="1" >
            <tr><th>Name</th><th>Address</th><th>Mobile</th><th>Emails</th></tr>
            <tr><td>seruma</td><td>Rongai</td><td>07848683778</td><td>serumajidu@gmail.com</td></tr>
            <tr><td>Mitchelle</td><td>Nairobi</td><td>079988737678</td><td>mitcheldoeij@gmail.com</td></tr>  
            <tr><td>zawadi</td><td>nakuru</td><td>5084653847595</td><td>zawaditadoij@gmail.com</td></tr>
            <tr><td>flora</td><td>naivasha</td><td>90853847595</td><td>floramktaij@gmail.com</td></tr>
            <tr><td>vaseline</td><td>botile</td><td>567653847595</td><td>vaselebotilej@gmail.com</td></tr>
            </table>


            
<!--creating a registration form-->
<form>
<!--creating label for name-->    
    <label for="name" >Name: </label>
    <input type="text" id="name" name="name" placeholder="Enter your name" required>
    <br>
<!--creating label for email-->    
    <label for="email">Email:</label>
    <input typr="email" id="email" name="email" placeholder="enter your email" required>
    <br>
<!--creating label for password-->  
    <label for="password">Password:</label>
    <input type="password" id="password" name="password" placeholder="Enter your password" required>
    <br>
<!--creating label for date-->    
    <label for ="date">Date:</label>
    <input type="date" id="date" name="date" required>
    <br>
<!--creating input radio-->      
    <label for="gender">Gender:</label>
            <input type="radio" id="male" name="gender" value="male" required> Male
            <input type="radio" id="female" name="gender" value="female"> Female
            <input type="radio" id="other" name="gender" value="other"> Other
            <br>
<!--creating select dropdown options-->              
    <label for="country">Country:</label>
            <select id="country" name="country" required>
                <option value="">Select your country</option>
                <option value="kenya">Kenya</option>
                <option value="uganda">Uganda</option>
                <option value="tanzania">Tanzania</option>
            </select>
            <br>
<!--creating checkbox-->
            <label>Interests:</label>
            <input type="checkbox" name="interests" value="coding"> Coding
            <input type="checkbox" name="interests" value="sports"> Sports
            <input type="checkbox" name="interests" value="music"> Music
            <br>
<!--creating submit button-->          
            <button type="submit">Submit</button>
<!--crrating register button-->
            <button type="submit">Register</button>
    </form>

</body>
</html>
