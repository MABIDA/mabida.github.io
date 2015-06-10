---
layout: page
title: Contact MABIDA
h1color: fff
h1bg: 1B374B
permalink: /contact/
published: true
bodyclass: contact
---

<form action="https://getsimpleform.com/messages?form_api_token={{ site.simpleform_api_token }}" method="post">
  <!-- the redirect_to is optional, the form will redirect to the referrer on submission -->
  <input type='hidden' name='redirect_to' value='{{ site.simpleform_redirect }}' />
  <!-- all your input fields here.... -->




      <span class="input">
                  <input type="text" name="name" value="" class="input__field">
                  <label class="input__label">
                  <span class="input__label-content">Your name</span>
                  </label>
      </span>


      <span class="input">
                  <input type="text" name="email" value="" class="input__field">
                  <label class="input__label">
                  <span class="input__label-content">Your email address</span>
                  </label>
      </span>

      <textarea name="message" placeholder="Your message..."></textarea>



    <input type='submit' value='Send' class="btn btn-1 btn-1a"/>

</form>
