<template>
  <section class="resume-section" id="skills">
    <div class="w-100">
      <h1 class="mb-5">Compétences</h1>

      <div class="subheading mb-3">Languages de programmations</div>
      <ul class="list-inline dev-icons">
        <li title="Html 5" class="icons list-inline-item">
          <font-awesome :icon="['fab', 'html5']" />
        </li>
        <li title=" CSS " class="icons list-inline-item">
          <font-awesome :icon="['fab', 'css3-alt']" />
        </li>
      </ul>
      <ul>
        <li>Html</li>
        <li>Css</li>
      </ul>

      <div class="subheading mb-3">Applications et autres</div>
      <ul class="list-inline dev-icons">
        <li title=" Github " class="icons list-inline-item">
          <font-awesome :icon="['fab', 'github']" />
        </li>
        <li title=" Git " class="icons list-inline-item">
          <font-awesome :icon="['fab', 'git']" />
        </li>
      </ul>
    </div>

    <ul>
      <li>Git</li>
      <li>GitHub</li>
    </ul>
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