<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sadaqah Network - Muslim Charity</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background: #008000;
            color: white;
            text-align: center;
            padding: 1rem;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            padding: 20px;
        }
        .donate-section {
            background: #ffd700;
            padding: 20px;
            text-align: center;
        }
        .donate-btn {
            background: #008000;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            font-size: 18px;
            border-radius: 5px;
            display: inline-block;
        }
        .donate-btn:hover {
            background: #006600;
        }
        .section {
            background: white;
            margin: 20px 0;
            padding: 20px;
            border-radius: 10px;
        }
        footer {
            background: #222;
            color: white;
            text-align: center;
            padding: 10px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Sadaqah Network</h1>
        <p>Supporting Orphans, the Needy & Islamic Causes</p>
    </header>
    
    <div class="container">
        <section class="donate-section">
            <h2>Make a Difference Today</h2>
            <p>Your donation helps orphans, provides food, and supports education.</p>
            <a href="#donate" class="donate-btn">Donate Now</a>
        </section>
        
        <section class="section">
            <h2>Our Mission</h2>
            <p>We are a Muslim charity organization dedicated to helping orphans, supporting less privileged children, funding education, and providing food for those in need.</p>
        </section>
        
        <section class="section">
            <h2>How You Can Help</h2>
            <ul>
                <li>Sponsor an Orphan</li>
                <li>Contribute to the Food Bank</li>
                <li>Provide Tuition Support</li>
                <li>Help Imams and Islamic Scholars</li>
                <li>Support Eid & Ramadan Giving</li>
            </ul>
        </section>
        
        <section class="section">
            <h2>Live Donation Tracker</h2>
            <p>Total Donations: <span id="donation-amount">$0</span></p>
            <button class="donate-btn" onclick="increaseDonation()">Contribute Now</button>
        </section>
    </div>
    
    <footer>
        <p>&copy; 2025 Sadaqah Network | Helping Those in Need</p>
    </footer>
    
    <script>
        let donationAmount = 0;
        function increaseDonation() {
            donationAmount += 10;
            document.getElementById('donation-amount').innerText = '$' + donationAmount;
        }
    </script>
</body>
</html>
