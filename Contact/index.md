---
layout: layouts/post.njk
title: Get In Touch
templateClass: tmpl-post
eleventyNavigation:
  key: Contact
  order: 4
---

<form name="contact" method="POST" data-netlify="true">
    <p>
        <label>Your Name: <input type="text" id="name" name="name" /></label>   
    </p>
    <p>
        <label>Your Email: <input type="email" id="email" name="email" /></label>
    </p>
    <p>
        <input type="radio"
        <option value="leader">Leader</option><br />
        <input type="radio"
        <option value="follower">Follower</option>
        </select></label>
    </p>
    <p>
        <label>Message: <textarea name="message"></textarea></label>
    </p>
    <p>
        <button class="form_submit" type="submit">Send</button>
    </p>
</form>