# Glitch-

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Glitch and Neon Effects</title>
    <style>
        body {
            background-color: black;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            color: white;
            font-family: 'Arial', sans-serif;
        }

        .glitch {
            font-size: 48px;
            font-weight: bold;
            position: relative;
            color: lime;
            animation: neon 1.5s infinite alternate;
        }

        .glitch:before,
        .glitch:after {
            content: "Glitch & Neon Effects";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: black;
            overflow: hidden;
            color: lime;
        }

        .glitch:before {
            left: 2px;
            text-shadow: -2px 0 red;
            clip: rect(24px, 550px, 90px, 0);
            animation: glitch 2s infinite linear alternate-reverse;
        }

        .glitch:after {
            left: -2px;
            text-shadow: -2px 0 blue;
            clip: rect(85px, 550px, 140px, 0);
            animation: glitch 3s infinite

            
