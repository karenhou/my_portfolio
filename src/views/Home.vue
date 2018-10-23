<template>
  <div>
    <div class="container-fluid text-center my-background">
        <div class="row">
          <div class="col">
            <h1>Hello!</h1>
          </div>
        </div>
    </div>

    <section class="text-center container-fluid" id="intro">
        <div class="row">
          <div class="col">
            <span>
              <a href="mailto:ymcl760728@gmail.com" rel="noopener"><i class="far fa-envelope fa-5x"></i></a>
              <a target='_blank' href="https://github.com/karenhou" rel="noopener"><i class="fab fa-github fa-5x"></i></a>
              <a target='_blank' href="https://www.linkedin.com/in/karen-hou-6a407069/" rel="noopener"><i class="fab fa-linkedin fa-5x"></i></a>
            </span>
          </div>
        </div>
        <div class="row">
          <div class="col">
            <p>my name is <span class="my-title">Karen</span></p>
            <p>I'm a web developer, open for job offerings</p>
            <p>Drop me a line</p>
          </div>
        </div>
    </section>

    <section class="text-center" id="projects">
      <div class="container">
        <div class="row">
          <div class="col">
            <h1 class="mt-5" id="projectTitle">Work</h1>
          </div>
        </div>

        <div class="row shadow p-3 bg-white rounded mt-4">
          <div class="col-md-4">
            <a target='_blank' href="https://vue-authentication-73b90.firebaseapp.com/" rel="noopener"><img src="https://png.icons8.com/ios/230/cccccc/web.png" alt="can't find"></a>
          </div>
          <div class="col-md-8 px-3">
            <div class="card-block px-3 pt-4">
              <h4 class="card-title">Rss getter<i class="far fa-browser"></i></h4>
              <p class="card-text">A page where user can see quote of the day, weather, and several rss feeds using APIs. User can also login with FB.</p>
              <p><img src="https://png.icons8.com/color/50/cccccc/api.png" style="padding-right: 1em;" alt="api icon"><img src="https://png.icons8.com/color/50/000000/firebase.png" alt="firebase icon"><img id='vue-icon' src="https://upload.wikimedia.org/wikipedia/commons/5/53/Vue.js_Logo.svg" alt="can't find"><img src="https://png.icons8.com/color/50/cccccc/bootstrap.png" alt="bootstrap icon"></p>
            </div>
          </div>
        </div>

        <div class="row shadow p-3 bg-white rounded mt-4">
          <div class="col-md-4">
            <a target='_blank' href="https://weighter-fee2d.firebaseapp.com/" rel="noopener"><img src="https://png.icons8.com/ios/230/cccccc/web.png" alt="can't find"></a>
          </div>
          <div class="col-md-8 px-3">
            <div class="card-block px-3 pt-4">
              <h4 class="card-title">Weighter<i class="far fa-browser"></i></h4>
              <p class="card-text">Prompt user to use email login/signin so they can save their weights and body fat%. It will then display a chart accordingly</p>
              <p><img src="../assets/chartjs-logo.svg" style="padding-right: 1em;" alt="api icon" id="chart-js"><img src="https://png.icons8.com/color/50/000000/firebase.png" alt="firebase icon"><img id='vue-icon' src="https://upload.wikimedia.org/wikipedia/commons/5/53/Vue.js_Logo.svg" alt="can't find"><img src="https://png.icons8.com/color/50/cccccc/bootstrap.png" alt="bootstrap icon"></p>
            </div>
          </div>
        </div>

        <div class="row shadow p-3 bg-white rounded mt-4">
          <div class="col-md-4">
            <a href=""><img src="https://png.icons8.com/ios/230/cccccc/road-worker.png" alt="can't find"></a>
          </div>
          <div class="col-md-8 px-3 pt-5">
            <div class="card-block px-3">
              <h4 class="card-title">Under contruction</h4>
              <p class="card-text">Coming up soon...</p>
            </div>
          </div>
        </div>

        <p class="pt-4"></p>
      </div>
      
    </section>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "home",
  components: {}
};
</script>

<style>
h1 {
  color: white;
  font-size: 7em;
}
.my-background {
  padding-top: 15em;
  padding-bottom: 15em;
  background: linear-gradient(to bottom,  #41b983 0%, #35495e 100%);
}
#intro {
  color: white;
  padding: 5em 0 10em 0;
  background: linear-gradient(to bottom,  #35495e 100%,  #41b983 0%);
}

#intro p {
  font-size: 1.5em;
}

.my-title {
  font-size: 4.5em;
  color: #41b983;
}

i {
  margin: 0 0.5em 0 0.5em;
}

a:hover {
  color: #41b983;
}

#projects {
  background: linear-gradient(to bottom,  #35495e 0%,  #41b983 100%);
}

#projects p {
  margin-bottom: 0px;
}

#projectTitle {
  font-size: 4em;
  color: white;
}

.rounded {
  border-radius: 1rem !important;
}

#vue-icon {
  width: 4em;
}

#chart-js {
  width: 4em;
}
</style>

