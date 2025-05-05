# agnihistory
<section id="join">
  <h2>Join AGNIhistory</h2>
  <form action="https://formspree.io/f/YOUR_CODE_HERE" method="POST">
    <label for="name">Full Name:</label><br>
    <input type="text" id="name" name="name" required><br><br>

    <label for="email">Email Address:</label><br>
    <input type="email" id="email" name="email" required><br><br>

    <label for="message">Why do you want to join?</label><br>
    <textarea id="message" name="message" rows="4" required></textarea><br><br>

    <button type="submit">Join Now</button>
  </form>
</section>
   


form {
  background-color: #1e1e1e;
  padding: 20px;
  border-radius: 10px;
  max-width: 500px;
  margin: 20px auto;
}
input, textarea, button {
  width: 100%;
  padding: 10px;
  margin-top: 5px;
  border: none;
  border-radius: 5px;
}
input, textarea {
  background-color: #2a2a2a;
  color: #f0f0f0;
}
button {
  background-color: #90caf9;
  color: #000;
  font-weight: bold;
  cursor: pointer;
}
button:hover {
  background-color: #64b5f6;
}

