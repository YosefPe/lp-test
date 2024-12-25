<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blings.io Landing Page</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #000;
            color: #fff;
        }
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 50px;
            background-color: #0d0d0d;
        }
        header a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
        }
        .hero {
            display: flex;
            align-items: center;
            justify-content: space-between;
            padding: 50px;
        }
        .hero-text {
            max-width: 50%;
        }
        .hero-text h1 {
            font-size: 3rem;
        }
        .hero img {
            max-width: 40%;
            border-radius: 20px;
        }
        .cta {
            background: linear-gradient(90deg, #ff0076, #ff4d00);
            padding: 15px 30px;
            color: #fff;
            font-size: 1.2rem;
            border: none;
            cursor: pointer;
            margin: 20px 0;
            display: inline-block;
        }
        .trusted {
            text-align: center;
            padding: 50px;
        }
        .trusted img {
            max-width: 150px;
            margin: 20px;
        }
        .features {
            padding: 50px;
            text-align: center;
        }
        .features h2 {
            font-size: 2.5rem;
        }
        .features .cards {
            display: flex;
            justify-content: space-around;
            margin-top: 30px;
        }
        .card {
            background-color: #1a1a1a;
            padding: 20px;
            border-radius: 10px;
            width: 30%;
        }
        .card h3 {
            color: #ff0076;
        }
        .demo {
            background: #1a1a1a;
            padding: 50px;
            text-align: center;
        }
        .demo form {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .demo input {
            padding: 10px;
            margin: 10px;
            width: 70%;
            max-width: 500px;
            border-radius: 5px;
            border: none;
        }
        .demo button {
            background: linear-gradient(90deg, #ff0076, #ff4d00);
            padding: 15px 30px;
            color: #fff;
            font-size: 1rem;
            border: none;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <header>
        <div><a href="#">Blings.io</a></div>
        <nav>
            <a href="#solution">Solution</a>
            <a href="#resources">Resources</a>
            <a href="#company">Company</a>
        </nav>
        <div>
            <a href="#" class="cta">Play</a>
            <a href="#" class="cta">Book a Demo</a>
        </div>
    </header>

    <section class="hero">
        <div class="hero-text">
            <h1>Welcome, {{FIRSTNAME}} {{LASTNAME}}</h1>
            <p>At Blings.io, we believe every interaction should shine. That's why we've crafted a personalized video experience just for you. Watch your custom video and discover the magic of MP5 technology!</p>
            <a href="#demo" class="cta">Get Your Free Custom Video Now!</a>
        </div>
        <img src="placeholder.jpg" alt="Custom Video">
    </section>

    <section class="trusted">
        <h2>Trusted By</h2>
        <img src="salesforce.png" alt="Salesforce">
        <img src="hubspot.png" alt="Hubspot">
        <img src="microsoft.png" alt="Microsoft">
        <img src="adobe.png" alt="Adobe">
    </section>

    <section class="features">
        <h2>How It’s Done</h2>
        <div class="cards">
            <div class="card">
                <h3>Quick Integration</h3>
                <p>Embed videos into your CRM in under 5 minutes.</p>
            </div>
            <div class="card">
                <h3>Secure By Design</h3>
                <p>Fully GDPR and CCPA compliant, with zero data exposure to Blings.</p>
            </div>
            <div class="card">
                <h3>Light and Fast</h3>
                <p>Each video is only 60kb, ensuring smooth playback and lightning-fast performance.</p>
            </div>
        </div>
    </section>

    <section class="demo" id="demo">
        <h2>Book a Demo</h2>
        <form>
            <input type="text" placeholder="First name *">
            <input type="text" placeholder="Last name *">
            <input type="text" placeholder="Company name *">
            <input type="email" placeholder="Company email address *">
            <input type="text" placeholder="Job title *">
            <input type="text" placeholder="Phone number *">
            <input type="text" placeholder="How did you hear about us?">
            <button type="submit">Submit</button>
        </form>
        <p>By clicking the button, you agree to Blings' <a href="#">Terms of Use</a> and <a href="#">Privacy Policy</a>.</p>
    </section>
</body>
</html>
