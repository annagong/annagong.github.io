---
layout: page
title: contact
permalink: /contact/
---
Fill out the form to get in touch about commisions  :)

<form action="https://formspree.io/agong1@hwemail.com"
      method="POST">
    <input type="email" name="_replyto" placeholder="Your email"/>
    <textarea name="message" placeholder="Your message"></textarea>
    <input type="hidden" name="_subject" value="New submission!" />
    <input type="hidden" name="_next" value="{{ site.baseurl }}/thanks" />
    <button type="submit">Send</button>
</form>
