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
    <title>Document</title>
</head>
<body>
    <h2>css elements</h2>
    <ol type="i">
        <li>font-size</li>
        <li>font-family</li>
        <li>font-weight</li>
    </ol>
    <img src="code.jpg"alt= "coding image"width="150"height
    ="150">
    <table border 1> 
       <caption>personal details</caption>
       <thead>
        <tr>
            <th>name</th>
            <th>address</th>
            <th>mobile</th>
            <th>email</th>
        </tr>
       </thead>
       <tbody>
        <tr>
            <td>Jeremy</td>
            <td>1749</td>
            <td>+254 790405011</td>
            <td>mainajeremyk@gmail.com</td>
        </tr>
        <tr>
            <td>Jeremy</td>
            <td>1749</td>
            <td>+254 790406611</td>
            <td>mainajeremyk@gmail.com</td>
        </tr>
        <tr>  <td>Jeremy</td>
            <td>1749</td>
            <td>+254 790406611</td>
            <td>mainajeremyk@gmail.com</td>
        </tr>
        <tr>  <td>Jeremy</td>
            <td>1749</td>
            <td>+254 790406611</td>
            <td>mainajeremyk@gmail.com</td>
        </tr>
        <tr>  <td>Jeremy</td>
            <td>1749</td>
            <td>+254 790406611</td>
            <td>mainajeremyk@gmail.com</td>
        </tr>
       </tbody>
    </table>

    <h3>regestration form</h3>
    <label for="name">name</label>" 
    <input type=""text" id="name"name="name"required>
    <br><br>
    <label for="email">email</label>
    <input type="email" name="email" placeholder="enter your email"
    <br><br>
    <label for="country">country</label>
    <select name="country" id="country">
        <option>--select country--</option>
        <option value="Kenya">Kenya</option>
        <option value="Ghana">Ghana</option>
    </select>
    <label for"description">Describe yourself</label>
    <textarea id="description"name="description">
        
    </textarea>
</body>
</html>
