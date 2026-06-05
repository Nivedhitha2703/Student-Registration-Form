# Student-Registration-Form
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width,initial-scale=1.0">
        <title> Registration Form </title>
    </head>
    <body bgcolor="peachpuff">
        <h1> Student Registration Form </h1>
        <form action="">
            <label for=""> Roll no.: </label>
            <input type="number"><br><br>

            <label for=""> Student Name: </label>
            <input type="text" placeholder="First Name">
            <input type="text" placeholder="Last Name"><br><br>

            <label for=""> Father's Name: </label>
            <input type="text"><br><br> 

            <label for="">Date of Birth: </label>
            <select>
                <option> Date </option>
            </select>
            <select>
                <option> Month </option>
            </select>
            <select>
                <option> Year </option>
            </select>
            (DD-MM-YYYY)
            <br><br>

            <label for=""> Mobile no.: </label>
            <input type="text" value="+91" size="3">
            <input type="tel"><br><br>

            <label for=""> E-mail id: </label>
            <input type="email"><br><br>

            <label for=""> Password: </label>
            <input type="password"><br><br>

            <label for=""> Gender: </label>
            <input type="radio" name="gender"> Male
            <input type="radio" name="gender"> Female
            <br><br>

            <label for=""> Department: </label>
            <input type="checkbox"> CSE 
            <input type="checkbox"> IT
            <input type="checkbox"> ECE
            <input type="checkbox"> Civil
            <input type="checkbox"> Mech
            <br><br>

            <label for=""> Course: </label>
            <select>
                <option>  ----Select Current Course---- </option>
                <option> CSE </option>
                <option> IT </option>
                <option> ECE </option>
                <option> Civil </option>
                <option> Mechanical </option>
            </select>
            <br><br>

            <label for=""> Student Photo: </label>
            <input type="file"> <br><br>

            <label for=""> City: </label>
            <input type="text"><br><br>

            <label for=""> Address: </label><br><br>
            <textarea rows="5" cols="40"></textarea>

            <input type="submit" value="Register">
        </form>
    </body>
</html>
