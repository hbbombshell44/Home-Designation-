# Home-Designation-<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home Designation - Design and Build Your Real-Life Home</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(to right, #dfe9f3, #ffffff);
            color: #333;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
        }
        header {
            text-align: center;
            padding: 20px;
            background-color: #004b8d;
            color: white;
            width: 100%;
        }
        .content {
            max-width: 800px;
            padding: 20px;
            text-align: center;
        }
        .section {
            margin: 20px 0;
            padding: 20px;
            border-radius: 8px;
            background-color: #f1f5f9;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        .button {
            background-color: #004b8d;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s, transform 0.3s;
        }
        .button:hover {
            background-color: #388e3c;
            transform: scale(1.05);
        }
        .chat {
            background-color: #e0f7fa;
            padding: 10px;
            border-radius: 8px;
            max-width: 100%;
            margin: auto;
            text-align: left;
        }
        .chat p {
            margin: 5px 0;
        }
        .chat-typing::after {
            content: "|";
            animation: typing 1s steps(3, end) infinite;
        }
        @keyframes typing {
            0%, 100% { content: ""; }
            50% { content: "|"; }
        }
    </style>
</head>
<body>

<header>
    <h1>Home Designation</h1>
    <p>Design and build your real-life home from the ease of your phone or computer.</p>
</header>

<div class="content">
    <div class="section">
        <h2>Explore Your Future Home</h2>
        <p>Integrate with Google Earth, Pinterest, and major hardware stores like Lowe's and Home Depot.</p>
        <a href="#" class="button">Get Started</a>
    </div>

    <div class="section">
        <h2>Choose Your Builder</h2>
        <p>Browse and select from our trusted network of builders.</p>
        <a href="#" class="button">Select a Builder</a>
    </div>

    <div class="section">
        <h2>Live Chat with Your Builder</h2>
        <div class="chat">
            <p><strong>Builder:</strong> Welcome! Let's discuss your home building needs.</p>
            <p class="chat-typing"><strong>Builder is typing...</strong></p>
        </div>
    </div>

    <div class="section">
        <h2>View Your Build Schedule</h2>
        <p>Stay updated with real-time progress on your home construction schedule.</p>
        <a href="#" class="button">View Schedule</a>
    </div>
</div>

</body>
</html>
