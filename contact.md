---
layout: page
title: Contact
description: "Contact us for design and order requests and price quotes."
permalink: /contact/
---

<p>You can upload an image of your idea to help us design the perfect product for you.</p>

<form id="contactform" method="POST">
    <!-- This is where the widget will be. Don't forget the name attribute! -->
    <input class="uploader" type="hidden" role="uploadcare-uploader" name="my_file" />
    <input type="text" name="name" placeholder="Your name" required>
    <input type="email" name="_replyto" placeholder="Your email" required>
    <input type="hidden" name="_subject" value="Website contact" />
    <textarea name="message" placeholder="Your message"></textarea>
    <input type="text" name="_gotcha" style="display:none" />
    <button class="btn flat-button" type="submit" name="action">
	    <i class="fa fa-paper-plane" aria-hidden="true"></i>
	    Send
	  </button>
    <input type="hidden" name="_next" value="/thanks" />
</form>
<script>
    var contactform =  document.getElementById('contactform');
    contactform.setAttribute('action', '//formspree.io/' + 'l3rittny.l' + '@' + 'gmail' + '.' + 'com');
</script>