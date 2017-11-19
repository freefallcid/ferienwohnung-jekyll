---
layout: page
title: "Kontakt"
permalink: /kontakt/
subtitle: 
---

Sie haben eine Frage oder wollen direkt Ihren Urlaub buchen?[^1] Schreiben Sie uns Ihr Anliegen per Email.

<form id="contact" name="contact" accept-charset="UTF-8" autocomplete="off" enctype="multipart/form-data" method="post" novalidate action="https://dominicreich.com/cgi-bin/contact.pl">
  <div class="form-group">
    <label id="lbl_name" for="realname"><strong>Name</strong><span id="req_2" class="req">*</span></label>
    <input id="realname" name="realname" type="text" maxlength="255">
  </div>
  <div class="form-group">
    <label id="lbl_email" for="email"><strong>Email</strong><span id="req_3" class="req">*</span><!--  <small>(wird nicht veröffentlicht)</small> --></label>
    <input id="email" name="email" type="email" spellcheck="false" maxlength="255" required>
  </div>
  <div class="form-group">
    <label id="lbl_info" class="box-note"><em>Bitte geben Sie eine gültige Email Adresse an, damit wir Ihnen auch antworten können!</em></label>
  </div>
  <div class="form-group">
    <label id="lbl_message" for="message"><strong>Nachricht</strong><span id="req_1" class="req">*</span></label>
    <textarea id="message" name="message" spellcheck="true" rows="10" cols="50" required></textarea>
  </div>
<!--   <div class="form-group">
    <label id="lbl_subject" for="subject"><strong>Betreff</strong></label>
    <input id="subject" name="subject" spellcheck="true" maxlength="255">
  </div> -->
  <div class="form-group">
    <button id="saveForm" name="saveForm" class="btn" type="submit">Nachricht senden</button>
    <button id="resetForm" name="resetForm" class="btn" type="reset">Zurücksetzen</button>
  </div>
  <div class="form-group hidden">
    <label for="comment">Dieses Eingabefeld nicht ausfüllen!</label>
    <textarea name="comment" id="comment" rows="1" cols="1"></textarea>
    <!-- <input type="hidden" id="idstamp" name="idstamp" value="DXSyHZyBYpNZI+88LvVOKO8dSfd/5lyIeCQAXFVxeJY="> -->

    <input type="hidden" name="env_report" value="REMOTE_HOST,REMOTE_ADDR,REMOTE_USER,HTTP_USER_AGENT">
    <input type="hidden" name="recipient" value="contact-ferienwohnung@dore.pw">
    <input type="hidden" name="subject" value="[noblock] - [Ferienwohnung] Kontaktformular">
    <!-- <input type="hidden" name="email" value="webmail@dore.pw"> -->
    <input type="hidden" name="required" value="email,realname,message">
    <!-- <input type="hidden" name="redirect" value="/thanks.html"> -->
    <!-- <input type="hidden" name="print_config" value="name,email,subject,message,comment"> -->
    <input type="hidden" name="print_blank_fields" value="0">
  </div>
</form>

[^1]: Wenn Sie Ihren Urlaub bei uns buchen möchten, sollte Ihre Email bereits Ihren **vollständigen Namen**, Ihre **Adresse** sowie Ihre **Staatsbürgerschaft** enthalten. Weiters sollten die **Daten der gewünschten An- bzw, Abreise** bekannt sein als auch die **Anzahl der Erwachsenen** und **Kinder** -- unsere Ferienwohnung ist geeignet für maximal 2 Erwachsene und 2 Kinder oder 3 Erwachsene.
