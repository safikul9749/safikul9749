

<!---
safikul9749/safikul9749 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

<html>

<head>
    <title>form create</title>
</head>
  <style>
    input[type=text],select{
    width: 60%;
    padding:5px 5px;
    margin:8px 0;
    display:inline-block;
    border:1px solid #ccc;
    border-radious:4px;
    box-sizing:border-box
    }
     input[type=text],select{
    width: 60%;
    background-color: #4CAF50;
    color:white;
    padding:5px 5px;
    margin:8px 0;
    border:none;
    border-radious:4px;
    cursor:pointer;
    }
    
    input[type=email],select{
    width: 60%;
    background-color: #4CAF50;
    color:white;
    padding:5px 5px;
    margin:8px 0;
    border:none;
    border-radious:4px;
    cursor:pointer;
    }
    
    input[type=password],select{
    width: 40%;
    background-color: #4CAF50;
    color:white;
    padding:5px 5px;
    margin:4px 0;
    border:none;
    border-radious:4px;
    cursor:pointer;
    }
    
    input[type=submit]:hover{
    background-color: #45a049;
    }
    
    div{
    border-radious:5px;
    background-color:#f2f2f2;
    padding:20px
    }
    
  </style>

<body>
    <form>
        <label for="fname">First name:</label><br>
        <input type="text" id="fname" name="fname" placeholder="your first name" required><br>
          
        <label for="lname">Last name:</label><br>
        <input type="text" id="lname" name="lname" placeholder="last name" required><br>
          
        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email" placeholder="email" required><br>
          
        <label for="password">Password:</label><br>
        <input type="password" id="password" name="password" placeholder="password" required><br>
          
        <input type="submit" value="submit">

 </form>
</body>

</html>
