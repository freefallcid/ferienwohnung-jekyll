---
layout: page
title: "Kontakt"
permalink: /kontakt/
subtitle: 
---
<!-- Short and succinct messages [via Twitter](https://twitter.com/mmistakes) are my preferred contact point. I can also be found on several other social networks if you want to reach out and [follow me]({{ site.url }}/support/#follow-me-on-social-media) there.

Before asking questions related to creating art on iPad or using Jekyll be sure to check the [Frequently Asked Questions section](/faqs/) --- there's a good chance I've already answered them. For anything longer please fill out the form below and I'll get back to you by email.

If you have a product, service, app, or other opportunity that you feel is a good fit for my site let me know. While I can't promise anything, there's a good chance I'll write about it if I think there's value for my readers.

<script>{\% include wufoo.js %}</script> -->

<form id="contact" name="contact" accept-charset="UTF-8" autocomplete="off" enctype="multipart/form-data" method="post" novalidate action="https://dominicreich.com/cgi-bin/contact.pl">
  <table border="0" cellpadding="2" cellspacing="2">
    <tr>
      <td>
        <div class="form-group">
          <label id="lbl_message" for="message"><strong>Nachricht</strong><span id="req_1" class="req">*</span></label>
          <textarea id="message" name="message" spellcheck="true" rows="10" cols="50" required></textarea>
        </div>
      </td>
    </tr>
    <tr>
      <td>
        <div class="form-group">
          <label id="lbl_subject" for="subject"><strong>Betreff</strong></label>
          <input id="subject" name="subject" spellcheck="true" maxlength="255">
        </div>
      </td>
    </tr>
    <tr>
      <td>
        <div class="form-group">
          <label id="lbl_name" for="realname"><strong>Name</strong><!-- <span id="req_2" class="req">*</span> --></label>
          <input id="realname" name="realname" type="text" maxlength="255">
        </div>
      </td>
    </tr>
    <tr>
      <td>
        <div class="form-group">
          <label id="lbl_email" for="email"><strong>Email</strong><span id="req_3" class="req">*</span> <small>(wird **nicht** veröffentlicht)</small></label>
          <input id="email" name="email" type="email" spellcheck="false" maxlength="255" required>
        </div>
      </td>
    </tr>
    <tr>
      <td>
        <div class="form-group">
          <label id="lbl_heard_about_your_site" for="heard_about_your_site"><strong>How&rsquo;d you hear about my website?</strong></label>
          <input id="heard_about_your_site" name="heard_about_your_site" type="text" maxlength="255">
        </div>
      </td>
    </tr>
    <tr>
      <td>
        <div class="form-group">
          <button id="saveForm" name="saveForm" class="btn" type="submit">Nachricht senden</button>
          <button id="resetForm" name="resetForm" class="btn" type="reset">Zurücksetzen</button>
        </div>
      </td>
    </tr>
    <tr>
      <td>
        <div class="form-group hidden">
          <label for="comment">Dieses Eingabefeld nicht ausfüllen!</label>
          <textarea name="comment" id="comment" rows="1" cols="1"></textarea>
          <!-- <input type="hidden" id="idstamp" name="idstamp" value="DXSyHZyBYpNZI+88LvVOKO8dSfd/5lyIeCQAXFVxeJY="> -->

          <input type="hidden" name="env_report" value="REMOTE_HOST,REMOTE_ADDR,REMOTE_USER,HTTP_USER_AGENT">
          <input type="hidden" name="recipient" value="contact-ferienwohnung@dore.pw">
          <input type="hidden" name="subject" value="[noblock] - [Ferienwohnung] Kontaktformular">
          <!-- <input type="hidden" name="email" value="webmail@dore.pw"> -->
          <input type="hidden" name="required" value="email,message">
          <!-- <input type="hidden" name="redirect" value="/thanks.html"> -->
          <!-- <input type="hidden" name="print_config" value="name,email,subject,message,comment"> -->
          <input type="hidden" name="print_blank_fields" value="0">
        </div>
      </td>
    </tr>
  </table>
</form>
