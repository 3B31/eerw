<!DOCTYPE html>
<html lang="en">

<head>
    <title>3B 31's Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: left; /* Align all text to the left */
            margin: 0; /* Remove default margin */
        }
        .header {
            text-align: center; /* Center the header */
        }
        .photo-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr); /* 3 columns */
            gap: 10px; /* Space between images */
            justify-items: center; /* Center images in their grid cells */
            margin: 20px auto; /* Center grid in the page */
        }
        .input-container {
            margin: 20px; /* Add some margin */
            max-width: 400px; /* Set a maximum width for the input container */
        }
    </style>
</head>

<body>

<h1 class="header" style="background-color: #42f5ef; font-size: 40px;">3B 31's Website</h1>

<p style="font-size: 25px; background-color: Yellow;">
    I am <span style="color: red;">Jacky Yu.</span><br>
    Nice to meet you.<br>Email: s220xxx@gmail.com<br>
    <a href="https://www.example.com" style="color: blue; text-decoration: underline;">Go to school</a>
</p>

<h2>My Photos</h2>
<div class="photo-grid">
    <img src="photo1.jpg" alt="no photo" width="104" height="142">
    <img src="photo2.jpg" alt="no photo" width="104" height="142">
    <img src="photo3.jpg" alt="no photo" width="104" height="142">
    <img src="photo4.jpg" alt="no photo" width="104" height="142">
    <img src="photo5.jpg" alt="no photo" width="104" height="142">
    <img src="photo6.jpg" alt="no photo" width="104" height="142">
    <img src="photo7.jpg" alt="no photo" width="104" height="142">
    <img src="photo8.jpg" alt="no photo" width="104" height="142">
    <img src="photo9.jpg" alt="no photo" width="104" height="142">
</div>

<p>Can you see the photos?</p>
<input type="range"> 
<select>
    <option>See, very beautiful</option>
    <option>No! You even do not put the photo!?</option>
</select>

<div class="input-container">
    <label>First name: <input type="text"></label><br>
    <label>Last name: <input type="text"></label>
</div>

<img src="Timetable.jpg" alt="Class Timetable" style="display: block; margin: 20px auto; max-width: 100%; height: auto;">

</body>
</html>
