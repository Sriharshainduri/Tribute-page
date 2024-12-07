# Tribute-page.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tribute to [Person's Name]</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <nav class="navbar">
            <a href="#about">About</a>
            <a href="#achievements">Achievements</a>
            <a href="#quote">Quote</a>
            <a href="#contact">Contact</a>
        </nav>

        <header class="hero-section">
            <div class="hero-content">
                <h1>In Honor of N. R. Narayana Murthy</h1>
                <p class="subtitle">A Legacy of Inspiration and Achievement</p>
            </div>
        </header>

        <main>
            <section id="about" class="about-section">
                <img src="picture.jpg" alt="[Person's Name]" class="profile-img">
                <div class="about-content">
                    <h2>N. R. Narayana Murthy</h2>
                    <p>
                        N. R. Narayana Murthy was born on 20 August 1946 in Sidlaghatta, a city in India's south-western state of Karnataka into a middle-class Hindu family. After completing his school education, he went to the National Institute of Engineering and graduated in 1967 with a bachelor's degree in electrical engineering. In 1969 he received his master's degree from the Indian Institute of Technology Kanpur.
                    </p>
                    <p>
                        Murthy is an independent director on the corporate board of HSBC and has been a director on the boards of DBS Bank, Unilever, ICICI and NDTV.He is also a member of the advisory boards and councils of several educational and philanthropic institutions,including Cornell University, INSEAD, ESSEC, Ford Foundation, the UN Foundation, the Indo-British Partnership, Asian Institute of Management, a trustee of the Infosys Prize, a trustee of the Institute for Advanced Study in Princeton, and as a trustee of the Rhodes Trust.He is also the Chairman of the Governing board of Public Health Foundation of India.He is on the Asia Pacific advisory board of British Telecommunications.
                    </p>

                </div>
            </section>

            <section id="achievements" class="achievements-section">
                <h2>Achievements</h2>
                <ul>
                    <li>🏆Infosys - 
                        Murthy founded Infosys, a global software services company that is listed on the NYSE and the Bombay Stock Exchange.</li>
                    <li>🏆 Conceptualizing the Global Delivery Model - 
                        Murthy conceptualized, articulated, and implemented the Global Delivery Model (GDM), which has become a backbone of the Indian software industry.</li>
                    <li>🏆 Receiving awards-
                        Murthy has received many awards and honors, including:
                        Padma Shri: Received in 2000 <br>
                        Padma Vibhushan: Received in 2008 <br>
                        Honorary Commander of the Order of the British Empire: Received in 2007 <br>
                        Legion of Honour: Received in 2008 <br>
                        Woodrow Wilson Award for Corporate Citizenship: Received for his corporate citizenship <br>
                        Max Schmidheiny Freedom Prize: Received for his humanitarian work <br>
                        James C. Morgan Global Humanitarian Award: Received for his humanitarian work</li>
                </ul>
            </section>

            <section id="quote" class="quote-section">
                <h2>Inspirational Quote</h2>
                <blockquote>
                    "Growth is painful. Change is painful. But, nothing is as painful as staying stuck where you do not belong."
                </blockquote>
            </section>
        </main>

        <footer id="contact" class="footer">
            <p>Made with ❤️ by Sriharsha Induri</p>
            <p>Contact: sriharshainduri@gmail.com</p>
        </footer>
    </div>
</body>
</html>

#Tribute-page.css

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    background-color: #f9f9fc;
    color: #333;
    line-height: 1.6;
}

.container {
    max-width: 1000px;
    margin: 0 auto;
    padding: 20px;
}

/* Navbar */
.navbar {
    display: flex;
    justify-content: center;
    gap: 20px;
    background-color: #4a4a8a;
    padding: 15px 0;
}

.navbar a {
    color: #fff;
    text-decoration: none;
    font-size: 1.1em;
    transition: color 0.3s ease;
}

.navbar a:hover {
    color: #f9f9fc;
}

/* Hero Section */
.hero-section {
    background: linear-gradient(135deg, #6d6ddb, #a1a1f0);
    color: white;
    text-align: center;
    padding: 50px 0;
}

.hero-content {
    max-width: 600px;
    margin: 0 auto;
}

h1 {
    font-size: 2.5em;
    margin-bottom: 10px;
}

.subtitle {
    font-size: 1.3em;
    color: #e0e0ff;
    font-weight: 300;
}

/* About Section */
.about-section {
    display: flex;
    align-items: center;
    margin: 50px 0;
}

.profile-img {
    width: 200px;
    height: auto;
    border-radius: 10px;
    box-shadow: 0px 4px 15px rgba(0, 0, 0, 0.3);
    margin-right: 20px;
}

.about-content {
    max-width: 600px;
}

h2 {
    font-size: 2em;
    color: #4a4a8a;
    margin-bottom: 15px;
}

/* Achievements Section */
.achievements-section {
    background-color: #f0f0f7;
    padding: 30px;
    border-radius: 8px;
    margin: 50px 0;
}

ul {
    list-style-type: none;
}

ul li {
    font-size: 1.1em;
    margin-bottom: 10px;
    padding-left: 10px;
    position: relative;
}

ul li::before {
    content: "🏆";
    position: absolute;
    left: -30px;
    color: #4a4a8a;
}

/* Quote Section */
.quote-section {
    text-align: center;
    font-style: italic;
    color: #4a4a8a;
    padding: 40px;
    background: linear-gradient(135deg, #e0e0ff, #f9f9fc);
    border-radius: 8px;
}

blockquote {
    font-size: 1.5em;
    color: #4a4a8a;
    margin: 0;
}

/* Footer */
.footer {
    text-align: center;
    padding: 15px 0;
    font-size: 0.9em;
    color: #777;
    margin-top: 20px;
}
