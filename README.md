<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>3D Voxel World</title>
    <style>
        body { margin: 0; overflow: hidden; background-color: #87CEEB; }
        #ui {
            position: absolute;
            top: 50%; left: 50%;
            transform: translate(-50%, -50%);
            text-align: center;
            color: #333;
            background: rgba(255, 255, 255, 0.9);
            padding: 30px;
            border-radius: 8px;
            font-family: Arial, sans-serif;
            cursor: pointer;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }
        #crosshair {
            position: absolute;
            top: 50%; left: 50%;
            transform: translate(-50%, -50%);
            color: white;
            font-size: 24px;
            pointer-events: none;
            display: none;
            text-shadow: 1px 1px 0 #000;
        }
    </style>
</head>
<body>
    <div id="ui">

