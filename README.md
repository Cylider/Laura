<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Para Laura</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            background: linear-gradient(black,#2c2f34);
        }
        h1 {
            position: fixed;
            color: #f20050;
            bottom: 10vh;
            left: 50%;
            transform: translateX(-50%);
            text-shadow: 0 0 5px black;
            animation: text 1s linear infinite;
            font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        }
        @media (min-width: 1080px) {
            h1 {
                position: fixed;
            color: #f20050;
                bottom: 20vh;
                left: 50%;
                transform: translateX(-50%);
                text-shadow: 0 0 5px black;
                animation: text 1s linear infinite;
                font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
            }
        }

        @keyframes text {
            0%{
                color: red;
                text-shadow: 0 0 10px black;
            }
            80%{
                color: #f20050;
                text-shadow: 0 0 10px #2c2f34;
            }
            100%{
                color: #f20044;
                text-shadow: 0 0 10px black;
            }

        }
        .heart {
            height: 140px;
            width: 140px;
            background-color: #f20044;
            position: relative;
            transform: rotate(-45deg);
            box-shadow: 0px 0px 100px #f20044;
            animation: heart 0.9s linear infinite;
        }
        @keyframes heart {
            0% {
                transform: rotate(-45deg) scale(1.07);
            }
            80% {
                transform: rotate(-45deg) scale(0.9);
            }
            100% {
                transform: rotate(-45deg) scale(0.7);
            }
        }
        .heart:before {
            content: "";
            position: absolute;
            height: 140px;
            width: 140px;
            background-color: #f20044;
            top: -50%;
            border-radius: 75px;
            box-shadow: 0px 0px 100px #f20044;
        }
        .heart:after {
            content: "";
            position: absolute;
            height: 140px;
            width: 140px;
            background-color: #f20044;
            right: -50%;
            border-radius: 75px;
            box-shadow: 0px 0px 100px #f20044;
        }
        .music {
            position: fixed;
            top: 50vh ;
            left: 50%;
            transform: translateX(-50%);
        }
    </style>
</head>
<body>
    <div class="text">
        <h1>Te Quiero mucho Laura</h1>
    </div>
    <div class="heart"></div
