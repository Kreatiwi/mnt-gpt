<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Registrierung</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            max-width: 400px;
            margin: 50px auto;
            padding: 20px;
        }
        .form-group {
            margin-bottom: 15px;
        }
        input {
            width: 100%;
            padding: 8px;
            margin-top: 5px;
        }
        button {
            width: 100%;
            padding: 10px;
            background-color: #4CAF50;
            color: white;
            border: none;
            cursor: pointer;
        }
        .message {
            margin-top: 15px;
            padding: 10px;
            border-radius: 5px;
        }
        .success {
            background-color: #d4edda;
            color: #155724;
        }
        .error {
            background-color: #f8d7da;
            color: #721c24;
        }
    </style>
</head>
<body>
<h2>Registrieren</h2>
<form id="registerForm">
    <div class="form-group">
        <label for="username">Benutzername</label>
        <input type="text" id="username" name="username" required minlength="3" />
    </div>
    <div class="form-group">
        <label for="password">Passwort</label>
        <input type="password" id="password" name="password" required minlength="8" />
    </div>
    <div class="form-group">
        <label for="confirm_password">Passwort bestätigen</label>
        <input type="password" id="confirm_password" name="confirm_password" required minlength="8" />
    </div>
    <button type="submit">Registrieren</button>
</form>

<div id="message" class="message" style="display: none;"></div>

<script>
    const form = document.getElementById('registerForm')
    const messageBox = document.getElementById('message')

    form.addEventListener('submit', async (e) => {
        e.preventDefault()

        const username = form.username.value.trim()
        const password = form.password.value
        const confirm = form.confirm_password.value

        if (password !== confirm) {
            messageBox.textContent = "❌ Die Passwörter stimmen nicht überein!"
            messageBox.className = "message error"
            messageBox.style.display = "block"
            return
        }

        try {
            const res = await fetch("https://keepznnvijtatmbfxbar.functions.supabase.co/register-user", {
                method: "POST",
                headers: { "Content-Type": "application/json" },
                body: JSON.stringify({ username, password })
            })

            const result = await res.json()

            if (result.success) {
                messageBox.textContent = "✅ Registrierung erfolgreich! Du kannst dich jetzt anmelden."
                messageBox.className = "message success"
                form.reset()
            } else {
                messageBox.textContent = "❌ " + result.error
                messageBox.className = "message error"
            }

            messageBox.style.display = "block"
        } catch (err) {
            messageBox.textContent = "❌ Netzwerkfehler: " + err.message
            messageBox.className = "message error"
            messageBox.style.display = "block"
        }
    })
</script>
</body>
</html>
