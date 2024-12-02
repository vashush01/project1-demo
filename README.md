# project1-demo
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Forms-lets learn</title>
</head>
<body>
    <h1>Form to Apply For Sigma web Dev Course-TA</h1>
    <form action="post">
        <div>
            <label for="username">ENTER YOUR NAME</label>
            <input type="text" id="username" name="username"placeholder="Enter your username" autofocus>
            </div>
            <div>
                <input type="radio"id="male"name="gender"value="male">
                <label for="male">MALE</label>
                <input type="radio"id="female"name="gender"value="female">
                <label for="female">FEMALE</label>
                </div>
                <div>
                    <input type="checkbox"id="subscribe"name="subscribe" value="yes">
                    <label for="subscribe">Subscribe For New Content</label>
                    
                </div>
                <div>
                    <textarea name="comment" rows="4" cols="50">Enter your comment here...
                  </textarea>
                </div>
                <div>
                    <select name="fruits">
                        <option value="apple">Apple</option>
                        <option value="banana">Banana</option>
                        <option value="cherry">Cherry</option>
                  </select>
                </div>
    </form>




            
</body>
</html>
