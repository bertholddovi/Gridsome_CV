<template>
  <section class="resume-section middle" id="contact">
    <div class="w-100">
      <h1 class="mb-5">Contact</h1>

      <div class="inline-block">
        <div class="social-icons contact-icons">
          <li title="Numéro de téléphone" class="icons">
            <font-awesome :icon="['fa', 'phone']" />
          </li>
        </div>
        <div>PHONE NUMBER</div>
      </div>
      <div class="inline-block">
        <div class="social-icons contact-icons">
          <li title="Adresse Gmail" class="icons">
            <font-awesome :icon="['fa', 'envelope']" />
          </li>
        </div>
        <div>EMAIL</div>
      </div>
      <div class="inline-block">
        <div class="social-icons contact-icons">
          <a title="Profile LinkedIn" href="https://linkedin.com/in/" target="_blank">
            <font-awesome :icon="['fab', 'linkedin']" />
          </a>
        </div>
        <div>
          <a
            href="LINKEDINLINK"
          >LINKEDIN LINK</a>
        </div>
      </div>
      <div class="inline-block">
        <div class="social-icons contact-icons">
          <a title="Profile Github" href="https://github.com/profile" target="_blank">
            <font-awesome :icon="['fab', 'github']" />
          </a>
        </div>
        <div>
          <a href="https://github.com/NAME">https://github.com/NAME</a>
        </div>
      </div>
    </div>
  </section>
</template>