<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Azienda di Videogiochi</title>
    <style>
        /* Reset CSS */
        *, *::before, *::after {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }
        
        /* Stili generali */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            background-color: #f5f5f5;
            color: #333;
            margin: 0;
            padding: 0;
        }
        
        /* Intestazione */
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
        }
        header h1 {
            font-size: 3rem;
            margin-bottom: 10px;
            text-transform: uppercase;
        }
        
        /* Barra di navigazione */
        nav {
            background-color: #444;
            text-align: center;
            padding: 10px 0;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            padding: 10px 20px;
            font-size: 1.2rem;
        }
        nav a:hover {
            background-color: #555;
        }
        
        /* Hero section */
        .hero {
            background-image: url('hero-background.jpg');
            background-size: cover;
            background-position: center;
            height: 600px;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: #fff;
            margin-top: 80px;
        }
        .hero h2 {
            font-size: 4rem;
            margin-bottom: 20px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }
        .hero p {
            font-size: 1.5rem;
            max-width: 800px;
            margin: 0 auto;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }
        
        /* Sezione Giochi */
        .games {
            background-color: #fff;
            padding: 50px 0;
            text-align: center;
        }
        .games h2 {
            font-size: 3rem;
            margin-bottom: 30px;
            text-transform: uppercase;
        }
        .game {
            display: inline-block;
            margin: 20px;
            background-color: #f9f9f9;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
            overflow: hidden;
... (105 righe a disposizione)

