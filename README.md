<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Low Yi Yi Website</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Arial', sans-serif;
            display: flex;
            justify-content: center;
            align-items: flex-start;
            height: 100vh;
            background: linear-gradient(to right, #c0d8f0, #e3f0cb);
        }

        header {
            width: 100%;
            background-color: #fafafa;
            font-size: 10px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            position: fixed;
            top: 0;
            left: 0;
            z-index: 1000;
        }

        .container {
            display: flex;
            background-color: #fef5e7;
            border-radius: 20px;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            max-width: 1300px;
            width: 100%;
            margin-top: 50px;
        }

        .image-section {
            flex: 1.5; 
            background: linear-gradient(to bottom, #c0d8f0, #e3f0cb);
            padding: 30px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .image-section img {
            border-radius: 20px;
            max-width: 100%;
            height: auto;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            margin-bottom: 30px; 
        }

        .social-icons {
            display: flex;
            gap: 20px;
        }

        .social-icons img {
            width: 30px;
            height: 30px;
        }

        .content-section {
            flex: 2.5; 
            padding: 40px;
            display: flex;
            flex-direction: column;
            justify-content: flex-start;
            align-items: flex-start;
        }

        .content-section h1 {
            font-size: 23px;
            margin-bottom: 10px;
            background-color: rgb(255, 202, 202); 
            color: rgb(0, 0, 0); 
            width: 100%;
            padding: 10px;
            margin: 0;
        }

        .content-section p {
            font-size: 18px;
            margin-bottom: 20px;
            line-height: 1.6;
        }
    </style>
<header>
        <h1>Hello! Welcome To My Website!</h1>
    </header>
<body>
    <div class="container">
        <div class="image-section">
            <img src="photo_6192856303097987528_w.jpg" alt="Low Yi Yi">
            <div class="social-icons">
                <a href="https://www.instagram.com/wendyyiii._/">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" alt="Instagram">
                </a>
                <a href="https://wa.me/60182229077">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp">
                </a>
            </div>
        </div>
        <div class="content-section">
            <h1>Introduction</h1>
            <p>My name is Low Yi Yi, and I am currently pursuing a Diploma in Computer Science at Universiti Pendidikan Sultan Idris (UPSI). I look forward to applying my skills in real-world projects and contributing to innovative solutions.</p>

            <h1>Education</h1>
            <p>Diploma in Computer Science - Universiti Pendidikan Sultan Idris (UPSI)</p>

            <h1>Skills</h1>
            <p>Programming Languages: Java</p>
            <p>Web Development: HTML, CSS, JavaScript</p>
            <p>Database Management: MySQL</p>
        </div>
    </div>
</body>
</html>
