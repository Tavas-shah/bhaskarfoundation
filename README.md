<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bhaskar prabha Foundation</title> 
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
        }
        .header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px;
            background-color: #ffffff;
        }
        .header .logo {
            font-size: 24px;
            font-weight: bold;
            color: #613b00; /* Logo text color */
        }
        .header nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #613b00; /* Navigation links color */
            font-weight: bold;
        }
        .header nav a:hover {
            color: #ff5733;
        }
        .main-content {
            background-color: #f7990e; /* Background color of the section */
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            height: calc(100vh - 80px); /* Full height minus header */
        }
        .main-content h1 {
            font-size: 48px;
            font-weight: bold;
            margin: 0;
            text-align: center;
        }
        .container {
            max-width: 900px;
            margin: 20px auto;
            background: #fff;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
        }
        iframe {
            width: 100%;
            height: 300px;
            border: none;
            border-radius: 8px;
            margin-top: 20px;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #5D9CEC;
            margin-top: 20px;
            color: white;
            font-size: 16px;
        }
        .quick-links, .join-us, .address {
            margin: 20px 0;
        }
        .quick-links a {
            text-decoration: none;
            color: #613b00;
            font-weight: bold;
        }
        .quick-links a:hover {
            color: #fff5733;
        }
        .footer-content {
            display: flex;
            justify-content: space-between;
            padding: 20px;
            background-color: #h2g2g2;
        }
        .footer-content div {
            flex: 1;
            margin: 0 10px;
        }
    </style>
</head>
<body>
    <div class="header">
        <div class="logo">BHASKAR PRABHA FOUNDATION</div>
        <nav>
            <a href="about.html" target="_blank">About Us</a>
            <a href="support.html" target="_blank">Support Us</a>
            <a href="contact.html" target="_blank">Contact</a>
            <a href="#find-us">Find Us</a>
        </nav>
    </div>

    <div class="main-content">
        <h1 id="rotating-text">Indian Mathematics</h1>
    </div>

    <div class="container">
        <h2>Bhaskar Prabha Foundation</h2>
        <p>The Bhaskar Prabha Foundation, established in 2025, is dedicated to the study and promotion of both modern and ancient mathematics. We focus on advancing mathematical knowledge and inspiring the next generation of mathematicians through a blend of historical wisdom and contemporary methods.</p>
    </div>

    <footer>
        <div class="footer-content">
            <div class="quick-links">
                <h3>Quick Links</h3>
                <a href="#">Home</a><br>
                <a href="#">About Us</a><br>
                <a href="#">Mission</a><br>
                <a href="#">Education</a><br>
                <a href="#">School System</a><br>
                <a href="#">Gallery</a><br>
                <a href="#">Event</a><br>
                <a href="#">Inspire and Support</a><br>
                <a href="#">Biological Life</a><br>
                <a href="#">FAQs</a><br>
                <a href="#">Contact Us</a><br>
                <a href="#">Privacy Policy</a>
            </div>
            <div class="join-us">
                <h3>Join Us</h3>
                <p>📞 7977067703</p>
                <p>📞 9321144426</p>
                <p>📧 info@Bhaskarprabha foundation.in</p>
            </div>
            <div class="address">
                <h3>Address</h3>
                <p>2, Anand Vihar Colony Rd, Near Sudarshan Nivas, Anand Vihar, Mahadev Nagar, Hingne Khurd, Pune, Maharashtra 411009</p>
                <p>PinCode - 411009</p>
            </div>
        </div>
        <p>&copy; 2025 Bhaskar Prabha Foundation</p>
    </footer>

    <script>
        const texts = ["Indian Mathematics", "Bhaskar Prabha Foundation"];
        let index = 0;
        const textElement = document.getElementById('rotating-text');

        setInterval(() => {
            index = (index + 1) % texts.length;
            textElement.textContent = texts[index];
        }, 5000); // Change text every 5 seconds
    </script>
</body>
</html>
