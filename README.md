<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Football Presentation</title>
    <style>
        body {
            font-family: Helvetica, Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            overflow-y: scroll; /* Enable vertical scrolling */
        }

        .slide {
            height: 100vh; /* Full viewport height */
            display: flex;
            flex-direction: column;
            justify-content: flex-start; /* Start content from the top */
            align-items: center;
            padding: 20px;
            background: #C1DEF1;
            border-bottom: 2px solid #000; /* Optional visual separation */
        }

        .slide-content {
            display: flex;
            flex-direction: row; /* Align body text and image side by side */
            justify-content: space-between;
            align-items: flex-start;
            width: 100%;
            max-width: 1200px; /* Limit the content width */
        }

        .headline {
            font-size: 36pt;
            color: #1C1C1C;
            text-align: center;
            margin-bottom: 20px;
            width: 100%;
        }

        .body-text {
            font-size: 20pt;
            line-height: 1.5;
            margin-right: 20px;
            color: #1C1C1C;
            flex: 1; /* Take up remaining space */
        }

        .body-text ul {
            list-style-type: disc;
            margin-left: 20px;
        }

        .body-text li {
            margin-bottom: 10px;
            font-size: 20pt;
            color: #1C1C1C;
        }

        .slide img {
            border: 2px solid #000;
            flex-shrink: 0; /* Prevent the image from shrinking */
        }
    </style>
</head>
<body>
    <!-- Title Slide -->
<div class="slide" style="display: flex; flex-direction: row; align-items: center; justify-content: space-between; padding:50px; color: #1C1C1C;">
    <!-- Headline Section -->
    <h1 class="headline" style="font-size: 43pt; font-family: 'Times New Roman'; margin: 0; flex-basis: 80%; text-align: left color: #1C1C1C;">
     FOOTBALL: A GREAT GAME 
    </h1>
    <!-- Image Section -->
    <div style="flex-basis: 40%; text-align: right;">
        <img src="images/image1.jpg" alt="Football Image" style="width: 400px; height: 400px;">
    </div>
</div>
    <!-- Slide 1 -->
    <div class="slide" style="display: flex; flex-direction: column; padding: 50px; color: #1C1C1C;">
    <!-- Headline Section -->
    <h2 class="headline" style="font-size: 36pt; font-family: 'Helvetica'; margin-bottom: 20px; text-align: center; color: #1C1C1C;">
        INTRODUCTION TO FOOTBALL
    </h2>
    
    <!-- Content and Image Section -->
    <div style="display: flex; flex-direction: row; justify-content: space-between; align-items: flex-start;">
        <!-- Body Section -->
        <div class="slide-content" style="flex-basis: 50%; padding-right: 20px;">
            <ul style="padding-left: 20px; list-style-type: disc; margin: 0;">
                <li style="font-size: 20pt; margin-bottom: 10px;">Football, also known as soccer in some countries, is the most popular sport in the world.</li>
                <li style="font-size: 23pt; margin-bottom: 10px;">Played by over 250 million players in 200 countries, its impact is undeniable.</li>
            </ul>
        </div>
        
        <!-- Image Section -->
        <img src="images/image2.jpg" alt="Football Field" style="width: 500px; height: 500px; flex-basis: 50%;">
    </div>
</div>

    <!-- Slide 2 -->
    <div class="slide" style="display: flex; flex-direction: column; padding: 50px; color: #1C1C1C;">
    <!-- Headline Section -->
    <h2 class="headline" style="font-size: 32pt; font-family: 'Helvetica'; margin-bottom: 40px; text-align: center; color: #1C1C1C;">
        GAMEPLAY & GOVERNANCE
    </h2>
    <!-- Content and Image Section -->
    <div style="display: flex; flex-direction: row; justify-content: space-between; align-items: flex-start;">
        <!-- Body Section -->
        <div class="slide-content" style="flex-basis: 50%; padding-right: 20px;">
            <ul style="padding-left: 20px; list-style-type: disc; margin: 0; font-family: 'Helvetica'; font-weight: normal;">
                <li style="font-size: 23pt; margin-bottom: 20px;">A standard match consists of two 45-minute halves.
</li>
                <li style="font-size: 26pt; margin-bottom: 20px;">FIFA, the governing body, oversees international competitions.
</li>
            </ul>
        </div>
        
        <!-- Image Section -->
        <img src="images/image3.jpg" alt="Football Field" style="width: 700px; height: 500px; flex-basis: 50%;">
    </div>
</div>
    <!-- Slide 3 -->
    <div class="slide" style="display: flex; flex-direction: column; padding: 50px; color: #1C1C1C;">
    <!-- Headline Section -->
    <h2 class="headline" style="font-size: 32pt; font-family: 'Helvetica'; margin-bottom: 40px; text-align: center; color: #1C1C1C;">
        Skills and Teamwork
 </h2>
    <!-- Content and Image Section -->
    <div style="display: flex; flex-direction: row; justify-content: space-between; align-items: flex-start; gap: 40px;">
        <!-- Body Section -->
        <div class="slide-content" style="flex-basis: 50%; padding-right: 20px;">
            <ul style="padding-left: 20px; list-style-type: disc; margin: 0; font-family: 'Helvetica'; font-weight: normal;">
                <li style="font-size: 23pt; margin-bottom: 10px;">Dribbling</li>
<li style="font-size: 23pt; margin-bottom: 10px;">Passing </li>
<li style="font-size: 23pt; margin-bottom: 10px;">Shooting </li>
<li style="font-size: 23pt; margin-bottom: 10px;">Tackling</li>
<li style="font-size: 23pt; margin-bottom: 10px;">Teamwork </li>
                <li style="font-size: 26pt; margin-bottom: 10px;">Strategic thinking</li>
            </ul>
        </div>
        
        <!-- Image Section -->
        <img src="images/image4.jpg" alt="Football Field" style="width: 540px; height: 516px; flex-basis: 50%; margin-left:20px;">
    </div>
</div>

    <!-- Slide 4 -->
    <div class="slide" style="display: flex; flex-direction: column; padding: 50px; color: #1C1C1C;">
    <!-- Headline Section -->
    <h2 class="headline" style="font-size: 36pt; font-family: 'Helvetica'; margin-bottom: 40px; text-align: center; color: #1C1C1C;">
        Conclusion
    </h2>
    <!-- Content and Image Section -->
    <div style="display: flex; flex-direction: row; justify-content: space-between; align-items: flex-start;">
        <!-- Body Section -->
        <div class="slide-content" style="flex-basis: 50%; padding-right: 20px;">
            <ul style="padding-left: 20px; list-style-type: disc; margin: 0; font-family: 'Helvetica'; font-weight: normal;">
                <li style="font-size: 23pt; margin-bottom: 20px;">Football's global impact, exciting gameplay, and requirement for skill and teamwork make it a beloved sport.
</li>
                <li style="font-size: 26pt; margin-bottom: 20px;">Explore the world of football further!
</li>
            </ul>
        </div>
        
        <!-- Image Section -->
        <img src="images/image5.jpg" alt="Football Field" style="width: 488px; height: 446px; flex-basis: 50%;">
    </div>
</div>
</body>
</html>
