<template>
  <section class="resume-section" id="skills">
    <div class="w-100">
      <h1 class="mb-5">Competences</h1>

      <div class="subheading mb-3">Languages de programmations</div>
      <ul class="list-inline dev-icons">
        <li title="Html 5" class="icons list-inline-item">
          <font-awesome :icon="['fab', 'html5']" />
        </li>
        <li title=" CSS " class="icons list-inline-item">
          <font-awesome :icon="['fab', 'css3-alt']" />
        </li>
        <li title=" Javascript " class="icons list-inline-item">
          <font-awesome :icon="['fab', 'js']" />
        </li>
        <li title=" Php " class="icons list-inline-item">
          <font-awesome :icon="['fab', 'php']" />
        </li>
        
      </ul>
      

      <div class="subheading mb-3">Frameworks - Libraries - CMS</div>
      <ul class="list-inline dev-icons">
        <li title=" Symfony " class="icons list-inline-item">
          <font-awesome :icon="['fab', 'symfony']" />
        </li>
        <li title=" Laravel " class="icons list-inline-item">
          <font-awesome :icon="['fab', 'laravel']" />
        </li>
         <li title=" Bootsrap " class="icons list-inline-item">
          <font-awesome :icon="['fab', 'bootstrap']" />
        </li>
        <li title=" NodeJs " class="icons list-inline-item">
          <font-awesome :icon="['fab', 'npm']" />
        </li>
        <li title=" Sass " class="icons list-inline-item">
          <font-awesome :icon="['fab', 'sass']" />
        </li>
         <li title=" ReactJs " class="icons list-inline-item">
          <font-awesome :icon="['fab', 'react']" />
        </li>
         <li title=" AngularJs " class="icons list-inline-item">
          <font-awesome :icon="['fab', 'angular']" />
        </li>
         <li title=" VueJs " class="icons list-inline-item">
          <font-awesome :icon="['fab', 'vuejs']" />
        </li>
         <li title="Wordpress" class="icons list-inline-item">
          <font-awesome :icon="['fab', 'wordpress']" />
        </li>
      </ul>

      <div class="subheading mb-3">Applications et Logiclies</div>
      <ul class="list-inline dev-icons">
        <li title=" Github " class="icons list-inline-item">
          <font-awesome :icon="['fab', 'github']" />
        </li>
        <li title=" Docker " class="icons list-inline-item">
          <font-awesome :icon="['fab', 'docker']" />
        </li>
        <li title=" Git " class="icons list-inline-item">
          <font-awesome :icon="['fab', 'git']" />
        </li>
        <li title=" Discord " class="icons list-inline-item">
          <font-awesome :icon="['fab', 'discord']" />
        </li>
        
      </ul>
    </div>
  </section>
</template>

<style lang="scss">
.icons {
  display: inline-block;
  height: 3.5rem;
  width: 3.5rem;
  background-color: #007bff;
  color: white !important;
  border-radius: 100%;
  text-align: center;
  font-size: 2.5rem;
  line-height: 3.5rem;
  margin-right: 0.5rem;
}
</style>
