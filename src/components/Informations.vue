<template>
  <section class="resume-section middle" id="informations">
    <div class="w-100">
      <h1 class="mb-5">Informations</h1>

      <div class="inline-block">
        <div class="social-icons contact-icons">
          <li title="Permis B et voiture" class="icons">
            <font-awesome :icon="['fa', 'car']" />
          </li>
        </div>
        <div>Permis B et voiture</div>
      </div>

      <div class="inline-block">
        <div class="social-icons contact-icons">
          <li title="Date de naissance" class="icons">
            <font-awesome :icon="['fa', 'birthday-cake']" />
          </li>
        </div>
        <div>DATE OF BIRTH</div>
      </div>

      <div class="inline-block">
        <div class="social-icons contact-icons">
          <li title="Lieu d'habitation" class="icons">
            <font-awesome :icon="['fa', 'map-marker']" />
          </li>
        </div>
        <div>WHERE YOU LIVE</div>
      </div>
    </div>
  </section>
</template>

<style scoped lang="scss">
.contact-icons {
  margin: 3px;
}

.inline-block {
  display: flex;
  align-items: center;
}
</style>