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
<HTML>
    <H1>HTML ORDERED LIST</H1>
    <ol type="i">
        <li>Mekatilili Wamenza</li>
        <li>Nelson  Mandela</li>
        <li>Julius Nyerere</li>
        <li>Jomo Kenyatta</li>
        <li>Mabuto seseko</li>
        <li>Nabongo Mumia</li>
    </ol>
    <img src="styleheel.jpg" alt="high heel black boot" height="300" width="300">
    <table border="1">
        <thead>
            <tr>
            <th>NAME</th>
            <th>ADDRESS</th>
            <th>MOBILE</th>
            <th>EMAIL</th>
            </tr>
        </thead>
        <tbody>
            <tr>
            <td>SAMUEL</td>
            <td>30, NAIROBI</td>
            <td>5236148</td>
            <td>samuel@plp.com</td>
            <tr>
                <tr>
                    <td>Joy</td>
                    <td>100, SEATTLE</td>
                    <td>254973</td>
                    <td>joy@gmail.com</td>
                </tr>
                <tr>
                    <td>Precious</td>
                    <td>89, RIVER ROAD</td>
                    <td>591268</td>
                    <td>precious@email.com</td>
                </tr>
                <tr>
                    <td>Peter</td>
                    <td>14, PEPONI</td>
                    <td>7821660</td>
                    <td>peter@gmail.com</td>
                </tr>
                <tr>
                    <td>John</td>
                    <td>5, DALLAS</td>
                    <td>25478926</td>
                    <td>John@gmail.com</td>
                </tr>
       </tbody>
    </table>
    <h1>HTML FORM</h1>
    <form action="" method="">
    <label for="name">Name:</label>
    <input type="text" id="student name" name="student name" required>
    <br><br>
    <label for="email">Email:</label>
    <input type="checkbox" name=" email" value="John@gmail.com">John@gmail.com
    <input type="checkbox" name=" email" value="peter@gmail.com">peter@gmail.com
    <input type="checkbox" name=" email" value="precious@email.com">precious@email.com
    <input type="checkbox" name=" email" value="joy@gmail.com">joy@gmail.com
    <input type="checkbox" name=" email" value="samuel@plp.com">samuel@plp.com

    <br><br>

    <label for="password">Password:</label>
    <input type="text" id="password" required>
    <br><br>

    <label for="date"></label>
    <select name="date" id="date"> 
    <option>--- Select Month---</option>
    <option  value="JANUARY">JANUARY</option>
    <option  value="FEBRUARY">FEBRUARY</option>
    <option  value="MARCH">MARCH</option>
    <option  value="APRIL">APRIL</option>
    <option  value="MAY">MAY</option>
    <option  value="JUNE">JUNE</option>
    <option  value="JULY">JULY</option>
    <option  value="AUGUST">AUGUST</option>
    <option  value="SEPTEMBER">SEPTEMBER</option>
    <option  value="OCTOBER">OCTOBER</option>
    <option  value="NOVEMBER">NOVEMBER</option>
    <option  value="DECEMBER">DECEMBER</option>

     <br><br>

    </form>
</HTML>
