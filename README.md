Modify this so the text is white:

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Christina's Research Website| Research</title>
  <style>
    body {
      font-family: Georgia, serif;
      margin: 0;
      padding: 2rem;
      max-width: 850px;
      margin-left: auto;
      margin-right: auto;
      background-color: #000000;
      color: #ffffff;
      line-height: 1.6;
    }
    header {
      display: flex;
      align-items: center;
      gap: 1.5rem;
      margin-bottom: 2rem;
    }
    img.profile {
      width: 150px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.5);
    }
    h1 {
      font-size: 2em;
      margin: 0;
      color: #ffffff;
    }
    h2 {
      color: #ffffff;
      margin-top: 2rem;
    }
    a {
      color: #ffffff;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    .button {
      display: inline-block;
      margin-top: 1rem;
      padding: 0.5rem 1rem;
      background-color: #117864;
      color: white;
      border-radius: 5px;
      text-decoration: none;
      font-weight: bold;
    }
    .button:hover {
      background-color: #ffffff;
    }
  </style>
</head>
<body>
   <header>
    <img src="Singh_Christina_web.jpg" alt="Christina Singh" class="profile" />
    <div>
      <h1>Christina Singh</h1>
      <p><em>Graduate Research Assistant | Planetary Science</em></p>
      <a href="cv.pdf" class="button" target="_blank">Download CV</a>
    </div>
  </header>
  <h2>About Me</h2>
  <p>
    I'm a first-year graduate research assistant studying boulder distributions on midlatitude Martian ice sheets a the University of Arizona's Lunar and Planetary Lab with Dr. Shane Byrne.
    My work focuses on analyzing geomorphological data to assess the Martian paleoclimate and water budgets.
  </p>

  <h2>Research Interests</h2>
  <ul>
    <li>Planetary Surface Processes</li>
    <li>Photogrammetry</li>
    <li>Planetary Analogs</li>
    <li>Astrobiology</li>
  </ul>

  <h2>Publications</h2>
  <p>Coming soon...</p>

  <h2>Contact</h2>
  <p>Email: <a href="mailto:christina@arizona.edu">christina@arizona.edu</a></p>
  <p>GitHub: <a href="https://github.com/christinaysingh" target="_blank">christinaysingh</a></p>
</body>
