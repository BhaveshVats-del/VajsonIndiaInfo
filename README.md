# VajsonIndiaInfo
[Uploading <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>index.html</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <nav>
        <h1>Vajson India</h1>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#our team">Our Team</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <section id="home" class="banner">
        <h2>Vajson India</h2>
        <h4><img src="Black & White Minimalist Business Logo (1).jpg"></h4>
        <p>What you are looking for is right here!</p>
        <button onclick="showMessage()">Click Me</button>
    </section>

    <section id="services">
        <h2>Our Team</h2>
        <div class="service-box">
            <div class="service">
                <h3>Properioter</h3>
                <p>Bhartendu Sharma</p>
            </div>
            <div class="service">
                <h3>Manager</h3>
                <p>Narinder Sharma</p>
            </div>
            <div class="service">
                <h3>Sales Executive</h3>
                <p>Anmol Yadav</p>
            </div>
            <div class="service">
                <h3>Accountant</h3>
                <p>Gautam Sehgal</p>
            </div>
        </div>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>Vajson India is a manufacturer of printer ink, printing chemical ink, and off set ink printing. We are located at Plot No. 1409, Sector-82, Mohali-160055. The contact person is Narinder Sharma, who is the Manager. His mobile number is +91 97797 17849. Vajson India is a top printing chemical distributor in Mohali, Chandigarh. Vajson India is one of the most best growing printing chemicaldistributor not only in its area but also in whole Mohali.</p>
    </section>

    <footer id="contact">
        <h2>Contact Us</h2>
        <p>Gmail: vajsonindia@gmail.com | Phone: +91 97797 17849</p>
    </footer>


    <script src="script.js"></script>
</body>
</html>

index.html…]()



[Upl* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    color: #333;
}

nav {
    background: linear-gradient(45deg, #ff416c, #ff4b2b);
    padding: 1rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

nav h1 {
    color: #fff;
}

nav ul {
    list-style: none;
    display: flex;
}

nav ul li {
    margin-left: 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-size: 18px;
}

.banner {
    background: linear-gradient(120deg, #84fab0, #8fd3f4);
    padding: 100px 0;
    text-align: center;
    color: white;
}

.banner h2 {
    font-size: 48px;
    margin-bottom: 20px;
}

.banner p {
    font-size: 24px;
    margin-bottom: 20px;
}

.service-box {
    display: flex;
    justify-content: space-around;
    padding: 50px 0;
    background-color: #f4f4f9;
}

.service {
    background: #fdfdfd;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    text-align: center;
}

.service h3 {
    font-size: 24px;
    margin-bottom: 10px;
}

#about {
    padding: 50px;
    text-align: center;
    background: linear-gradient(120deg, #f6d365, #fda085);
    color: white;
}

footer {
    background: #333;
    color: white;
    padding: 20px;
    text-align: center;
}
oading styles.css…]()




function showMessage() {
    alert('Welcome to Vajson India!');
}
