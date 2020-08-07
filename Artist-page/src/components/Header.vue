<template>
  <header class="section-header">
    <!-- <section class="hero">
      <div id="overlay"></div> -->
    <!-- <nav class="navbar">
        <div style="display: flex;">
          
          <p>
            JohnnyB.
          </p>
        </div>

        <i class="fa fa-bars" id="icon"></i>

        <ul class="nav">
          <li><a href="" class="active">Home</a></li>
          <li><a href="">About</a></li>
          <li><a href="">Music</a></li>
          <li><a href="">Concerts</a></li>
           <li><a href="">Contact Us</a></li>
           
        </ul>
      </nav> -->
    <div id="main" class="parent">
      <div class="navbar">
        <div class="navbar-content">
          <div>Logo</div>
          <div class="toggle-button" v-on:click="showLinks = !showLinks">
            Naviagte
          </div>
        </div>
        <ul class="nav-links" v-bind:class="{ show: showLinks }">
          <li class="nav-link">Home</li>
          <li class="nav-link">About</li>
          <li class="nav-link">Music</li>
          <li class="nav-link">Concerts</li>
          <li class="nav-link">Contact Us</li>
        </ul>
      </div>
    </div>
    <!-- </section> -->
  </header>
</template>
<script>
export default {
  name: "Header",
  data: () => {
    showLinks: true;
  },
  methods: {
    flipLinks: function() {
      console.log("called");
      this.showLinks = !this.showLinks;
    },
  },
};
</script>
<style>
/* .hero #overlay {
  /* background-color: rgba(0, 0, 0, 0.7); */
/* position: absolute;
  width: 100%;
  height: 100%;
}

.hero{
   background-color:#FFFFFF;
} */

/* .navbar { */
/* position: relative; */
/* display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  align-items: center;
  margin: 0 50px;
  padding: 20px 0px;
 
}
.fa-bars,
.fa-close {
  color:#333333;
  font-size: 30px !important;
  display: none !important;
}

.hero .navbar p {
  text-transform: capitalize;
  font-size: 1.1rem;
  color: #F43757;
}

.hero .navbar .nav {
  list-style: none;
  padding: 0;
  margin: 0;
  display: flex;
  flex-wrap: wrap;
  align-items: center;
 
}

.hero .navbar .nav li {
  margin-left: 5rem;
}

.hero .navbar .nav li a {
  text-decoration: none;
  font-size: 15px;
  color: #333333;
  padding: 0.3rem;
}
.active{
  color: #F43757;
}
@media screen  and (max-width: 768px){
  .fa-bars,
.fa-close {
  color:#333333;
  font-size: 30px !important;
}
} */

.parent {
  width: 100vw;
}

.navbar {
  position: relative;
  border: 1px solid lightgrey;

  margin: 20px;
}

.navbar-content {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px 40px;
}

.toggle-button {
  border: 1px solid lightgrey;
  padding: 10px 20px;
  cursor: pointer;
  border-radius: 3px;
}

.nav-links {
  position: absolute;

  display: flex;
  flex-direction: column;
  align-items: center;

  list-style: none;
  border: 1px solid lightgrey;
  width: 100%;
  padding: 0;
  top: 100%;
  transform-origin: 50% 0%;
  transform: scaleY(0);
  transition: 0.3s ease-in;
}

.nav-links.show {
  transform: scaleY(1);
}

.nav-link {
  background: lightgrey;
  margin: 10px 0px;
  padding: 5px 30px;
  border-radius: 3px;
  cursor: pointer;
}
</style>
