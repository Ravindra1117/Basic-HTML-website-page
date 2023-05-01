# Basic-HTML-website-page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>1st HTML & CSS project</title>
    <style>
        *{
            margin:10;
            padding:10;
        }
        div{
            background-position: right;
        }
        body{
            background-image: url("https://imgs.search.brave.com/OD-M-fmTNdbEF54nHCUesZVVNBJT1eiO-Yo3AmugvXg/rs:fit:1200:1200:1/g:ce/aHR0cHM6Ly9zdGF0/aWMudmVjdGVlenku/Y29tL3N5c3RlbS9y/ZXNvdXJjZXMvcHJl/dmlld3MvMDAwLzY2/NS80OTQvb3JpZ2lu/YWwvZnV0dXJpc3Rp/Yy1saWdodGluZy1l/ZmZlY3Qtb24tcmVk/LWNvbG9yLXRvbmUt/YmFja2dyb3VuZC12/ZWN0b3IuanBn");
            background-size: 3000px;
            background-repeat:no-repeat;
            
        }
        .menu
        {
            display: inline;
            height: 10pxl;
            background-position-x: center; */
            background-color: rgb(87, 119, 119);
           
        }
        .red{
            border: 5px solid black;
            width: fit-content;
        }
        .user
        {
            position: absolute;
            right: 500px;
            width: 300px;
            border: 3px solid #4221ad;
            padding: 40px;
        
        }
        #radio {
            accent-color: #13d83e;
        }
        
    </style>
</head>
<body>
    <header>
        DEMO LOGIN PAGE....
    </header>
    <main>
        <div class="menu">
            <ul type="circle">
            <li>HOME</li>
            <li>ABOUT</li>
            <li>CONTACT US</li>
        </div>
    <div class="user">
        <form>
            <h4>SIGN UP FOR DEMO</h4>
            Name : <input type="text" name="user_name" size="10" value="e.g. meher21" maxlength="10"><br>
            <br>
            last name : <input type="text" name="user_name" size="10" value="e.g. xyz" maxlength="10"><br>
            <br>
            email ID : <input type="text" name="user_pass" ><br>
            <br>
            Password : <input type="password" name="user_pass" ><br>
            <br>
            Contact number : <input type="number" name="user_pass" size="10"><br>
            <h5>Meals :
                <input type="checkbox" name="c_male" checked> yes
                <input type="checkbox" name="c_female"> no
            </h5>
            <input type="radio" name="r_gender"> Male
                <input type="radio" name="r_gender"> Female
                <input type="radio" name="r_gender" checked> infant
                <br><br>
            Address proof:
            <br>
            <input type="file">
            <br><br>
            <!-- <input type="Sign up" name="b_Sign up" value="Sign up"/><br> -->
            <input type="button" onclick="alert('Sign up')" name="b_alert" value="Sign up"/><br>
            <br>
            <div class="red">
                <textarea name="explain" id="explain" cols="30" rows="10">"give us feedback"</textarea>
            </div>
            <!-- <textarea name="explain" id="explain" cols="30" rows="10">"give us feedback"</textarea>
        </div>
    </main> 
</body
</html>
