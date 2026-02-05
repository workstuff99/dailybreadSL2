---
layout: page
title: Prayer Request
---

<form name="prayer" method="POST" data-netlify="true">
  <p>
    <label>Name<br>
      <input type="text" name="name" required>
    </label>
  </p>

  <p>
    <label>Email (optional)<br>
      <input type="email" name="email">
    </label>
  </p>

  <p>
    <label>Prayer Request<br>
      <textarea name="request" rows="5" required></textarea>
    </label>
  </p>

  <p>
    <button type="submit">Submit</button>
  </p>
</form>
