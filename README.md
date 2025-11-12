<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>The Inclusive Dictionary</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins&display=swap" rel="stylesheet" />
<style>
  body {
    margin: 0; 
    padding: 2rem;
    background-color: #363657;
    color: #FFDBE6;
    font-family: 'Poppins', sans-serif;
    display: flex;
    flex-direction: column;
    align-items: center;
    min-height: 100vh;
  }

  .container {
    max-width: 700px;
    text-align: center;
  }

  /* Logo background and layout */
  .logo {
    width: 140px;
    height: 140px;
    border-radius: 50%;
    background-color: #fff;
    padding: 10px;
    margin: 1rem auto 1.5rem;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  h1 {
    color: #FF8CA8;
    letter-spacing: 0.1em;
    font-weight: 700;
    margin-bottom: 0.2rem;
  }

  h2 {
    color: #FF8CA8;
    font-weight: 400;
    margin-bottom: 1.5rem;
  }

  p {
    font-weight: 500;
    line-height: 1.6;
    margin-bottom: 1rem;
  }

  p strong {
    font-weight: 700;
    color: #FF8CA8;
  }

  .buttons {
    margin-top: 2rem;
    display: flex;
    flex-direction: column;
    gap: 1rem;
  }

  .btn {
    background: transparent;
    border: 1px solid #FF8CA8;
    color: #FFDBE6;
    font-weight: 600;
    font-size: 1rem;
    padding: 0.5rem 1.5rem;
    border-radius: 0.75rem;
    cursor: pointer;
    text-decoration: none;
    transition: background-color 0.3s, color 0.3s;
    user-select: none;
  }

  .btn:hover, .btn:focus {
    background-color: #FF8CA8;
    color: #363657;
    outline: none;
  }

  hr {
    border: none;
    border-top: 1px solid #FF8CA8;
    margin: 2rem 0;
    opacity: 0.3;
  }

  .footer {
    margin-top: auto;
    font-size: 0.75rem;
    color: #888;
    user-select: none;
  }
</style>
</head>
<body>
  <div class="container">
    <!-- SVG logo with thin overlapping rainbow rings -->
    <div class="logo">
      <svg viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg">
        <!-- Six colored outer rings -->
        <circle cx="100" cy="40" r="35" stroke="#FF4B4B" stroke-width="8" fill="none" opacity="0.7" />
        <circle cx="150" cy="70" r="35" stroke="#FFA500" stroke-width="8" fill="none" opacity="0.7" />
        <circle cx="150" cy="130" r="35" stroke="#FFFF00" stroke-width="8" fill="none" opacity="0.7" />
        <circle cx="100" cy="160" r="35" stroke="#00FF00" stroke-width="8" fill="none" opacity="0.7" />
        <circle cx="50" cy="130" r="35" stroke="#0099FF" stroke-width="8" fill="none" opacity="0.7" />
        <circle cx="50" cy="70" r="35" stroke="#9933FF" stroke-width="8" fill="none" opacity="0.7" />
        <!-- Center ring overlapping halfway with other rings -->
        <circle cx="100" cy="100" r="30" stroke="#FF69B4" stroke-width="6" fill="none" opacity="0.9" />
      </svg>
    </div>

    <h1>THE INCLUSIVE DICTIONARY</h1>
    <h2>Welcome to The Inclusive Dictionary!</h2>

    <p><strong>This is a safe and friendly place</strong> to learn about identities, pronouns, types of attraction, plural systems, kin experiences, and more.</p>

    <p>Here you’ll find simple definitions and helpful resources to understand yourself and others. Think of this dictionary as a guide to words that matter, designed to be inclusive, welcoming, and easy to navigate.</p>

    <p><strong>Disclaimer:</strong> This guide is for learning and information only. It is not professional advice. Please seek help from qualified professionals if you need support.</p>

    <p>If you have questions, suggestions, or resources to share, please go to the contact page.</p>

    <p>Click “Explore by Topic” to explore all topics and resources.</p>
    <p>Click "Updates" to view updates that have been made to this dictionary.</p>
    <p>Note: Due to Carrd's limited assets for free users, this is not as easily navigable as we had hoped.</p>

    <div class="buttons">
      <a href="updates.html" class="btn">Updates</a>
      <hr />
      <a href="explore.html" class="btn">Explore By Topic</a>
      <hr />
      <div style="display:flex; justify-content:center; gap:1rem;">
        <a href="index.html" class="btn" style="flex:1; max-width: 150px;">Home</a>
        <a href="contact.html" class="btn" style="flex:1; max-width: 150px;">Contact/About Me</a>
      </div>
    </div>
  </div>
  <div class="footer">( Made with GitHub Pages )</div>
</body>
</html>
