<template>
    <div>
      <b-navbar toggleable="lg" type="dark" variant="dark">
        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
            <b-collapse id="nav-collapse" is-nav>
                <b-navbar-nav>
                    <b-nav-item><router-link class="nav-link" to="/">Home</router-link></b-nav-item>
                    <b-nav-item><router-link class="nav-link" to="/details">Détails</router-link></b-nav-item>
                </b-navbar-nav>
            </b-collapse>
      </b-navbar>
    </div>
</template>

<script>
  export default {
      name: 'navbar',
      components: {

      },

  }
</script>