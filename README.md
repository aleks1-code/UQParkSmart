<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>UQParkSmart</title>
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
        .feature li::before {
            content: "🔹";
            margin-right: 8px;
        }
        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
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
        <h1>Welcome to UQParkSmart 🚗💡</h1>
    </header>

    <div class="container">
        <p>Welcome to UQParkSmart, your go-to solution for finding parking at the University of Queensland! 🚘</p>
        <p>Stay informed with real-time parking availability, predictive alerts, and smart recommendations to find parking quickly and efficiently. 🚗💨</p>
        
        <a href="#" class="cta-button">Download the App 📲</a>
        
        <div class="feature">
            <h2>Key Features 🛠️</h2>
            <ul>
                <li><strong>Live Car Park Availability</strong>: Get real-time data on car park occupancy. 🚙</li>
                <li><strong>Predictive Notifications</strong>: Receive alerts before your usual car park is full. ⏰</li>
                <li><strong>Smart Recommendations</strong>: Find the closest available parking with walking time estimates. 🏃‍♂️</li>
                <li><strong>Weather-Based Alerts</strong>: Prioritize undercover parking when it rains. 🌧️</li>
                <li><strong>Peak Hour Forecasting</strong>: Predict parking availability during peak hours. ⏳</li>
            </ul>
        </div>
    </div>
</body>
</html>
