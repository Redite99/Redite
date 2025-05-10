<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Redite Bista ✨</title>
    <style>
        body {
            font-family: 'Comic Sans MS', cursive, sans-serif;
            background: linear-gradient(135deg, #ffcce6, #ccf2ff);
            text-align: center;
            padding: 30px;
            min-height: 100vh;
        }
        
        .hidden-message {
            display: none;
        }
        
        .social-links {
            margin: 30px 0;
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }
        
        .social-links a {
            padding: 12px 20px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            transition: all 0.3s;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        
        .instagram {
            background: linear-gradient(45deg, #f09433, #e6683c, #dc2743, #cc2366, #bc1888);
            color: white;
        }
        
        .facebook {
            background: #3b5998;
            color: white;
        }
        
        .youtube {
            background: #ff0000;
            color: white;
        }
        
        .social-links a:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 15px rgba(0,0,0,0.2);
        }
        
        .creator-text {
            font-size: 24px;
            color: #ff66b3;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.1);
            margin-top: 30px;
            background: white;
            padding: 15px;
            border-radius: 20px;
            display: inline-block;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        
        .cute-emoji {
            font-size: 30px;
            margin: 0 5px;
        }
        
        .decoration {
            position: absolute;
            font-size: 20px;
            opacity: 0.6;
            animation: float 4s ease-in-out infinite;
        }
        
        @keyframes float {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-20px); }
        }
    </style>
</head>
<body>
    <!-- Hidden message -->
    <div class="hidden-message">Hi i am Redite</div>
    
    <!-- Floating decorations -->
    <div class="decoration" style="top: 10%; left: 10%;">🌸</div>
    <div class="decoration" style="top: 20%; right: 15%;">✨</div>
    <div class="decoration" style="bottom: 15%; left: 20%;">🍭</div>
    <div class="decoration" style="bottom: 25%; right: 10%;">🎀</div>
    
    <!-- Social Links -->
    <div class="social-links">
        <a href="https://www.instagram.com/reditebista11/" class="instagram" target="_blank">
            <span class="cute-emoji">📷</span> Instagram
        </a>
        <a href="https://www.facebook.com/reditebista1" class="facebook" target="_blank">
            <span class="cute-emoji">👍</span> Facebook
        </a>
        <a href="https://www.youtube.com/@reditebista4788" class="youtube" target="_blank">
            <span class="cute-emoji">▶️</span> YouTube
        </a>
    </div>
    
    <!-- Creator Text -->
    <div class="creator-text">
        Redite Bista <span class="cute-emoji">✨</span> content creator
    </div>
</body>
</html>
