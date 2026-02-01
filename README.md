<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Awesome Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #007bff;
            color: white;
            text-align: center;
            padding: 1rem;
        }
        section {
            max-width: 800px;
            margin: 2rem auto;
            padding: 1rem;
            background: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        footer {
            text-align: center;
            padding: 1rem;
            background-color: #333;
            color: white;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Site</h1>
        <p>A simple page built with AI help.</p>
    </header>
    
    <section>
        <h2>About Me</h2>
        <p>This is a placeholder for your content. Add your bio, photos, or whatever you like!</p>
        <img src="https://via.placeholder.com/300" alt="Placeholder Image" style="max-width: 100%; height: auto;">
    </section>
    
    <section>
        <h2>Contact</h2>
        <p>Email: your.email@example.com</p>
        <button onclick="alert('Thanks for visiting!')">Click Me</button>
    </section>
    
    <footer>
        <p>&copy; 2023 Your Name. Powered by Grok.</p>
    </footer>
    
    <script>
        // Simple JS example: Change header color on click
        document.querySelector('header').addEventListener('click', function() {
            this.style.backgroundColor = this.style.backgroundColor === 'rgb(0, 123, 255)' ? '#28a745' : '#007bff';
        });
    </script>
</body>
</html>
