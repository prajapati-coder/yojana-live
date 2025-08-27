# yojana-live
भारत सरकार की नई योजनाओं की जानकारी देने वाला पोर्टल | Yojana Live
Government schemes updates website | Bharat Sarkar Yojana Portal<h1>भारत सरकार की योजनाएँ</h1>
<ul>
  <li>प्रधानमंत्री आवास योजना</li>
  <li>उज्ज्वला योजना</li>
  <li>जन धन योजना</li>
</ul>
<!DOCTYPE html>
<html lang="hi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Yojana Live | भारत सरकार की नई योजनाएँ</title>
  <style>
    /* ------------------- Reset ------------------- */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Segoe UI", Arial, sans-serif;
    }

    body {
      background: #f7f8fc;
      color: #333;
      line-height: 1.6;
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    /* ------------------- Header ------------------- */
    header {
      background: #1e3a8a;
      color: white;
      padding: 1rem 2rem;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    header h1 {
      font-size: 1.8rem;
    }

    nav {
      margin-top: 0.5rem;
    }

    nav a {
      margin-right: 1rem;
      font-weight: 500;
      color: #e0e7ff;
    }

    nav a:hover {
      color: #fff;
    }

    /* ------------------- Hero Section ------------------- */
    .hero {
      background: url('https://source.unsplash.com/1200x400/?india,government') no-repeat center/cover;
      height: 350px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-align: center;
      padding: 2rem;
    }

    .hero h2 {
      font-size: 2.2rem;
      background: rgba(0,0,0,0.5);
      padding: 1rem 2rem;
      border-radius: 12px;
    }

    /* ------------------- Search ------------------- */
    .search-section {
      padding: 2rem;
      text-align: center;
    }

    .search-section input {
      width: 60%;
      padding: 0.8rem;
      border: 2px solid #1e3a8a;
      border-radius: 8px;
      font-size: 1rem;
    }

    /* ------------------- Schemes Section ------------------- */
    .schemes {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 1.5rem;
      padding: 2rem;
    }

    .scheme-card {
      background: white;
      border-radius: 12px;
      padding: 1.5rem;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
      transition: transform 0.2s;
    }

    .scheme-card:hover {
      transform: translateY(-5px);
    }

    .scheme-card h3 {
      color: #1e3a8a;
      margin-bottom: 0.5rem;
    }

    .scheme-card p {
      font-size: 0.95rem;
      color: #444;
    }

    /* ------------------- Footer ------------------- */
    footer {
      background: #1e3a8a;
      color: white;
      padding: 1.5rem;
      text-align: center;
      margin-top: 2rem;
    }

    footer p {
      margin: 0.3rem 0;
    }

    @media (max-width: 600px) {
      .search-section input {
        width: 90%;
      }
      .hero h2 {
        font-size: 1.6rem;
      }
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <h1>Yojana Live</h1>
    <nav>
      <a href="#">होम</a>
      <a href="#schemes">योजनाएँ</a>
      <a href="#about">हमारे बारे में</a>
      <a href="#contact">संपर्क</a>
    </nav>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <h2>भारत सरकार की नई-नई योजनाओं की जानकारी एक ही जगह</h2>
  </section>

  <!-- Search -->
  <section class="search-section">
    <input type="text" id="searchBox" placeholder="योजना खोजें...">
  </section>

  <!-- Schemes Section -->
  <section class="schemes" id="schemes">
    <div class="scheme-card">
      <h3>प्रधानमंत्री आवास योजना</h3>
      <p>शहरी और ग्रामीण गरीबों को सस्ती दर पर घर उपलब्ध कराने की योजना।</p>
    </div>

    <div class="scheme-card">
      <h3>उज्ज्वला योजना</h3>
      <p>गरीब परिवारों को मुफ्त गैस कनेक्शन उपलब्ध कराने के लिए शुरू की गई योजना।</p>
    </div>

    <div class="scheme-card">
      <h3>जन धन योजना</h3>
      <p>हर नागरिक को बैंक खाता उपलब्ध कराने की योजना, जिससे सबका वित्तीय समावेशन हो।</p>
    </div>

    <div class="scheme-card">
      <h3>प्रधानमंत्री किसान सम्मान निधि</h3>
      <p>किसानों को सालाना 6000 रुपये की सहायता सीधे उनके बैंक खाते में।</p>
    </div>

    <div class="scheme-card">
      <h3>आयुष्मान भारत योजना</h3>
      <p>गरीब और वंचित परिवारों को 5 लाख तक का स्वास्थ्य बीमा कवरेज।</p>
    </div>

    <div class="scheme-card">
      <h3>प्रधानमंत्री स्वरोजगार योजना</h3>
      <p>युवाओं को रोजगार शुरू करने के लिए लोन और सहायता प्रदान करना।</p>
    </div>
  </section>

  <!-- Footer -->
  <footer id="about">
    <p><strong>Yojana Live</strong> - भारत सरकार की योजनाओं की जानकारी देने वाला पोर्टल</p>
    <p id="contact">📧 संपर्क करें: info@yojanalive.in</p>
    <p>© 2025 Yojana Live. सर्वाधिकार सुरक्षित।</p>
  </footer>

  <!-- Script -->
  <script>
    // Simple Search Filter
    const searchBox = document.getElementById('searchBox');
    const cards = document.querySelectorAll('.scheme-card');

    searchBox.addEventListener('keyup', function() {
      let query = searchBox.value.toLowerCase();
      cards.forEach(card => {
        let text = card.innerText.toLowerCase();
        if (text.includes(query)) {
          card.style.display = "block";
        } else {
          card.style.display = "none";
        }
      });
    });
  </script>
</body>
</html>
