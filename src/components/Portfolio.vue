<template>
  <section class="resume-section middle" id="portfolio">
    <div>
      <h1>Portfolio</h1>
      <div>
        <b-card-group deck>
          <b-card
            header="CV with Gridsome"
            header-tag="header"
            footer="Gridsome-vue.js, Bootstrap-vue"
            footer-tag="footer"
            title="Curriculum Vitae"
          >
            <b-card-text
              >CV - Portfolio réalisé sous Gridsome Vue-js "One Page Responsive"</b-card-text
            >
            <b-button href="#" variant="primary">Link Netlify</b-button> <br />
            <br />
            <b-button
              href="https://github.com/bertholddovi/Gridsome_CV"
              target="_blank"
              variant="primary"
              >Link Code github</b-button
            >
          </b-card>

          <b-card title="Api" header-tag="header" footer-tag="footer">
            <template v-slot:header>
              <h6 class="mb-0">Api Restfull</h6>
            </template>
            <b-card-text
              >Api Restfull construite avec node js & Mongodb</b-card-text
            >
            <b-button
              href="https://github.com/bertholddovi/api-bertholddovi-node-js"
              variant="primary"
              >Link Github</b-button
            >
            <template v-slot:footer>
              <em>Node js, MongoDb</em>
            </template>
          </b-card>
        </b-card-group>
      </div>
      <br />
      <div>
        <b-card-group deck>
          <b-card
            header="Pomodoro"
            header-tag="header"
            footer="React js, javascript, typescript"
            footer-tag="footer"
            title="Pomodoro"
          >
            <b-card-text>Pomodoro réalisé avec react js</b-card-text>
            <b-button
              href="https://bertholddovi-react-pomodoro.netlify.app"
              target="_blank"
              variant="primary"
              >Link Netlify
            </b-button>
            <br />
            <br />
            <b-button
              href="https://github.com/bertholddovi/react_pomodoro"
              target="_blank"
              variant="primary"
              >Link Code github</b-button
            >
          </b-card>

          <b-card title="Forum" header-tag="header" footer-tag="footer">
            <template v-slot:header>
              <h6 class="mb-0">Forum</h6>
            </template>
            <b-card-text
              >Forum de discussion réalisé avec php et MySQl</b-card-text
            >
            <b-button
              href="https://becode-person.herokuapp.com/pages/connexion.php"
              target="_blank"
              variant="primary"
              >Link Heroku</b-button
            ><br />
            <br />
            <b-button
              href="https://github.com/faking-it/forum_person/tree/berthold_forum_person"
              target="_blank"
              variant="primary"
              >Link Code github</b-button
            >
            <template v-slot:footer>
              <em>Docker-Php, javascript, MySql</em>
            </template>
          </b-card>
        </b-card-group>
      </div>
      <br />
      <div>
        <b-card-group deck>
          <b-card
            header="Carte de visite"
            header-tag="header"
            footer="html, Css, Animation 3D"
            footer-tag="footer"
            title="Carte de Visite"
          >
            <b-card-text
              >Jolie petite carte de visite développeur web</b-card-text
            >
            <b-button
              href="https://bertholddovi.github.io/VCard/."
              target="_blank"
              variant="primary"
              >Link Pages Github</b-button
            >
            <br />
            <br />
            <b-button
              href="https://github.com/bertholddovi/VCard"
              target="_blank"
              variant="primary"
              >Link Code Github</b-button
            >
          </b-card>

          <b-card title="MERN" header-tag="header" footer-tag="footer">
            <template v-slot:header>
              <h6 class="mb-0">MERN</h6>
            </template>
            <b-card-text
              >Jeu. Gros projet avec Docker et la MERN compagnie, manipulant les
              quelques 6000 arbres de lièges. Malheureusement toujours en
              travaux mais tourne en local
            </b-card-text>
            <b-button
              href="https://crakehall.herokuapp.com/"
              target="_blank"
              variant="primary"
              >Link Heroku</b-button
            >
            <br />
            <br />
            <b-button
              href="https://github.com/bertholddovi/crakehall"
              target="_blank"
              variant="primary"
              >Link Code Github</b-button
            >
            <template v-slot:footer>
              <em
                >Mongodb, Express, React Js,Bulma, Javascript, Typescript, Node js
              </em>
            </template>
          </b-card>
        </b-card-group>
      </div>
      <br />
      <div>
        <b-card-group deck>
          <b-card
            header="Zlatane - Gallerie"
            header-tag="header"
            footer="Angular js, javascript, typescript, Node js , Mongodb"
            footer-tag="footer"
            title="Gallerie photos et vidéos"
          >
            <b-card-text
              >Je tenais à faire une application spécialment dédiée à ma fille
              bien aimée de 20 mois. Gallerie photo et vidéo réalisée avec
              angular js (frontend), node js et Mongodb (backend).Toujours en
              travaux</b-card-text
            >
             <b-button
              href="https://flamboyant-hypatia-ba590f.netlify.app/all"
              target="_blank"
              variant="primary"
              >Link Heroku</b-button
            >
            <br />
            <br />
            <b-button
              href="https://github.com/bertholddovi/z-gallerie-angular"
              target="_blank"
              variant="primary"
              >Link Github</b-button
            >
          </b-card>

          <b-card
            title="Site vitrine avec Wordpress"
            header-tag="header"
            footer-tag="footer"
          >
            <template v-slot:header>
              <h6 class="mb-0">eds - Wordpress</h6>
            </template>
            <b-card-text
              >eds est un Site Vitrine réalisé avec Wordpress pour La FGTB
              (Ecole des Solidarités)
            </b-card-text>
            <b-button
              href="http://eds.p2018.sirius-school.be/"
              target="_blank"
              variant="primary"
              >Lien du site en ligne</b-button
            >
            <template v-slot:footer>
              <em>Wordpress, javascript</em>
            </template>
          </b-card>
        </b-card-group>
      </div>
    </div>
  </section>
</template>
