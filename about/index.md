---
layout: layouts/post.njk
title: About Me
templateClass: tmpl-post
eleventyNavigation:
  key: About Me
  order: 3
---

<p>I am a person that writes stuff. Sometime that stuff is fluff.</p>

<form name="contact" method="POST" data-netlify="true">
  <p>
    <label>Your Name: <input type="text" name="name" /></label>   
  </p>
  <p>
    <label>Your Email: <input type="email" name="email" /></label>
  </p>
  <p>
    <label>Your Role: <select name="role[]" multiple>
      <option value="leader">Leader</option>
      <option value="follower">Follower</option>
      <option value="folder">Folder</option>
    </select></label>
  </p>
  <p class="vh">
    <label>Your enquiry<input name="bot-field" /></label>
  </p>
  <p>
    <label>Message: <textarea name="message"></textarea></label>
  </p>
  <input type="file"></input>
  <p>
    <button type="submit">Send</button>
  </p>
</form>

