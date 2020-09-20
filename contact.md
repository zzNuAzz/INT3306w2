---
layout: default
title: Contact
---

<section class="bg-contact">

  <h1 class="text-center text-uppercase text-danger mb-0">Contact me !!!</h1>

  <div class="container pt-5 pb-3 w-100">
    <div class="row">
      {% for contact in site.data.contacts.contact %}
      {% include card.md title=contact.title icon=contact.icon body=contact.body %}
      {% endfor %}
    </div>

    <hr class="my-4">

    <div class="container">
      <div class="row">
        <div class="col-lg-8 col-md-10 mx-auto">
          <ul class="list-inline text-center">
            {% for social in site.data.contacts.social %}
            {% include social.md href=social.href icon=social.icon %}
            {% endfor %}
          </ul>
        </div>
      </div>
    </div>
  </div>
</section>