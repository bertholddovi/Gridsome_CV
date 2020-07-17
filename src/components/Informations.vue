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
        <div>le 03 Septembre 1986 Lomé - TOGO</div>
      </div>

      <div class="inline-block">
        <div class="social-icons contact-icons">
          <li title="Date de naissance" class="icons">
            <font-awesome :icon="['fa', 'user']" />
          </li>
        </div>
        <div>Marié et père d'une chouette Fille de 20 mois</div>
      </div>

      <div class="inline-block">
        <div class="social-icons contact-icons">
          <li title="CV en Pdf" class="icons">
            <font-awesome :icon="['fa', 'file-pdf']" />
          </li>
        </div>

        <div>
          <div>
            <a href="#" target="_blank"
              >Bientôt disponible</a
            >
          </div>
          <!--   <div>
           <pdf href="~/assets/images/Berthold_DoviCV.pdf" target="_blank"
            >Télécharger le CV au format PDF</pdf
          >
            </div> -->
        </div>
      </div>

      <div class="inline-block">
        <div class="social-icons contact-icons">
          <li title="Lieu d'habitation" class="icons">
            <font-awesome :icon="['fa', 'map-marker']" />
          </li>
        </div>
        <div>Rue Reine - Astrid 20/1D Welekenraedt 4840 - Belgique</div>
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
