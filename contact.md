---
layout: page
title: Contact
description: "Contact us for design and order requests and price quotes."
permalink: /contact/
---
<form id="contactform" method="POST">
    <input type="text" name="name" placeholder="Your name">
    <input type="email" name="_replyto" placeholder="Your email">
    <input type="hidden" name="_subject" value="Website contact" />
    <!-- This is where the widget will be. Don't forget the name attribute! -->
    <input type="hidden" role="uploadcare-uploader" name="my_file" />
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