<html lang="en"> 
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>The Inclusive Dictionary</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    body {
      background-color: #363657;
      color: #FFDBE6;
      font-family: 'Poppins', sans-serif;
      letter-spacing: 0.15em;
      text-align: center;
      margin: 0;
      padding: 0;
    }

    .container {
      max-width: 700px;
      margin: 60px auto;
      padding: 20px;
    }

    /* SVG Logo */
    .logo {
      width: 140px;
      height: 140px;
      margin: 0 auto 25px;
    }

    .logo svg {
      width: 100%;
      height: auto;
      display: block;
    }

    .title {
      color: #FF8CA8;
      font-weight: 700;
      font-size: 1.8rem;
    }

    .subtitle {
      color: #FFB0C0;
      font-weight: 600;
      margin-bottom: 20px;
    }

    .description {
      font-weight: 400;
      line-height: 1.6;
    }

    .description strong {
      font-weight: 600;
    }

    .disclaimer {
      color: #FFDBE6;
      margin-top: 25px;
      line-height: 1.5;
    }

    .disclaimer strong {
      color: #FF8CA8;
    }

    .btn {
      background: transparent;
      color: #FFDBE6;
      border: 2px solid #FFB0C0;
      border-radius: 0.75rem;
      padding: 10px 24px;
      margin: 8px;
      font-family: 'Poppins', sans-serif;
      font-size: 1rem;
      letter-spacing: 0.1em;
      cursor: pointer;
      transition: all 0.25s ease-in-out;
    }

    .btn:hover {
      background-color: #FF879F;
      color: #363657;
    }

    .bottom-buttons {
      margin-top: 10px; 
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- SVG Logo -->
    <div class="logo">
      <svg viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg">
        <!-- Inner rainbow ring -->
        <circle cx="100" cy="100" r="55" stroke="#FF4B4B" stroke-width="8" fill="none"
                stroke-dasharray="57.6 288" stroke-dashoffset="0" opacity="0.9" />
        <circle cx="100" cy="100" r="55" stroke="#FFA500" stroke-width="8" fill="none"
                stroke-dasharray="57.6 288" stroke-dashoffset="57.6" opacity="0.9" />
        <circle cx="100" cy="100" r="55" stroke="#FFFF00" stroke-width="8" fill="none"
                stroke-dasharray="57.6 288" stroke-dashoffset="115.2" opacity="0.9" />
        <circle cx="100" cy="100" r="55" stroke="#00FF00" stroke-width="8" fill="none"
                stroke-dasharray="57.6 288" stroke-dashoffset="172.8" opacity="0.9" />
        <circle cx="100" cy="100" r="55" stroke="#0099FF" stroke-width="8" fill="none"
                stroke-dasharray="57.6 288" stroke-dashoffset="230.4" opacity="0.9" />
        <circle cx="100" cy="100" r="55" stroke="#9933FF" stroke-width="8" fill="none"
                stroke-dasharray="57.6 288" stroke-dashoffset="288" opacity="0.9" />

        <!-- Outer colored rings -->
        <circle cx="100" cy="40"  r="35" stroke="#FFFF00" stroke-width="8" fill="none" opacity="0.7" />
        <circle cx="150" cy="70"  r="35" stroke="#FFA500" stroke-width="8" fill="none" opacity="0.7" />
        <circle cx="150" cy="130" r="35" stroke="#FF4B4B" stroke-width="8" fill="none" opacity="0.7" />
        <circle cx="100" cy="160" r="35" stroke="#9933FF" stroke-width="8" fill="none" opacity="0.7" />
        <circle cx="50"  cy="130" r="35" stroke="#0099FF" stroke-width="8" fill="none" opacity="0.7" />
        <circle cx="50"  cy="70"  r="35" stroke="#00FF00" stroke-width="8" fill="none" opacity="0.7" />
      </svg>
    </div>

    <h1 class="title">THE INCLUSIVE DICTIONARY</h1>
    <h2 class="subtitle">Welcome to The Inclusive Dictionary!</h2>

    <p class="description">
      This is a safe and friendly place to learn about identities, pronouns, types of attraction, plural systems, kin experiences, and more.<br><br>
      <strong>Here you’ll find simple definitions and helpful resources to understand yourself and others. Think of this dictionary as a guide to words that matter, designed to be inclusive, welcoming, and easy to navigate.</strong>
    </p>

    <p class="disclaimer">
      <strong>Disclaimer:</strong> This guide is for learning and information only. It is not professional advice. Please seek help from qualified professionals if you need support.
    </p>

    <p>
      If you have questions, suggestions, or resources to share, please go to the contact page.<br><br>
      Click “Explore by Topic” to explore all topics and resources.<br><br>
      Click “Updates” to view updates that have been made to this dictionary.
    </p>

    <div class="buttons">
      <button class="btn">Updates</button>
      <button class="btn">Explore By Topic</button>
      <div class="bottom-buttons">
        <button class="btn">Home</button>
        <button class="btn">Contact/About Me</button>
      </div>
    </div>
  </div>
</body>
</html>
