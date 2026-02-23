<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Best Credit Cards India</title>

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f5f6fa;
      color: #333;
    }

    header {
      background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
      color: white;
      text-align: center;
      padding: 40px 20px;
    }

    .cards {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      padding: 20px;
    }

    .card {
      background: white;
      padding: 20px;
      width: 280px;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      text-align: center;
      transition: transform 0.2s;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    button {
      margin-top: 10px;
      padding: 10px 20px;
      border: none;
      border-radius: 6px;
      background: #007bff;
      color: white;
      cursor: pointer;
    }

    button:hover {
      background: #0056b3;
    }

    .comparison {
      padding: 20px;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      background: white;
    }

    th, td {
      padding: 12px;
      border: 1px solid #ddd;
      text-align: center;
    }

    th {
      background: #007bff;
      color: white;
    }

    .faq {
      padding: 20px;
    }

    .faq-item h3 {
      cursor: pointer;
      background: #eee;
      padding: 10px;
      border-radius: 6px;
    }

    .faq-item p {
      display: none;
      padding: 10px;
      background: white;
      border-left: 3px solid #007bff;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #111;
      color: white;
      margin-top: 20px;
    }
  </style>
</head>

<body>

<header>
  <h1>💳 Best Credit Cards in India</h1>
  <p>Compare top cards & choose the best one for your lifestyle</p>
</header>

<section class="cards">

  <div class="card">
    <h2>HDFC Millennia</h2>
    <p>5% cashback on Amazon & Flipkart</p>
    <button onclick="applyNow('HDFC Millennia')">Apply Now</button>
  </div>

  <div class="card">
    <h2>SBI SimplyCLICK</h2>
    <p>10X rewards on online shopping</p>
    <button onclick="applyNow('SBI SimplyCLICK')">Apply Now</button>
  </div>

  <div class="card">
    <h2>ICICI Amazon Pay</h2>
    <p>Unlimited cashback on Amazon purchases</p>
    <button onclick="applyNow('ICICI Amazon Pay')">Apply Now</button>
  </div>

</section>

<section class="comparison">
  <h2>📊 Credit Card Comparison</h2>

  <table>
    <tr>
      <th>Card</th>
      <th>Annual Fee</th>
      <th>Rewards</th>
      <th>Best For</th>
    </tr>

    <tr>
      <td>HDFC Millennia</td>
      <td>₹1000</td>
      <td>5% Cashback</td>
      <td>Online Shopping</td>
    </tr>

    <tr>
      <td>SBI SimplyCLICK</td>
      <td>₹499</td>
      <td>10X Points</td>
      <td>E-commerce</td>
    </tr>

    <tr>
      <td>ICICI Amazon Pay</td>
      <td>Free</td>
      <td>5% Cashback</td>
      <td>Amazon Users</td>
    </tr>

  </table>
</section>

<section class="faq">
  <h2>❓ FAQs</h2>

  <div class="faq-item">
    <h3 onclick="toggleFAQ(this)">Which card is best for beginners?</h3>
    <p>The ICICI Amazon Pay card is great for beginners due to zero annual fee.</p>
  </div>

  <div class="faq-item">
    <h3 onclick="toggleFAQ(this)">Do I need income proof?</h3>
    <p>Yes, banks require income proof for most credit cards.</p>
  </div>

</section>

<footer>
  <p>⚠️ Disclaimer: This website is for informational purposes only. We are not a bank or financial institution. Please verify all details on official bank websites before applying.</p>
</footer>

<script>
  function applyNow(cardName) {
    alert("You selected " + cardName + ". Redirecting to application page...");
    // yaha apna affiliate link lagao
    // window.location.href = "https://your-affiliate-link.com";
  }

  function toggleFAQ(element) {
    let answer = element.nextElementSibling;
    if (answer.style.display === "block") {
      answer.style.display = "none";
    } else {
      answer.style.display = "block";
    }
  }
</script>

</body>
</html>
