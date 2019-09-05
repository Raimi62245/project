<template>
  <div id="app">
    <b-container fluid>
      <b-row>
        <b-col md="6" offset-md="6" id="bgd">
          <b-col md="6" offset-md="3"> 
            <form>
              <input type="text" id="login" placeholder="Email ou telephone" class="form-control">

              <br>

              <input type="password" id="password" placeholder="Mot de passe" class="form-control">

              <button type="button" id="btn" class="btn btn-warning form-control">CONNEXION</button>
              
              <a style="color: #fff; font-size: 11px">Vous n'êtes pas encore inscrit?</a>
              <a style="color: #fff; font-size: 11px; margin-left: 42px">Mot de passe oublié</a>
              
            </form>
          </b-col>
        </b-col>
      </b-row>
    </b-container fluid>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
    }
  }
}
</script>

<style lang="scss">
#app {
 
}

#bgd {
  background-color: #42b983;
  padding-bottom: 245px

}
#btn {
  color: #fff;
  margin-top: 50px;
}

form{
   margin-top: 200px;
}

</style>
