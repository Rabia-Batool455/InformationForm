# InformationForm
#My First Information Form Using HTML and CSS
#Rabia Batool
#This form is designed for the purpose of information regarding a student or a person
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Report Form</title>
</head>
<body>
    <table border="1"  width="50%" style="margin-left: auto; margin-right: auto;" >
        <tr>
            <td colspan="3" style="color: black; text-align: center; height: 30px; font-size: 25px;"><b>Report Form</b> </td>
        </tr>
        <tr>
            <td colspan="5" style="background-color: black; color: powderblue; text-align: center; height: 40px; font-size: 30px;">Information Table</td>
        </tr>
        <tr>
            <th style="text-align: right;">NAME</th>
            <td><form >
                <input type="text"><br>
                <label style="color: blue;">Enter Your Full Name</label>    
            </form></td>
        
        </tr>
        <tr>
            <th style="text-align: right;">EMAIL</th>
            <td><form >
                <input type="email"><br>
                <label style="color: blue;" >Enter an Internet Contact Address</label>    
            </form></td>  
        </tr>
        <tr>
            <th style="text-align: right;">PASSWORD</th>
            <td><form >
                <input type="password"><br>
                <label style="color: blue;" >Enter a Code to Identify You</label>    
            </form></td>
        </tr>
        <tr>
            <th style="text-align: right;">ADDRESS</th>
            <td><form >
                <input type="text"><br>
                <label style="color: blue;">Complete Address</label>    
            </form></td><br>
        </tr>
        <tr>
            <th style="text-align: right;">COUNTRY</th>
            <td><form >
                <select name="Country" >
                    <option value="America">Pakistan</option>
                    <option value="China">India</option>
                    <option value="Fantie">China</option>
                    <option value="Goward">America</option>
                    <option value="Nepal">Nepal</option>
                    <option value="Malta">Austria</option>
                    <option value="Ostria">Malta</option>

                </select>     
            </form></td>
        </tr>
        <tr>
            <th style="text-align: right ;">GENDER</th>
            <td><form >
                <input type="radio"name="male"value="male" >MALE
                <input type="radio"name="male"value="female">FEMALE
            </form></td>
            
        </tr>
        <tr>
            <th style="text-align: right ;">HOBBIES</th>
            <td>
                <form >
                    <input type="checkbox">Reading <br>
                    <input type="checkbox">Listening Music <br>
                    <input type="checkbox">Gardening <br>
                    <input type="checkbox">Swimming <br>
                    <input type="checkbox">Athletics <br>
                    <label >Check All That Apply</label>


                </form>
            </td>
        </tr>
        <tr>
            <form >
                <th style="text-align: right ;">Your Website</th>
                <td input type="url"><textarea cols="30" rows="1" placeholder="http://"></textarea><br>
                    <label style="color: blue;">Provide Your Website URL if Exists(Not Necessary)</label></td>
            </form>
        </tr>
        <tr>
            <form >
                <th style="text-align: right ;">OTHER INFORMATION ABOUT YOU</th>
                <td><textarea type="text" rows="4" cols="30"></textarea><br>
                </td>
            </form>
        </tr>
        <tr>
            <form >
                <td style="text-align: right;"><input type="submit" value="Send in my Report"></td>
                <td><input type="reset" value="Erase Report Form"></td>
            </form>
        </tr>

    </table>
</body>
</html>
