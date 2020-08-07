<template>
  <section class="music-section">
    <h1>Lattest Music</h1>
    <hr class="hr" />
    <div class="music-container">
      <div class="first-image">
        <figure>
          <img
            src="../assets/red.png"
            alt="The Pulpit Rock"
          
          />
          <figcaption>The People</figcaption>
          <figcaption>Available on Itunes, Spotify </figcaption>
        </figure>
      </div>
      <div class="second-image">
        <figure>
          <img
            src="../assets/yellow.png"
            alt="The Pulpit Rock"
           
          />
          <figcaption>Love Storm</figcaption>
          <figcaption>Available on Itunes, Spotify</figcaption>
        </figure>
      </div>
      <div class="third-image">
        <figure>
          <img
            src="../assets/dark.png"
            alt="The Pulpit Rock"
           
          />
          <figcaption>Back To The Begining</figcaption>
          <figcaption> Available on Itunes, Spotify </figcaption>
        </figure>
      </div>
    </div>
  </section>
</template>
<script>
export default {
    name:"Flexbox"
}
</script>
<style scoped>
.music-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}
.music-section h1{
    text-align: center;
    padding: 30px 0px;
}
figure img{
    width:304px;
    height:228px;
}
figcaption{
    line-height: 30px;
}
figure{
  margin: 30px 20px;
}
.hr {
  width: 39px;
  position: relative;
  left: 46%;
  bottom: 3%;
}
@media screen and (max-width: 280px){
   figure img{
      width:204px;
    height:170px;
} 
}

</style>

