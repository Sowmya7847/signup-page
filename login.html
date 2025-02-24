<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Auth System</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            transition: background 0.5s, color 0.5s;
            text-align: center;
        }
        .container {
            max-width: 400px;
            margin: 50px auto;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .hidden { display: none; }
        .btn {
            padding: 10px;
            margin: 10px;
            cursor: pointer;
            border: none;
            border-radius: 5px;
            transition: transform 0.3s;
        }
        .btn:hover { transform: scale(1.05); }
        .theme-toggle {
            position: absolute;
            top: 10px;
            right: 10px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <button class="theme-toggle" onclick="toggleTheme()">Switch Theme</button>
    
    <div class="container" id="welcome-page">
        <h2>Welcome!</h2>
        <button class="btn" onclick="showPage('signup-page')">Sign Up</button>
        <button class="btn" onclick="showPage('login-page')">Log In</button>
    </div>

    <div class="container hidden" id="signup-page">
        <h2>Sign Up</h2>
        <input type="email" id="signup-email" placeholder="Email" required>
        <input type="password" id="signup-password" placeholder="Password" required>
        <button class="btn" id="signup-btn">Sign Up</button>
        <button class="btn" onclick="showPage('welcome-page')">Back</button>
    </div>

    <div class="container hidden" id="login-page">
        <h2>Log In</h2>
        <input type="email" id="login-email" placeholder="Email" required>
        <input type="password" id="login-password" placeholder="Password" required>
        <button class="btn" id="login-btn">Log In</button>
        <button class="btn" onclick="showPage('forgot-password-page')">Forgot Password?</button>
        <button class="btn" onclick="showPage('welcome-page')">Back</button>
    </div>

    <div class="container hidden" id="forgot-password-page">
        <h2>Reset Password</h2>
        <input type="email" id="reset-email" placeholder="Enter your email" required>
        <button class="btn" id="reset-btn">Reset Password</button>
        <button class="btn" onclick="showPage('login-page')">Back</button>
    </div>

    <script type="module">
        import { initializeApp } from "https://www.gstatic.com/firebasejs/11.3.1/firebase-app.js";
        import { getAuth, createUserWithEmailAndPassword, signInWithEmailAndPassword, sendPasswordResetEmail } from "https://www.gstatic.com/firebasejs/11.3.1/firebase-auth.js";
        
        const firebaseConfig = {
            apiKey: "AIzaSyCp_7_xqIG00Bs1gjtc7uJ7s07pVl9YSNI",
            authDomain: "gen-lang-client-0390367057.firebaseapp.com",
            projectId: "gen-lang-client-0390367057",
            storageBucket: "gen-lang-client-0390367057.firebasestorage.app",
            messagingSenderId: "28571667369",
            appId: "1:28571667369:web:5652c6d8cc5bf9e916d2b8",
            measurementId: "G-NHR3JNZB4E"
        };

        const app = initializeApp(firebaseConfig);
        const auth = getAuth(app);
        
        document.getElementById("signup-btn").addEventListener("click", () => {
            const email = document.getElementById("signup-email").value;
            const password = document.getElementById("signup-password").value;
            
            createUserWithEmailAndPassword(auth, email, password)
                .then(() => alert("Signup successful!"))
                .catch((error) => alert(error.message));
        });

        document.getElementById("login-btn").addEventListener("click", () => {
            const email = document.getElementById("login-email").value;
            const password = document.getElementById("login-password").value;
            
            signInWithEmailAndPassword(auth, email, password)
                .then(() => window.location.href = "main.html")
                .catch((error) => alert(error.message));
        });

        document.getElementById("reset-btn").addEventListener("click", () => {
            const email = document.getElementById("reset-email").value;
            sendPasswordResetEmail(auth, email)
                .then(() => alert("Password reset email sent!"))
                .catch((error) => alert(error.message));
        });
    </script>

    <script>
        function showPage(pageId) {
            document.querySelectorAll('.container').forEach(div => div.classList.add('hidden'));
            document.getElementById(pageId).classList.remove('hidden');
        }
        
        function toggleTheme() {
            document.body.classList.toggle("dark-theme");
            if (document.body.classList.contains("dark-theme")) {
                document.body.style.background = "#1e1e2e";
                document.body.style.color = "#ffffff";
            } else {
                document.body.style.background = "#f0f0f0";
                document.body.style.color = "#000000";
            }
        }
    </script>
</body>
</html>
