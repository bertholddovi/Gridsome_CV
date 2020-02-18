<template>
  <Layout>
    <div class="container-fluid p-0">
      <About />
      <hr class="m-0" />
      <Experiences />
      <hr class="m-0" />
      <Educations />
      <hr class="m-0" />
      <Skills />
      <hr class="m-0" />
      <Interests />
      <hr class="m-0" />
      <Languages />
       <hr class="m-0" />
      <Contacts />
       <hr class="m-0" />
      <Informations />
      
    </div>
  </Layout>
</template>


<script>
import About from "../components/About";
import Contacts from "../components/Contacts";
import Experiences from "../components/Experiences";
import Educations from "../components/Educations";
import Skills from "../components/Skills";
import Interests from "../components/Interests";
import Languages from "../components/Languages";
import Informations from "../components/Informations";

export default {
  components: {
    About,
    Experiences,
    Educations,
    Skills,
    Languages,
    Informations,
    Interests,
    Contacts
  },
  metaInfo: {
    title: "Gridsome CV"
  }
};
</script>
