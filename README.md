git clone https://github.com/your-username/exercise-4-svg-house.git
cd exercise-4-svg-house# exercise-4-svg-house
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SVG House and Garden</title>
</head>
<body>
    <svg width="800" height="600">
        <!-- Background (Sky) -->
        <rect x="0" y="0" width="800" height="300" fill="skyblue"/>

        <!-- Grass -->
        <rect x="0" y="300" width="800" height="300" fill="lightgreen"/>

        <!-- House Body -->
        <rect x="300" y="200" width="200" height="200" fill="saddlebrown" stroke="black"/>

        <!-- Roof -->
        <polygon points="300,200 500,200 400,100" fill="maroon" stroke="black"/>

        <!-- Door -->
        <rect x="380" y="300" width="40" height="100" fill="darkbrown" stroke="black"/>

        <!-- Windows -->
        <rect x="320" y="220" width="50" height="50" fill="lightblue" stroke="black"/>
        <rect x="430" y="220" width="50" height="50" fill="lightblue" stroke="black"/>

        <!-- Sun -->
        <circle cx="100" cy="100" r="50" fill="yellow"/>

        <!-- Tree -->
        <rect x="600" y="250" width="40" height="100" fill="saddlebrown"/>
        <circle cx="620" cy="200" r="50" fill="green"/>

        <!-- Text Label -->
        <text x="350" y="450" font-size="24" fill="black">My SVG House & Garden</text>
    </svg>
</body>
</html>
