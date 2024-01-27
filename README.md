<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>École des Arts du Cirque</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to bottom, #87CEEB, #4682B4);
            color: #333;
        }
        header {
            background-color: #2E8B57;
            color: #fff;
            text-align: center;
            padding: 1em;
            border-bottom: 2px solid #fff;
        }
        nav {
            background-color: transparent;
            overflow: hidden;
            margin-bottom: 5px;
            text-align: center;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            padding: 10px 20px;
            margin: 0 10px;
            border-radius: 50%;
            background-color: #ff6347;
            transition: background-color 0.3s ease;
            display: inline-block;
        }
        nav a:hover {
            background-color: #ff7f50;
        }
        .banner {
            background-image: url('eac.jpg');
            height: 750px; 
            background-size: cover;
            background-position: center;
            position: relative;
            overflow: hidden;
        }
     
        }
       
        .banner:hover .banner-overlay {
            opacity: 1;
        }
        .banner-overlay h1 {
            font-size: 36px;
            margin: 0;
        }
        .banner-overlay p {
            font-size: 18px;
            margin-top: 10px;
        }
       
        footer {
            text-align: center;
            padding: 2px;
