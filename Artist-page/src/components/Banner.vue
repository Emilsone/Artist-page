<template>
  <section class="section-class">
    <!-- <div id="section-banner">
      <div class="spotify">
         <h1>Love You Baby </h1>
        <p>Available now on Itunes, Spotify </p>
       <button type="submit" class="btn-message">Send Message</button>
      </div>
</div> -->
  </section>
</template>
<script>
export default {
    name:"Banner"
}
</script>
<style >


/* #section-banner{
   position: relative;
  width: 100vw;
  height: 100vh;
  max-width: 100%;
  background-image: url("../assets/rectangle.png");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: right;
} */
 .btn-message{
    margin: 20px;
    padding: 8px;
    background-color: #F43757;
    border-radius: 30px;
    outline: transparent;
    border: 2px solid #F43757;
     color: #FFFFFF;


}
.spotify{
 position: relative;
 left: 4%;
 top: 30%;
 line-height: 50px;
 color: #FFFFFF;
}
.spotify h1{
  font-size: 60px;
}

</style>

