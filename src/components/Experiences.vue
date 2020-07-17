<template>
  <section class="resume-section" id="experience">
    <h1 class="mb-5">Expériences</h1>
    <div
      class="resume-item d-flex flex-column flex-md-row justify-content-between mb-5"
    >
      <div class="resume-content">
        <p>
          Young by experience but still motivated, always ready to learn !
        </p>

        <p>
          Développeur junior fullstack, je fais la maintenance des sites et
          conçois de nouveaux sites. En occurence avec de diverses technologies
          comme (Vue basée sur javascript node js) en frontend. Je mets en place
          un API pour se connecter et récupérer des données en temps réelles.
          Une bonne connaissance de la gestion des bases de données.
        </p>
      </div>
    </div>
    <div>
      <b-table striped hover :items="items" :fields="fields"></b-table>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      // Note 'isActive' is left out and will not appear in the rendered table
      fields: [
        {
          key: "Expériences",
          sortable: true,
        },
        {
          key: "Date_début",
          sortable: false,
        },
        {
          key: "date",
          label: "Date de fin",
          sortable: true,
          // Variant applies to the whole column, including the header and footer
          variant: "",
        },
      ],

      items: [
        {
          isActive: true,
          date: `à nos jours `,
          Expériences:
            "Freelance web developpeur fullstack sur codeur.com et MALT",
          Date_début: "2020",
        },
        {
          isActive: false,
          date: "à nos jours",
          Expériences: " Freelance web developpeur PHP sur codeur.com et MALT",
          Date_début: "2018",
        },
        {
          isActive: true,
          date: `"05-04-2020" `,
          Expériences:
            " Hackaton Stay The F*** At Home Hackathon organisé par Microsoft Belgique",
          Date_début: "03-04-2020",
        },
        {
          isActive: false,
          date: "08/2020",
          Expériences:
            " Hack in The Wood deuxième édition organisé par Microsoft Belgique",
          Date_début: "08/2020",
        },
        {
          isActive: true,
          date: "11/2017",
          Expériences:
            "Comédien - Acteur : Théâtre le Moderne de Liège avec la compagnie Alternative-Théâtre",
          Date_début: "Novembre/2016",
        },
        {
          isActive: false,
          date: "Juin/2015",
          Expériences:
            "Présentation , Pladoyer et Fundraising au sein de la société Suisse-Casino à Zurcih; dans le cadre du projet de développement communautaire pour la construction d'une ferme agricole dans la localité de Donamadé (préfecture de Yoto au Togo)",
          Date_début: "Juillet/2015",
        },
        {
          isActive: true,
          date: "Juillet/2012",
          Expériences:
            "Contrat CDI, Engagé comme principal chargé de la mobilisation des ressources de l'ONG Espace Fraternité. J'avais pour mission d'organiser la mobilisation des enfants bénéficiaires, du programmes de réinsertion socio-profetionnelles, pris en charge par le RAO (Réseau Afrique de l'Ouest pour la Protection des enfants) ",
          Date_début: "Septembre/2015",
        },
        {
          isActive: false,
          date: "01-09-2013",
          Expériences:
            "Mission à l'étranger: Présentation du projet de construction du centre d'accueil de l'ONG Espace Fraternité pour des enfants vulnérables au sein de l'ONG SSI-Suisse à Genève ",
          Date_début: "01-09-2013",
        },
        {
          isActive: true,
          date: "Mai/2013",
          Expériences:
            "Contrat bénévole: travail avec les enfants de rue de Lomé pour les amener à une éventuelle réinsertion socio-profetionnelle ",
          Date_début: "Février/2012",
        },
        {
          isActive: false,
          date: "Septembre/2009",
          Expériences:
            "Après mon baccalauréat j'ai travaillé dans l'entreprise familliale de mon père (Etablissement International de Construction Métallique Générale du Toogo) je m'occupais des tâches administratives (devis-factures et paie des ouvriers) ",
          Date_début: "Février/2012",
        },
      ],
    };
  },
};
</script>
