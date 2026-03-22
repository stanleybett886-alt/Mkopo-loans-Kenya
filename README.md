<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mkopo Loans Kenya</title>

<style>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  background: #f4f6f9;
}

header {
  background: #0a7f3f;
  color: white;
  padding: 20px;
  text-align: center;
}

.hero {
  padding: 40px;
  text-align: center;
}

.hero h1 {
  color: #0a7f3f;
}

.btn {
  background: #0a7f3f;
  color: white;
  padding: 12px 20px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

.section {
  padding: 30px;
}

.cards {
  display: flex;
  flex-wrap: wrap;
  gap: 15px;
}

.card {
  background: white;
  padding: 20px;
  flex: 1 1 200px;
  border-radius: 10px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

form {
  background: white;
  padding: 20px;
  border-radius: 10px;
  max-width: 400px;
  margin: auto;
}

input, select {
  width: 100%;
  padding: 10px;
  margin: 10px 0;
}

footer {
  background: #0a7f3f;
  color: white;
  text-align: center;
  padding: 15px;
}
</style>
</head>

<body>

<header>
  <h1>Mkopo Loans Kenya</h1>
  <p>Fast & Reliable Loans Anytime</p>
</header>

<section class="hero">
  <h1>Get Instant Loans Today 💰</h1>
  <p>Quick approval | Flexible repayment | Secure process</p>
  <button class="btn" onclick="scrollToForm()">Apply Now</button>
</section>

<section class="section">
  <h2>Loan Services</h2>
  <div class="cards">
    <div class="card">Business Loans</div>
    <div class="card">School Fees Loans</div>
    <div class="card">Emergency Loans</div>
    <div class="card">Personal Loans</div>
  </div>
</section>

<section class="section" id="formSection">
  <h2>Apply for a Loan</h2>

  <form onsubmit="submitForm(event)">
    <input type="text" placeholder="Full Name" required>
    <input type="tel" placeholder="Phone Number" required>

    <select required>
      <option value="">Select Loan Type</option>
      <option>Business Loan</option>
      <option>School Fees Loan</option>
      <option>Emergency Loan</option>
      <option>Personal Loan</option>
    </select>

    <input type="number" placeholder="Amount (KSH)" required>

    <button class="btn" type="submit">Submit Application</button>
  </form>
</section>

<section class="section">
  <h2>Contact Us</h2>
  <p>📞 0792996609</p>
  <p>📧 infomkopoloanskenya@gmail.com</p>
</section>

<footer>
  <p>© 2026 Mkopo Loans Kenya. All rights reserved.</p>
</footer>

<script>
function scrollToForm() {
  document.getElementById("formSection").scrollIntoView({ behavior: "smooth" });
}

function submitForm(e) {
  e.preventDefault();
  alert("Your loan application has been submitted successfully! We will contact you shortly.");
}
</script>

</body>
</html>
