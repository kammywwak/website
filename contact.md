---
layout: page
title: Contact
permalink: /contact/
---

Feel free to reach out to me using the form below:

<form action="https://formspree.io/f/xpwqrvng" method="POST">
  <div class="form-group">
    <label for="name">Name</label>
    <input type="text" name="name" required>
  </div>
  <div class="form-group">
    <label for="email">Email</label>
    <input type="email" name="email" required>
  </div>
  <div class="form-group">
    <label for="message">Message</label>
    <textarea name="message" required></textarea>
  </div>
  <button type="submit">Send Message</button>
</form>

<style>
.form-group {
  margin-bottom: 15px;
}
.form-group label {
  display: block;
  margin-bottom: 5px;
}
.form-group input,
.form-group textarea {
  width: 100%;
  padding: 10px;
  border: 1px solid #ddd;
  border-radius: 4px;
}
.form-group textarea {
  height: 150px;
}
button {
  background-color: #000;
  color: white;
  padding: 10px 20px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}
button:hover {
  background-color: #333;
}
</style>