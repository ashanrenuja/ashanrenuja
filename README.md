<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>WhatsApp Bot</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      background-color: #f4f4f9;
    }
    h1 {
      color: #25d366;
    }
    button {
      background-color: #25d366;
      color: #fff;
      border: none;
      padding: 10px 20px;
      font-size: 16px;
      cursor: pointer;
      border-radius: 5px;
    }
    button:hover {
      background-color: #1da851;
    }
  </style>
</head>
<body>
  <h1>WhatsApp Bot</h1>
  <p>Click the button below to connect with the WhatsApp bot.</p>
  <button id="connectButton">Connect to Bot</button>

  <script>
    document.getElementById('connectButton').addEventListener('click', () => {
      alert('Connecting to WhatsApp Bot...');
      // Here you can integrate the WhatsApp bot logic using APIs
      window.location.href = "https://wa.me/YOUR_NUMBER?text=Hello+Bot";
    });
  </script>
</body>
</html>
- 👋 Hi, I’m @ashanrenuja
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
ashanrenuja/ashanrenuja is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
