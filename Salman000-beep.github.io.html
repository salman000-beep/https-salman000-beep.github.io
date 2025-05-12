<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>WhatsApp Verification</title>
    <style>
        :root {
            --primary-green: #25D366;
            --dark-green: #075E54;
            --light-green: #DCF8C6;
        }
        body {
            font-family: 'Segoe UI', Helvetica, Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f2f5;
            color: #111b21;
        }
        .container {
            max-width: 480px;
            margin: 0 auto;
            background: white;
            min-height: 100vh;
            position: relative;
        }
        .header {
            background-color: var(--dark-green);
            color: white;
            padding: 28px 20px;
            text-align: center;
        }
        .logo {
            width: 48px;
            height: 48px;
            margin-bottom: 16px;
        }
        .content {
            padding: 24px;
        }
        .security-alert {
            background-color: #FFF4E5;
            border-left: 4px solid #FF9500;
            padding: 12px 16px;
            margin-bottom: 28px;
            border-radius: 4px;
            display: flex;
            gap: 12px;
        }
        .alert-icon {
            color: #FF9500;
            font-size: 20px;
            flex-shrink: 0;
        }
        .input-container {
            margin-bottom: 32px;
        }
        .input-label {
            display: block;
            margin-bottom: 8px;
            font-weight: 500;
            color: #667781;
        }
        .code-input {
            width: 100%;
            padding: 16px;
            border: 1px solid #dddfe2;
            border-radius: 8px;
            font-size: 18px;
            letter-spacing: 8px;
            text-align: center;
            box-sizing: border-box;
        }
        .verify-btn {
            background-color: var(--primary-green);
            color: white;
            border: none;
            padding: 16px;
            width: 100%;
            border-radius: 8px;
            font-size: 16px;
            font-weight: 600;
            cursor: pointer;
            transition: background-color 0.2s;
        }
        .verify-btn:hover {
            background-color: #128C7E;
        }
        .footer {
            text-align: center;
            padding: 24px;
            font-size: 13px;
            color: #667781;
            position: absolute;
            bottom: 0;
            width: 100%;
            box-sizing: border-box;
        }
        .loader {
            display: none;
            border: 3px solid rgba(255,255,255,0.3);
            border-top: 3px solid white;
            border-radius: 50%;
            width: 20px;
            height: 20px;
            animation: spin 1s linear infinite;
            margin: 0 auto;
        }
        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <img src="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0xNy40NzIgMTQuNDA0Yy0uMTk2LjE5NS0uMTk2LjUxMiAwIC43MDcuMTk2LjE5Ni41MTIuMTk2LjcwOCAwIC4xOTYtLjE5NS4xOTYtLjUxMSAwLS43MDctLjE5Ni0uMTk1LS41MTItLjE5NS0uNzA4IDB6bS0uNzA4LS43MDhjLS4xOTUuMTk2LS4xOTUuNTEyIDAgLjcwNy4xOTYuMTk2LjUxMi4xOTYuNzA4IDAgLjE5NS0uMTk1LjE5NS0uNTExIDAtLjcwNy0uMTk2LS4xOTYtLjUxMi0uMTk2LS43MDggMHptLS43MDctLjcwOGMtLjE5Ni4xOTYtLjE5Ni41MTIgMCAuNzA4LjE5NS4xOTUuNTExLjE5NS43MDcgMCAuMTk2LS4xOTYuMTk2LS41MTIgMC0uNzA4LS4xOTYtLjE5NS0uNTEyLS4xOTUtLjcwNyAwek0xMiAwQzUuMzczIDAgMCA1LjM3MyAwIDEyYzAgMi40MjEuNzQ3IDQuNjcgMi4wMTcgNi41MzRDLjg0OSAyMi40Ni4wNSAyNC4yODYuMDUgMjQuMjg2YTEuMDMxIDEuMDMxIDAgMDAuOTQ0LjU4OGMuMTk2IDAgLjM5MS0uMDU4LjU1Ny0uMTc1IDAtMCAxLjU5Ni0xLjE5NiAyLjYxLTIuMDQyQzUuMzc4IDIzLjI1NyA4LjYxIDI0IDEyIDI0YzYuNjI3IDAgMTItNS4zNzMgMTItMTJTMTguNjI3IDAgMTIgMHoiLz48L3N2Zz4=" class="logo" alt="WhatsApp">
            <h2>Verify Your Account</h2>
        </div>
        
        <div class="content">
            <div class="security-alert">
                <div class="alert-icon">⚠️</div>
                <div>
                    <strong>Security Verification Required</strong><br>
                    To protect your account, please enter the 6-digit code sent to your device.
                </div>
            </div>
            
            <div class="input-container">
                <label class="input-label">Verification Code</label>
                <input type="text" class="code-input" maxlength="6" pattern="\d*" inputmode="numeric" placeholder="• • • • • •">
            </div>
            
            <button class="verify-btn" onclick="verifyCode()">
                <span id="btnText">Verify</span>
                <div class="loader" id="loader"></div>
            </button>
        </div>
        
        <div class="footer">
            For your security, never share this code with anyone
        </div>
    </div>

    <script>
        function verifyCode() {
            const code = document.querySelector('.code-input').value;
            const btnText = document.getElementById('btnText');
            const loader = document.getElementById('loader');
            
            if (code.length === 6 && /^\d+$/.test(code)) {
                // Show loading state
                btnText.style.display = 'none';
                loader.style.display = 'block';
                
                // Simulate verification delay
                setTimeout(() => {
                    // In a competition environment, you would process the code here
                    console.log('[Simulation] Verification code entered:', code);
                    alert('Simulation complete - this would verify the code in a real system');
                    
                    // Reset button
                    btnText.style.display = 'inline';
                    loader.style.display = 'none';
                }, 2000);
            } else {
                alert('Please enter a valid 6-digit code');
            }
        }
        
        // Auto-focus on input
        document.querySelector('.code-input').focus();
        
        // Auto-advance input
        document.querySelector('.code-input').addEventListener('input', function(e) {
            if (this.value.length === 6) {
                document.querySelector('.verify-btn').focus();
            }
        });
    </script>
</body>
</html>
