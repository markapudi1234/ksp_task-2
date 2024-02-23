
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TASK-2</title>
</head>
<body>
    <link rel = "stylesheet" href = "style.css">
    <div class = "H"><h1 id = "Happy">Happy Day Guys</h1></div>
    <div class = "I">
    <a href = "https://careerx.club/" target = "main"><img src = "https://static.theprint.in/wp-content/uploads/2022/06/Image_42022060313452820220603135522.jpg" id = "image"></a>
    </div>
    <p>New Journey, New Beginning , New Intellectual People ✨ 
        I am delighted to embark on a new journey with CareerX Club 😍 , confident that it will pave the way for enhancing my skills and creating opportunities that will propel my future forward. I extend my gratitude to Amarnath KR Sir, and the kick-start session conducted yesterday by Jeeva Haridas Sir was truly enriching.</p>
    <div class = "Table">
    <table>
        <caption>DAILY ACTIVITY</caption>
       <tr>
        <th id = "P">Period of Time</th>
        <th id = "T">Topics Covered</th>
       </tr>
       <tr><th rowspan="4" id = "D">Day 1</th></tr>
       <tr><td id = "Same">Linkedin</td></tr>
       <tr><td id = "Same">Github</td></tr>
       <tr><td id = "Same">vscode</td></tr>
       <tr><th rowspan = "4" id = "D2">Day 2</th></tr>
       <tr><td id = "Same">HTML</td></tr>
       <tr><td id = "Same">CSS</td></tr>
       <tr><td id = "Same">JS</td></tr>
    </table>
    </div>
    <br>
    <br>
    <div class = "List">
    <h3>DAY-2 TOPICS</h3>
    <br>
    <ul><li id = "dec">heading tags
            <h4>In heading tags there are types</h4>
            <ol type = a>
                <li>h1 tag</li>
                <li>h2 tag</li>
                <li>h3 tag</li>
                <li>h4 tag</li>
                <li>h5 tag</li>
                <li>h6 tag</li>
            </ol>
        </li>
        <li id = "dec">para tag</li>
        <li id = "dec">video tag</li>
        <li id = "dec">image tag</li>
        <li id = "dec">comments in HTML</li>
        <li id = "dec">tables</li>
        <li id = "dec">anchor tag</li>
    </ul>
</div>
<!----Beach Video-->
<h2 id = "Beach">
    Here is a Beach Video That makes You calm :)
</h2>
<div class = "Vdo">
<video src = "pexels_videos_1321208 (2160p).mp4" width = "250px" height = "250px" controls></video>
</div>

</body>
</html>
 65 changes: 65 additions & 0 deletions65  
style.css
@@ -0,0 +1,65 @@
.H{
    display: flex;
   justify-content: center;
}
#Happy{
    border: 2px solid black;
    border-radius: 50%;
    padding: 3rem;
    background-color: rgb(219, 219, 138);
    text-align: center;
}
#dec::before{
    content: "\00BB";
}
.Table{
    display: flex;
    justify-content: center;
}
table{
    border: solid black 2px;
}
.List{
    display: flex;
    justify-content: center;
}
#P{
    border: solid black 1px; 
}
#T{
    border: solid black 1px;
}
#D{
    border: solid black 1px;
}
#D2{
    border: solid black 1px;
}
#Same{
    border: solid black 1px;
}
.I{
    display: flex;
    justify-content: center;
}
img{
    justify-content: center;
}
img:hover{
    opacity: 70%;
    cursor: pointer;
}
ol{
    margin: 0%;
}
h4{
    margin: 0%;
}
#Beach{
    text-align: center;
}
.Vdo{
    display: flex;
    justify-content: center;
}

# ksp_task-2
