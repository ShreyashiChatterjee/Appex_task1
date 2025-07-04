# Appex_task1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Basic Webpage</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f4f8;
            color: #333;
            line-height: 1.6;
        }
        header {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 2rem;
            margin-bottom: 2rem;
        }
        h1 {
            margin: 0;
            font-size: 2.5rem;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        .content {
            display: flex;
            flex-wrap: wrap;
            gap: 2rem;
            justify-content: space-between;
        }
        .text-section {
            flex: 1;
            min-width: 300px;
        }
        p {
            font-size: 1.1rem;
            margin-bottom: 1.5rem;
        }
        .image-section {
            flex: 1;
            min-width: 300px;
            text-align: center;
        }
        img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin-bottom: 1rem;
        }
        a {
            color: #3498db;
            text-decoration: none;
            font-weight: bold;
        }
        a:hover {
            color: #2980b9;
            text-decoration: underline;
        }
        button {
            background-color: #e74c3c;
            color: white;
            border: none;
            padding: 12px 24px;
            font-size: 1rem;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease;
            display: block;
            margin: 2rem auto;
        }
        button:hover {
            background-color: #c0392b;
        }
        @media (max-width: 768px) {
            .content {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Webpage</h1>
    </header>
    <div class="container">
        <div class="content">
            <div class="text-section">
                <p>This is a simple webpage created using HTML, CSS, and JavaScript. It features a clean layout with a heading, paragraphs, an image, and interactive elements.</p>
                <p>Explore more about web development by visiting <a href="https://developer.mozilla.org" target="_blank">MDN Web Docs</a> for comprehensive resources and tutorials.</p>
            </div>
            <div class="image-section">
                <img src="https://i.ibb.co/r2jd4Zm8/image1.jpg" alt="image1">
                <p>A sample image to enhance the visual appeal of the page.</p>
            </div>
        </div>
        <button onclick="showAlert()">Click Me!</button>
    </div>
    <script>
        function showAlert() {
            alert("Hello! You clicked the button!");
        }
    </script>
</body>
</html>
