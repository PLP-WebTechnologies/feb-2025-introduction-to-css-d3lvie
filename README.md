<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Elite Cars Dealership</title>

    <style>
        /* Apply background color and font to the whole page */
        body {
            background-color: #f4f4f4; /* Light gray background */
            font-family: 'Arial', sans-serif; /* Change font */
            margin: 0;
            padding: 0;
        }

        
        header {
            background-color: #333; /* Dark background for header */
            color: white; /* White text color */
            padding: 20px 0; /* Add padding */
        }

        header h1 {
            font-size: 36px;
            margin: 0;
            text-align: center;
        }

        
        nav a {
            color: white; /* White text color for links */
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        nav a:hover {
            color: #ff6347; /* Change color on hover (tomato) */
        }

        
        .container {
            padding: 20px;
            text-align: center;
        }

       
        img {
            max-width: 100%; /* Ensure images scale with the screen size */
            height: auto;
            border-radius: 8px; /* Rounded corners for images */
            margin: 20px 0; /* Add margin above and below images */
        }

        
        .car-list {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }

        .car {
            border: 1px solid #ddd;
            padding: 15px;
            width: 300px;
            background-color: #fff;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); /* Subtle shadow */
        }

        .car h3 {
            font-size: 22px;
            color: #333; /* Dark color for car names */
        }

        .car p {
            font-size: 18px;
            color: #555; /* Lighter gray color for text */
        }

       
        footer {
            background-color: #333;
            color: white;
            padding: 15px 0;
            text-align: center;
            margin-top: 20px;
        }

        
        form {
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 20px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); /* Subtle shadow for form */
        }

        form label {
            font-size: 18px;
            margin-bottom: 5px;
        }

        form input, form textarea {
            width: 80%;
            padding: 10px;
            margin: 10px 0 20px 0;
            border: 1px solid #ddd;
            border-radius: 4px;
        }

        form button {
            padding: 12px 20px;
            background-color: #333;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }

        form button:hover {
            background-color: #ff6347; /* Button color change on hover */
        }
    </style>
</head>
<body>
    <header>
        <h1>Elite Cars Dealership</h1>
        <nav>
            <a href="#home">Home</a>
            <a href="#cars">Our Cars</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section id="home" class="container">
        <h2>Welcome to Elite Cars</h2>
        <p>Your trusted dealership for luxury and affordable cars.</p>
    </section>

    <section id="cars" class="container">
        <h2>Featured Cars</h2>
        <div class="car-list">
            <div class="car">
                <h3>2024 Tesla Model S</h3>
                <p>Price: $85,000</p>
                <img src="https://via.placeholder.com/300x200" alt="Tesla Model S">
            </div>
            <div class="car">
                <h3>2023 BMW M4</h3>
                <p>Price: $72,000</p>
                <img src="https://via.placeholder.com/300x200" alt="BMW M4">
            </div>
            <div class="car">
                <h3>2023 Ford Mustang</h3>
                <p>Price: $55,000</p>
                <img src="https://via.placeholder.com/300x200" alt="Ford Mustang">
            </div>
        </div>
    </section>

    <section id="contact" class="container">
        <h2>Contact Us</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required placeholder="Enter your full name"><br><br>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required placeholder="Enter your email"><br><br>
            
            <label for="message">Message:</label><br>
            <textarea id="message" name="message" rows="4" required placeholder="Write your message here"></textarea><br><br>
            
            <button type="submit">Send</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Elite Cars Dealership. All rights reserved.</p>
    </footer>
</body>
</html>
