---
title: Contact
layout: default
permalink: /contact/
---

# Contact Us

<form id="contact-form" method="post">
  <label for="form-name" class="form-label">Name</label>
  <input id="form-name" class="form-control" type="text" placeholder="Enter your name">

  <label for="form-email" class="form-label mt-3">Email</label>
  <input id="form-email" class="form-control" type="email" placeholder="Enter your email">

  <label for="form-message" class="form-label mt-3">Message</label>
  <textarea id="form-message" class="form-control" rows="10" placeholder="Enter your message"></textarea>

  <button type="submit" class="btn btn-primary mb-3 mt-3" onClick="invokeAWSAPI(event)">Send</button>

</form>
