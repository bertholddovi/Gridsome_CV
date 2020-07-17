  <template>
  <nav id="sideNav" class="list-group shift">
    <!-- Photo -->
    <div v-on:click.prevent="$scrollTo('#about')" class="navbar-brand">
      <span class="d-none d-md-block">
        <g-image
          alt="Image of myself"
          src="../assets/images/profil.jpg"
          class="img-fluid img-profile rounded-circle mx-auto mb-2"
        />
      </span>
    </div>
    <!-- navigation part  -->
    <div class="collapse navbar-collapse" id="mysidebar ">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link" v-on:click.prevent="$scrollTo('#about')">Profile</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" v-on:click.prevent="$scrollTo('#contact')">Contacts</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" v-on:click.prevent="$scrollTo('#informations')">Informations</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" v-on:click.prevent="$scrollTo('#experience')">Experiences</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" v-on:click.prevent="$scrollTo('#formation')">Formations</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" v-on:click.prevent="$scrollTo('#skills')">Skills</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" v-on:click.prevent="$scrollTo('#langue')">Languages</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" v-on:click.prevent="$scrollTo('#interest')">Hobbies</a>
        </li>
         <li class="nav-item">
          <a class="nav-link" v-on:click.prevent="$scrollTo('#portfolio')">Portfolio</a>
        </li>
      </ul>
    </div>
  </nav>
</template>