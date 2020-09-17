---
layout: default
title: Contact
---

<section class="bg-contact">

  <h1 class="text-center text-uppercase text-primary mb-0">Contact me !!!</h1>

  <div class="container pt-5 pb-3 w-100">
    <div class="row">
      {% for contact in site.data.contacts %}
      {% include card.md title=contact.title icon=contact.icon body=contact.body %}
      {% endfor %}
    </div>

    <hr class="my-4">

    <div class="container">
      <div class="row">
        <div class="col-lg-8 col-md-10 mx-auto">
          <ul class="list-inline text-center">
            <li class="list-inline-item">
              <a href="mailto:tuananh2106a2@gmail.com">
                <span class="fa-stack fa-lg h1">
                  <i class="fas fa-circle fa-stack-2x"></i>
                  <i class="far fa-envelope fa-stack-1x fa-inverse"></i>
                </span>
              </a>
            </li>
            <li class="list-inline-item">
              <a href="https://www.facebook.com/SoNguyenTo216">
                <span class="fa-stack fa-lg h1">
                  <i class="fas fa-circle fa-stack-2x"></i>
                  <i class="fab fa-facebook-f fa-stack-1x fa-inverse"></i>
                </span>
              </a>
            </li>
            <li class="list-inline-item">
              <a href="https://github.com/zzNuAzz">
                <span class="fa-stack fa-lg h1">
                  <i class="fas fa-circle fa-stack-2x"></i>
                  <i class="fab fa-github fa-stack-1x fa-inverse"></i>
                </span>
              </a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</section>