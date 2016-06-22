---
title: "Contact"
layout: splash
excerpt: "Contact Guillermo Hernandez Jr"
sitemap: false
permalink: /contact/
header:
  overlay_color: "#eb9765"
---
<form id="contactform" method="POST">
    <input type="text" name="name" placeholder="Your name">
    <input type="email" name="_replyto" placeholder="Your email">
    <input type="hidden" name="_subject" value="Website contact" />
    <textarea name="message" placeholder="Your message"></textarea>
    <input type="text" name="_gotcha" style="display:none" />
    <input type="submit" value="Send">
</form>
<script>
    var contactform =  document.getElementById('contactform');
    contactform.setAttribute('action', '//formspree.io/' + 'guillermohernandez' + '@' + 'gmail' + '.' + 'com');
</script>
