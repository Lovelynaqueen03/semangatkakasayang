# semangatkakasayang
ily somaatt
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Pesan Manis 🎀</title>
  <link rel="stylesheet" href="style.css" />
  <link href="https://fonts.googleapis.com/css2?family=Comic+Neue&display=swap" rel="stylesheet">
</head>
<body>
  <div class="container">
    <h1>💌 Pesan Buat Kaka</h1>

    <button id="playButton">▶️ Play</button>
    <button id="pauseButton">⏸️ Pause</button>
    <audio id="bgMusic" loop>
      <source src="melody_piano_cinta.mp3" type="audio/mpeg" />
      Browser kamu tidak mendukung audio 😢
    </audio>

    <div class="message-box">
      <p>
        haloo kakaa semangatttt yaa ngejalaanin kesibukannyaa aku selalu adaa disini buatt support kamuuu🙆🏻‍♀️🙆🏻‍♀️🫶🏻‍🫶🏻
        jangan pernah ngerasa bersalah yaa karna terlalu sibuk dan jarang ada waktu buat akuu.. its okaay kok akuu bisa
        ngertiin kesibukann kamuu, yang penting usahain bisa tetep ngabarin akuu yaa .. sekerdar bilang “aku sibuk sebentar yaaa”
        jugaa gapapaa kok akuu pahamm bangettt okaayy??? akuu akan selalu disini nunggu kamuu nyelesaain semuaa nyaa🫰🏻
        jangann lupaa jagaa kesehatann yaa di sela sela kesibukan kamuuu🙆🏻‍♀️🙆🏻‍♀️💋 ailafyuu kakaaa
      </p>
    </div>

    <div class="from-to">
      <p><strong>from :</strong> sabian baik, imut, cantik nan menggemaskan</p>
      <p><strong>to :</strong> kaka sayangg slankers abadi piss🤞🏻⭐️</p>
    </div>

    <footer>
      <p>💗 Dibuat khusus buat kamu 🥺</p>
    </footer>
  </div>

  <script src="script.js"></script>
</body>
</html>
body {
  margin: 0;
  padding: 0;
  font-family: 'Comic Neue', cursive;
  background: linear-gradient(to bottom right, #ffe6f0, #ffc9e3);
  color: #444;
}

.container {
  max-width: 700px;
  margin: auto;
  padding: 20px;
  text-align: center;
}

h1 {
  color: #ff69b4;
  font-size: 2.3em;
  margin-top: 30px;
  animation: fadeIn 1.5s ease;
}

.message-box {
  background-color: #fff0f8;
  border-radius: 15px;
  padding: 25px;
  margin: 30px 0;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  font-size: 1.1em;
  line-height: 1.8em;
  text-align: justify;
  white-space: pre-line;
}

.from-to {
  background-color: #ffe0f0;
  border-radius: 10px;
  padding: 15px;
  font-size: 1.05em;
  color: #cc0077;
  margin-top: 20px;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

button {
  background-color: #ffb6c1;
  border: none;
  padding: 10px 20px;
  font-size: 1em;
  margin: 10px;
  border-radius: 10px;
  cursor: pointer;
  color: white;
  transition: background-color 0.3s;
}

button:hover {
  background-color: #ff69b4;
}

footer {
  margin-top: 40px;
  font-size: 0.9em;
  color: #888;
}

@keyframes fadeIn {
  from { opacity: 0; transform: translateY(-20px); }
  to { opacity: 1; transform: translateY(0); }
}
const music = document.getElementById("bgMusic");
const playButton = document.getElementById("playButton");
const pauseButton = document.getElementById("pauseButton");

playButton.onclick = () => music.play();
pauseButton.onclick = () => music.pause();


