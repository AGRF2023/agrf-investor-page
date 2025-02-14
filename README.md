<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AGRF Investor Landing Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            text-align: center;
        }
        .container {
            max-width: 800px;
            margin: 50px auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        h1 { color: #27ae60; }
        .cta-button {
            background-color: #27ae60;
            color: white;
            padding: 15px 25px;
            text-decoration: none;
            border-radius: 5px;
            display: inline-block;
            margin-top: 10px;
        }
        .form-group {
            margin-bottom: 15px;
            text-align: left;
        }
        input, button {
            width: 100%;
            padding: 10px;
            margin-top: 5px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            background-color: #27ae60;
            color: white;
            border: none;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Invest in AGRF - The Future of Agriculture</h1>
        <p>Join the AGRF revolution and unlock exclusive staking rewards, governance rights, and high-growth opportunities.</p>
        <a href="#invest" class="cta-button">Get Started</a>
        
        <h2>Why Invest in AGRF?</h2>
        <ul>
            <li>100% staking bonus after one year (hold in MetaMask, Trust, or SafePal).</li>
            <li>Discounts on agricultural purchases (land, seeds, fertilizers, and equipment).</li>
            <li>Governance rights for project decisions.</li>
            <li>High-growth potential in the AgriTech and DeFi markets.</li>
        </ul>
        
        <h2 id="invest">Join as an Early Investor</h2>
        <form>
            <div class="form-group">
                <label for="name">Full Name:</label>
                <input type="text" id="name" name="name" required>
            </div>
            <div class="form-group">
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
            </div>
            <div class="form-group">
                <label for="wallet">Wallet Address:</label>
                <input type="text" id="wallet" name="wallet" required>
            </div>
            <button type="submit">Join Now</button>
        </form>
    </div>
</body>
</html>
