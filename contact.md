---
layout: page
title: Contact me
permalink: /contact/
description: Get in touch with me
custom_css: contact
---

## Hello There! 👋 Do you want to contact me?

Fill in this form and I will reach you as soon as possible.

<form class="contact-form" method="post" action="/contact/">
  <div class="form-row">
    <label for="contact-email">Your email:</label>
    <input
      type="email"
      id="contact-email"
      name="email"
      placeholder="you@example.com"
      required
    >
  </div>

  <div class="form-row">
    <label for="contact-message">Your message:</label>
    <textarea
      id="contact-message"
      name="message"
      rows="6"
      placeholder="Write your message here..."
      required
    ></textarea>
  </div>

  <div class="form-actions">
    <button type="submit">Send</button>
  </div>
</form>