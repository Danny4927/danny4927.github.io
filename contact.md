---
layout: page
title: "Contact"
description: "Fragen? Dann hier melden!"
header-img: "../img/contact-bg.jpg"
---

<p>Kritik? Wünsche? Anregungen? Lasst es mich wissen: Hier das Kontaktformular um mich zu erreichen. </p>
    
<form name="sentMessage" id="contactForm" action="https://formspree.io/info@danielknoell.de" method="POST" novalidate>
    <div class="row control-group">
        <div class="form-group col-xs-12 floating-label-form-group controls">
            <label>Name</label>
            <input type="text" class="form-control" placeholder="Name" name="name" id="name" required data-validation-required-message="Please enter your name.">
            <p class="help-block text-danger"></p>
        </div>
    </div>
    <div class="row control-group">
        <div class="form-group col-xs-12 floating-label-form-group controls">
            <label>Email Address</label>
            <input type="email" class="form-control" placeholder="Email-Addresse" name="_replyto" id="email" required data-validation-required-message="Please enter your email address.">
            <p class="help-block text-danger"></p>
        </div>
    </div>
    <div class="row control-group">
        <div class="form-group col-xs-12 floating-label-form-group controls">
            <label>Message</label>
            <textarea rows="5" name="body" class="form-control" placeholder="Deine Nachricht" id="message" required data-validation-required-message="Please enter a message."></textarea>
            <p class="help-block text-danger"></p>
        </div>
    </div>
    <br>
    <div id="success"></div>
    <div class="row">
        <div class="form-group col-xs-12">
         
            <input type="submit" class="btn btn-default" value="Send">
        </div>
    </div>
</form>


