---
layout: page
title: Contact
description: "Fill out the form below to contact us for design or order requests and price quotes."
permalink: /contact/
---
<div class="wrapper">
<p>You can upload an image of your idea to help us design the perfect product for you.</p>

<form id="contactform" method="POST">
    <!-- This is where the widget will be. Don't forget the name attribute! -->
    <input class="uploader" type="hidden" role="uploadcare-uploader" name="my_file" />
    <input type="text" name="name" placeholder="Your name" required>
    <input type="email" name="_replyto" placeholder="Your email" required>
    <input type="hidden" name="_subject" value="Website contact" />
    <textarea name="message" placeholder="Your message"></textarea>
    <input type="text" name="_gotcha" style="display:none" />
    <button class="btn flat-button" type="submit" name="action" style="padding: 10px 15px 10px 10px !important;">
	    <i class="fa fa-paper-plane" aria-hidden="true"></i>
	    Send
	  </button>
    <input type="hidden" name="_next" value="/thanks" />
</form>
</div>
<script type="text/javascript">
    $('#contact').addClass('active');
</script>
<script>
    var contactform =  document.getElementById('contactform');
    contactform.setAttribute('action', '//formspree.io/' + 'shelley@sandrcreations.com');//l3rittny.l' + '@' + 'gmail' + '.' + 'com');
</script>
