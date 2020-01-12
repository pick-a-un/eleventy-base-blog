---
layout: layouts/post.njk
title: About Me
templateClass: tmpl-post
eleventyNavigation:
  key: About Me
  order: 3
---

<p>I am a person that writes stuff. Sometime that stuff is fluff.</p>
<strong>Want to get it <span class="grab">touch</span> with me?</strong>
<p>Just drop me some lines</p>
<form name="contact" method="POST" data-netlify="true">
<img src='/img/logo-ynotyout-solid.svg' alt='ynotyout-logo'>
<h2>Contact Form</h2>
  <p>
    <label>Your Name: <input type="text" name="name" /></label>   
  </p>
  <p>
    <label>Your Email: <input type="email" name="email" /></label>
  </p>
  <p>
    <label>Your Role: <div class="select"><select name="role[]" id="slct">
      <option selected disabled>Choose an option</option>
      <option value="follower">Follower</option>
      <option value="leader">Leader</option>
      <option value="folder">Folder</option>
      <option value="lowerlea">lower Lea</option>
      <option value="none">None of the above!</option>
    </select>
   </label>
  </div>
  </p>
  <p class="vh">
    <label>Your enquiry<input name="bot-field" /></label>
  </p>
  <p>
    <label>Message: <textarea name="message"></textarea></label>
  </p>
  <input type="file"></input>
  <p>
    <button type="submit" value="submit the form">Send</button>
  </p>
</form>

