<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport"
    content="width=device-width, initial-sclae=1.0">
    <title>XEROX DESIGNS</title>
    <style>
        *{
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body{
            margin: 0;
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: f4f4f4;
            color: #333;
            padding: 0;
            display:flex;
            flex-direction: column;
            height: 100vh;

        }
        .portfolio-section{
            padding: 60px 20px;
            background-color: #111;
            text-align: center;
            color: white;
        }
        .portfolio-section h2{
            color: #1c40f;
            margin-bottom: 10px;
        }
        .portfolio-section p{
            color: #ccc;
            margin-bottom: 40px;
        }
        .portfolio-grid{
            display: grid;
            grid-template-columns: repeat(auto-fit,minmax(220px,1fr));
            gap: 25px;
            max-width: 1000px;
            margin: 0 auto;
        }
        .portfolio-item h4{
            margin-top: 10px;
            color: #2ecc71;
        }
        .portfolio-item:hover{
            transform: scale(1.03);
        }
        .portfolio-item img{
            width: 100%;
            height: 100%;
            object-fit: 100%;
            border-radius: 5px;
        }
        img{
            max-width: 100%;
            height: auto;
        }
        .nav-links{
            display: flex;
            gap: 20px;
        }
        .nav-links.active{
            display: flex;
        }
        .nav-links a{
            color: white;
            text-decoration: none;
            font-size: 16px;
            transition: 0.3s;
        }
        .nav-links a:hover{
            color: black;
        }
        .toggle-btn{
            display: block;
            font-size: 28px;
            background: none;
            border: none;
            color: white;
            cursor: pointer;
        }
        .content{
            margin-top: 30px;
            padding: 20px;
            flex: 1;
        }
        .service-list li{
            margin: 10px 0;
            font-size: 18px;
        }
        footer{
            background-color: #2c3e50;
            color: white;
            margin-bottom: 20px;
            padding: 20px;
            bottom: 0;
            width: 100%;
        }
        .contact-section{
            padding: 60px 20px;
            text-align: center;
            background-color: #000;
            color: white;
        }
        .contact-section h3{
            color: #f1c40f;
            margin-bottom: 10px;
        }
        .contact-section p{
            color: #ccc;
            margin-bottom: 30px;
        }
        .contact-buttons{
        <div class="portfolio-item">
            <img src="C:\Users\UNREALISTIC\Desktop\XEROX.01\XEROX DESIGNS.png" alt="Logo Design">
            <h4>Logo Design</h4>
        </div>
        <div class="portfolio-item">
            <img src="C:\Users\UNREALISTIC\Desktop\XEROX.01\week extra.jpg" alt="Poster Design">
            <h4>Event Poster</h4>
        </div>
        <div class="portfolio-item">
            <img src="C:\Users\UNREALISTIC\Desktop\XEROX.01\NTO.jpg" alt="Business Card">
            <h4>Business Card</h4>
        </div>
        <div class="portfolio-item">
            <img src="C:\Users\UNREALISTIC\Desktop\XEROX.01\Untitled-1-Recovered.jpg" alt="Banner Design">
            <h4>Banner</h4> 
        </div>
        </div>
    </section>
<!--Main Content-->
<div class="main" id="mainCotent">
<h1 id="Home">Welcome to XEROX DESIGNS</h1>
<p>Welcome to our official site. Here we 
    showcase all our amaizing graphic designs</p>
    <h3 id="Services">Our Services</h3>
    <ul class="service-list">
        <li>Logo Design</li>
        <li>Bronchure Design</li>
        <li>Poster Design</li>
        <li>Business Card Design</li>
        <li>Website Graphics</li>
        <li>Social Media Graphics</li>
        <li>Product Pacjaging Design</li>
        <li>Infographics</li>
    </ul>
    <h3 id="Contact">Contact Us</h3>
    <p>Reach Us via +254783722072</p>
    <h3 id="about">About</h3>
    <p>Powered by Passion & Precision</p>
</div>
<!--Contact Form-->
<section id="contact" class="contact-section">
    <h3>Contact Me</h3>
    <p>Lets work together. Reach out via any platform below:</p>
    <div class="contact-buttons">
        <a href="https://wa.me/254783722072" target="_blank" class="btn whatsapp">WhatsApp</a>
        <a href="mailto:onlinecyberservices09@gmail.com" class="btn email">Email</a>
        <a href="tel:+254783722072" class="btn phone">Call</a>
        <a href="https://www.facebook.com/profile.php?id=61575141711057" target="_blank" class="btn facebook">Facebook</a>
    </div>
</section>
<div class="content">
    <h3>Contact Us</h3>
    <p>If you would like to inquire or work with us please fill out the form below</p>
    <div class="contact-form">
        <form action="#">
            <input type="text" placeholder="Your Name" required><br>
            <input type="email" placeholder="Your Email" required><br>
            <textarea placeholder="Your Message" rows="5" required></textarea><br>
            <button type="submit">Send Message</button>
        </form>
    </div>
</div>
<!--Footer Section-->
<footer>
    <p>&copy; 2025 Xerox Designs. All Rights Reserve.</p>
</footer>
</body>
<!--JavaScript-->
<script>
    function toggleMenu(){
       const nav = document.getElementById("navLinks").classList.toggle("active");
    }
        </script>
</html>
