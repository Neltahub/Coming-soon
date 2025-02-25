<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coming Soon - Nelta</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Inter', sans-serif;
            background: url('background-image.png') no-repeat center center/cover;
            color: white;
            text-align: center;
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            overflow: hidden;
        }
        header {
            position: absolute;
            top: 20px;
            left: 20px;
            display: flex;
            align-items: center;
        }
        header img {
            height: 40px;
            margin-right: 10px;
        }
        nav {
            position: absolute;
            top: 20px;
            right: 20px;
        }
        h1 {
            font-size: 48px;
            margin: 0;
        }
        p {
            font-size: 18px;
            margin: 10px 0 30px;
        }
        form {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 10px;
            margin-bottom: 20px;
        }
        input[type="email"] {
            padding: 10px;
            width: 80%;
            max-width: 400px;
            border-radius: 5px;
            border: none;
            font-size: 16px;
        }
        button {
            padding: 10px 20px;
            background-color: #0056b3;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            width: 80%;
            max-width: 400px;
        }
        button:hover {
            background-color: #003d80;
        }
        footer {
            position: absolute;
            bottom: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
            width: 100%;
            padding: 0 20px;
            box-sizing: border-box;
        }
        .social-icons a {
            margin: 0 5px;
            text-decoration: none;
        }
        .social-icons img {
            height: 30px;
        }
        @media (min-width: 768px) {
            h1 {
                font-size: 64px;
            }
            p {
                font-size: 20px;
            }
            form {
                flex-direction: row;
                gap: 10px;
            }
            input[type="email"], button {
                width: auto;
            }
            footer {
                flex-direction: row;
                justify-content: space-between;
            }
        }
    </style>
</head>
<body>
    <header>
        <img src="logo.png" alt="Nelta Logo">
        <strong>NELTA</strong>
    </header>
    <nav>
        <a href="#" style="color: white; text-decoration: none; font-weight: bold;">HOME</a>
    </nav>

    <main>
        <h1>COMING SOON</h1>
        <p>We're working on something awesome!</p>
        <form action="mailto:contact@nelta.sa" method="post" enctype="text/plain">
            <input type="email" name="email" placeholder="Enter your email" required>
            <button type="submit">Subscribe</button>
        </form>
        <p>Be the first to know when we launch.</p>
    </main>

    <footer>
        <div>
            <a href="mailto:contact@nelta.sa" style="color: white; text-decoration: none;">contact@nelta.sa</a>
        </div>
        <div class="social-icons">
            <span>FOLLOW US</span>
            <a href="https://www.linkedin.com/company/nelta" target="_blank">
                <img src="linkedin-icon.png" alt="LinkedIn">
            </a>
            <a href="https://www.instagram.com/nelta" target="_blank">
                <img src="instagram-icon.png" alt="Instagram">
            </a>
        </div>
    </footer>
</body>
</html>
