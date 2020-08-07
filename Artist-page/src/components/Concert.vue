<template>
  <section class="music-section">
    <h1> Concerts I’ve Featured In </h1>
    <p> I love entertaning people and performing music to make them happy. I’m open to performing and entertaining the fans at your concert. 
      Let’s discuss further. Contact Me </p>
    <hr class="hr" />
    <div class="music-container">
      <div class="first-image">
        <figure>
          <img
            src="../assets/first.png"
            alt="The Pulpit Rock"
          
          />
          <figcaption>Party Hard Concert (2018) </figcaption>
          <!-- <figcaption>Available on Itunes, Spotify </figcaption> -->
        </figure>
      </div>
      <div class="second-image">
        <figure>
          <img
            src="../assets/second.png"
            alt="The Pulpit Rock"
           
          />
          <figcaption> Wizzy Storms Alabama (2019)</figcaption>
          <!-- <figcaption>Available on Itunes, Spotify</figcaption> -->
        </figure>
      </div>
      <div class="third-image">
        <figure>
          <img
            src="../assets/third.png"
            alt="The Pulpit Rock"
           
          />
          <figcaption>O.B.O In New Jersey (2020)</figcaption>
          <!-- <figcaption> Available on Itunes, Spotify </figcaption> -->
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
p{
  text-align: center;
  font-size: 13px;
  
}
.music-section h1{
    text-align: center;
    padding: 30px 0px;
    margin-top: 10%;
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
   /* figure img{
      width:204px;
    height:170px;
}  */
}

</style>

