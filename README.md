<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>UQ ParkSmart</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f9f9f9;
            margin: 0;
            padding: 0;
            color: #333;
            text-align: center;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            border-bottom: 4px solid #333;
        }
        h1 {
            font-size: 3.5rem;
            animation: fadeIn 2s ease-in-out;
        }
        p {
            font-size: 1.3rem;
            margin-top: 20px;
            line-height: 1.6;
            animation: slideIn 2s ease-out;
            color: #555;
        }
        .container {
            max-width: 800px;
            margin: 50px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 10px 15px rgba(0, 0, 0, 0.1);
        }
        .cta-button {
            display: inline-block;
            background-color: #FF5722;
            color: white;
            padding: 15px 30px;
            margin-top: 30px;
            font-size: 1.2rem;
            font-weight: bold;
            text-decoration: none;
            border-radius: 5px;
            transition: all 0.3s ease;
        }
        .cta-button:hover {
            background-color: #E64A19;
            transform: scale(1.1);
        }
        .feature {
            margin-top: 30px;
            font-size: 1.2rem;
            background-color: #f4f4f4;
            padding: 15px;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .feature ul {
            list-style-type: none;
            padding: 0;
        }
        .feature li {
            margin: 10px 0;
            font-size: 1.1rem;
        }
        .logos {
            display: flex;
            justify-content: center;
            gap: 40px;
            margin-top: 40px;
            flex-wrap: wrap;
        }
        .logos img {
            height: 60px;
            object-fit: contain;
        }
        .main-logo {
            margin-top: 40px;
        }
        .main-logo img {
            max-width: 300px;
            height: auto;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        @keyframes slideIn {
            from {
                transform: translateY(20px);
                opacity: 0;
            }
            to {
                transform: translateY(0);
                opacity: 1;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to UQ ParkSmart </h1>
    </header>

    <div class="container">
        <div class="main-logo">
            <img src="/mnt/data/LOGO Park Smart Draft 1 12 Apr.png" alt="Park Smart Logo">
        </div>

        <p>Tired of spending precious time searching for parking at uni? Let UQ ParkSmart streamline the process and help you find the best spot quickly and easily. </p>
        <p>Stay informed with real-time parking availability, predictive alerts, and smart recommendations to find parking quickly and efficiently. </p>

        <a href="#" class="cta-button">Download the App 📲</a>

        <div class="logos">
            <img src="/mnt/data/image.png" alt="CellOPark Australia Logo">
            <img src="/mnt/data/image.png" alt="The University of Queensland Logo">
        </div>

        <div class="feature">
            <h2>Key Features </h2>
            <ul>
                <li><strong>Live Car Park Availability</strong>: Get real-time data on car park occupancy. </li>
                <li><strong>Predictive Notifications</strong>: Receive alerts before your usual car park is full. </li>
                <li><strong>Smart Recommendations</strong>: Find the closest available parking with walking time estimates. </li>
                <li><strong>Weather-Based Alerts</strong>: Prioritise undercover parking when it rains. </li>
                <li><strong>Peak Hour Forecasting</strong>: Predict parking availability during peak hours. </li>
                <li><strong>Advance Booking System</strong>: Reserve a parking spot up to 7 days in advance, with tiered pricing to encourage fair use. </li>
                <li><strong>User Profile Management</strong>: Secure account creation with vehicle registration and UQ ID for managing bookings. </li>
                <li><strong>HEX-Style Deferred Payments</strong>: Option to pay later with interest-accruing student-style debt. </li>
                <li><strong>Incentives with UQ Vendors</strong>: Earn discounts at Boost Juice, GYG, Subway and more through a loyalty program. </li>
                <li><strong>Gamified Loyalty Tiers</strong>: Bronze, Silver, and Gold tiers unlock escalating rewards and discounts. </li>
                <li><strong>Interactive Vendor Map</strong>: Find partnered cafés and food courts across campus with special offers. </li>
                <li><strong>Auto Notifications</strong>: Get reminders for upcoming reservations and alerts when time is running out. </li>
            </ul>
        </div>
    </div>
</body>
</html>
