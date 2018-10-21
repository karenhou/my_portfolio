<template>
  <div>
    <div class="position-relative overflow-hidden p-md-5 m-md-3 text-center bg-light">
        <div class="row">
          <div class="col">
            <h1 id="circle" class="font-weight-normal pt-3 text-center"></h1>
          </div>
          <div class="col">
          </div>
        </div>
        <div class="row">
          <div class="col">
            <h3>Hello!</h3>
          </div>
        </div>
        <div class="row">
          <div class="col">
          </div>
          <div class="col">
            <h1 id="halfCircleBottom" class="font-weight-normal pt-3 text-center"></h1>
          </div>
        </div> 
    </div>

    <section class="text-center container-fluid bg-white" id="intro">
        <div class="row">
          <div class="col">
            <span>
              <a href="mailto:ymcl760728@gmail.com"><i class="far fa-envelope fa-5x"></i></a>
              <a target='_blank' href="https://github.com/karenhou"><i class="fab fa-github fa-5x"></i></a>
              <a target='_blank' href="https://www.linkedin.com/in/karen-hou-6a407069/"><i class="fab fa-linkedin fa-5x"></i></a>
            </span>
          </div>
          
        </div>
        <div class="row">
          <div class="col">
            <!-- <p class="text-muted">My name is h4</p> -->
            <!-- <h4 class="mt-3 ">my nams is </h4> -->
            <p class='text-muted'>my name is <span class="my-title">Karen</span></p>
            <p class="text-muted">I'm a web developer, open for job offerings</p>
            <p class="text-muted">Drop me a line</p>
          </div>
        </div>
    </section>

    <section class="text-center " id="projects">
      <div class="container">
        <div class="row">
          <div class="col">
            <h1 class="mt-5" id="projectTitle">Project</h1>
          </div>
        </div>

        <div class="row shadow p-3 bg-white rounded mt-4" id="card">
          <div class="col-md-4">
            <a href=""><img src="https://png.icons8.com/ios/230/cccccc/web.png"></a>
          </div>
          <div class="col-md-8 px-3">
            <div class="card-block px-3 pt-4">
              <h4 class="card-title">Rss getter<i class="far fa-browser"></i></h4>
              <p class="card-text">A page where user can see quote of the day, weather, and several rss feeds using APIs. User can also login with FB.</p>
              <p><img src="https://png.icons8.com/color/50/cccccc/api.png" style="padding-right: 1em;"><img src="https://png.icons8.com/color/50/000000/firebase.png"><img id='vue-icon' src="https://upload.wikimedia.org/wikipedia/commons/5/53/Vue.js_Logo.svg" alt="can't find"><img src="https://png.icons8.com/color/50/cccccc/bootstrap.png"></p>
            </div>
          </div>
        </div>

        <div class="row shadow p-3 bg-white rounded mt-4" id="card">
          <div class="col-md-4">
            <a href=""><img src="https://png.icons8.com/ios/230/cccccc/road-worker.png"></a>
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
#circle {
  height: 7.5em;
  width: 100%;
  border-radius: 300px 300px 0 0;
  background: #35495e;
  z-index: -1;
}

#halfCircleBottom {
  height: 7.5em;
  width: 100%;
  border-radius: 0 0 300px 300px;
  background: #35495e;
  z-index: -3;
}

hr {
  width: 97%;
  margin-left: auto;
  margin-right: auto;
  height: 10px !important;
  background-color: #35495e;
}

h2 {
  color: #35495e;
  width: 100%;
  text-align: center;
  border-bottom: 10px solid #fff;
  line-height: 0.1em;
  margin: 10px 0 20px;
}

h2 span {
  font-size: 3.5em;
  background: #fff;
  padding: 10px 10px;
  color: #41b983;
}

.col {
  padding: 0;
}

h1 {
  margin-bottom: 0;
}

.col h3 {
  margin-bottom: 0px;
  background: #fff;
  color: #35495e;
  font-size: 7em;
  margin: 0 35% 0 35%;
  position: absolute;
  top: -60px;
  z-index: 2;
  border: 2px solid #35495e;
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
  background: #35495e;
}

#projects p {
  margin-bottom: 0px;
}

#projectTitle {
  color: white;
}

.rounded {
  border-radius: 1rem !important;
}

#vue-icon {
  width: 4em;
}

#intro {
  color:#35495e;
  margin: 15em 0 15em 0;
}

#intro p {
  font-size: 1.5em;
}
</style>

