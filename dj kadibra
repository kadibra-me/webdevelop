<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>KADIBRA_The_DJ</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: black;
      color: white;
    }
    header {
      background: #222;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 10px;
      text-decoration: none;
    }
    nav a:hover {
      color: pink;
    }
    section {
      padding: 20px;
    }
    h1, h2 {
      color: hotpink;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 10px;
    }
    th, td {
      border: 1px solid #555;
      padding: 8px;
      text-align: left;
    }
    .gallery {
      display: flex;
      gap: 10px;
      flex-wrap: wrap;
    }
    .gallery img {
      width: 150px;
      height: 100px;
      object-fit: cover;
      border: 2px solid #ff4081;
    }
    form input, form textarea {
      width: 100%;
      padding: 8px;
      margin: 5px 0;
    }
    button {
      background: #ff4081;
      border: none;
      padding: 10px;
      color: white;
      cursor: pointer;
    }
    button:hover {
      background: #e91e63;
    }
  </style>
</head>
<body>

  <header>
    <h1>KADIBRA😎 | DJ Portfolio</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#gallery">Gallery</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>Hi, I’m David aka Kadibra😌. I’m a student at Machakos University and a rising DJ. I mix Kenyan culture with hype energy to keep crowds moving.</p>
  </section>

  <section id="services">
    <h2>Services</h2>
    <table>
      <tr>
        <th>Package</th>
        <th>Details</th>
      </tr>
      <tr>
        <td>Basic Set</td>
        <td>DJ set + playlist</td>
      </tr>
      <tr>
        <td>Culture Mix</td>
        <td>1-hour Kenyan cultural set</td>
      </tr>
      <tr>
        <td>Full Event</td>
        <td>DJ + sound system + décor</td>
      </tr>
    </table>
  </section>

  <section id="gallery">
    <h2>Gallery</h2>
    <div class="gallery">
      <img src="alipi.jpg" alt="DJ set">
      <img src="sawa.jpg" alt="Crowd">
      <img src="lipa.jpg" alt="Event">
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <form id="contactForm">
      <input type="text" id="name" placeholder="Your Name" required>
      <input type="email" id="email" placeholder="Your Email" required>
      <textarea id="message" placeholder="Your Message" required></textarea>
      <button type="submit">Send</button>
    </form>
    <p id="feedback"></p>
  </section>

  <script>
        document.getElementById("contactForm").addEventListener("submit", function(e){
      e.preventDefault();
      let name = document.getElementById("name").value;
      let email = document.getElementById("email").value;
      let message = document.getElementById("message").value;
      if(name && email && message){
        document.getElementById("feedback").innerText = "Thanks " + name + "! Your message has been sent.";
      } else {
        document.getElementById("feedback").innerText = "Please fill all fields.";
      }
    });
  </script>

</body>
</html>
