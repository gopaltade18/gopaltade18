<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Gopal Tade — Embedded Systems</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
  <style>
    :root { --bg:#0b1220; --card:#121a2b; --fg:#e6edf3; --accent:#00c2ff; --muted:#9fb3c8; }
    *{box-sizing:border-box}
    body{margin:0;font-family:Inter,system-ui,Segoe UI,Roboto,Arial,sans-serif;background:var(--bg);color:var(--fg)}
    .wrap{max-width:1000px;margin:0 auto;padding:32px}
    header{display:flex;align-items:center;gap:20px;flex-wrap:wrap}
    header img{width:90px;height:90px;border-radius:20px}
    h1{margin:0;font-size:28px}
    h2{margin:28px 0 12px}
    .badges img{height:28px;margin:4px}
    .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:16px}
    .card{background:var(--card);border:1px solid #22314d;border-radius:16px;padding:16px;box-shadow:0 10px 30px rgba(0,0,0,.25)}
    .card img{width:100%;border-radius:12px}
    a.btn{display:inline-block;margin-top:10px;padding:10px 14px;border-radius:12px;background:var(--accent);color:#002b3a;text-decoration:none;font-weight:700}
    footer{margin:36px 0 12px;text-align:center;color:var(--muted)}
    .links a{margin-right:10px}
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <img src="https://avatars.githubusercontent.com/u/0000000?v=4" alt="avatar">
      <div>
        <h1>Gopal Tade — Embedded Systems Developer</h1>
        <div class="links">
          <a href="mailto:gopaltade17@gmail.com">Email</a> •
          <a href="https://linkedin.com/in/gopaltade" target="_blank">LinkedIn</a> •
          <a href="https://github.com/gopaltade18" target="_blank">GitHub</a>
        </div>
      </div>
    </header>

    <h2>Skills</h2>
    <div class="badges">
      <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white">
      <img src="https://img.shields.io/badge/Embedded%20C-008000?style=for-the-badge">
      <img src="https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white">
      <img src="https://img.shields.io/badge/ESP32-000000?style=for-the-badge">
      <img src="https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white">
      <img src="https://img.shields.io/badge/Keil-0091BD?style=for-the-badge">
      <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white">
      <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black">
    </div>

    <h2>Projects</h2>
    <div class="grid">
      <div class="card">
        <img src="assets/smarthome.png" alt="Smart Home">
        <h3>Smart Home (ESP32 + Firebase)</h3>
        <p>Voice/app control, realtime DB, OTA updates.</p>
        <a class="btn" href="https://github.com/gopaltade18/smart-home-esp32">Repository</a>
      </div>
      <div class="card">
        <img src="assets/rtos.png" alt="RTOS">
        <h3>Mini RTOS Task Scheduler</h3>
        <p>Round-robin tasks, tick timer, cooperative design.</p>
        <a class="btn" href="https://github.com/gopaltade18/mini-rtos-scheduler">Repository</a>
      </div>
      <div class="card">
        <img src="assets/rfid.png" alt="RFID">
        <h3>RFID Attendance</h3>
        <p>RC522, EEPROM logging, UART export.</p>
        <a class="btn" href="https://github.com/gopaltade18/rfid-attendance">Repository</a>
      </div>
    </div>

    <footer>© <span id="y"></span> Gopal Tade • Built for GitHub Pages</footer>
  </div>
  <script>document.getElementById('y').textContent=new Date().getFullYear()</script>
</body>
</html>
