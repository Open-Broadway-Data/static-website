---
title: "Contact"
permalink: about/contact.html
layout: page
menus:
  about:
    icon: <i class="fas fa-phone"></i>
    identifier: contact
    is_child: true
    skip_title: false
    weight: 10
---

<h1>Contact Us <i class="fas fa-phone"></i></h1>
<div id="form-explanation">
We'd love to hear from you. Fill out the following form and we will get back to you shortly.
</div>

<form name="gform" id="gform" enctype="text/plain" action="https://docs.google.com/forms/d/e/1FAIpQLSdxLdwHsocfLppIATAKrcbtgUJsVcomDxuIj2zEK7FAXt2K5A/formResponse?" target="hidden_iframe" onsubmit="submitted=true;">
  <ul>
    <li id="name">
      Name:<br>
      <input type="text" name="entry.124705125" id="entry.124705125">
    </li>
    <li id="email-address">
      Email:<br>
      <input type="email" name="entry.2036870632" id="entry.2036870632">
    </li>
    <li id="message">
      Message:<br>
      <textarea name="entry.1215537375" id="entry.1215537375"></textarea>
    </li>
    <li id="submit">
      <input type="submit" value="Submit">
    </li>
  </ul>
</form>

<script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js"></script>
<script type="text/javascript">var submitted=false;</script>
<script type="text/javascript">
  $("#gform").on("submit", function(e) {
    $('#gform *').fadeOut(1_000);

    // get all the inputs into a dictionary.
    var $inputs = $('#gform :input');

    // not sure if you wanted this, but I thought I'd add it.
    // get an associative array of just the values.
    var values = {};
    $inputs.each(function() {
        values[this.parentElement.id] = $(this).val();
    });
    console.log(values);
    $('#form-explanation').html('Thank you for your submission ' + values['name'] +'.').fadeIn(500);
    $('#form-explanation').css({"color": "var(--obd-green, #00AE7A)", "font-weight": "bold"});

    });
</script>

<iframe name="hidden_iframe" id="hidden_iframe" style="display:none;" onload="if(submitted) {}"></iframe>
