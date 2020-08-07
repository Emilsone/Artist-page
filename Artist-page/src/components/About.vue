<template>
  <section class="about-section">
    <h1>About Me</h1><hr class="hr">
    <div class="container">
      <div class="banner-img">
           <img alt=" Young guy " src="../assets/guy.png" />
      </div>
      <div class="banner-text">
        <p>
           Hey! Welcome here. About me? You probably know all about me from
          listening to my music. Don’t listen to my music? Well, this is a step
          in the right direction. My name is Walker Johnny, a RnB singer with
          the stagename “JohnnyB”. I started singing since i was 5 years old,
          but i started singing officially in 2018. After my debut album
          Infinite (2019), I signed with Turner Beacons record and subsequently
          achieved mainstream popularity in late 2019 with Butterflies EP. I
          have since then released other music which includes Dont leave me,
          Love you Baby amongst others. 
        </p>
        <button type="submit" class="btn-book">Book Now</button>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  name: "About",
};
</script>
<style scoped>
/* .about-section {
  background: #e5e5e5;
  height: 90vh; 
  width: 100vw;

} */
h1 {
  text-align: center;
  padding: 20px ;
}

.container{
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    padding-top: 90px;
}
p{
    width: 600px;
    font-size: 16px;
    padding-top: 30px 0px;
    line-height: 30px;
}
.hr {
  width: 39px;
  position: relative;
  left: 46%;
  bottom: 3%;
}
img{
    width: 300px;
    height: 300px;
}
.btn-book{
    background-color: #F43757;
    border-radius: 30px;
    color: white;
    padding: 10px 40px;
    outline: #F43757;
    margin-top: 20px;
    border: 2px solid #F43757;
    /* margin:0px 30px; */
}
@media (max-width: 768px) {
  /* .container{
    flex-direction: column;
  } */
  p{
    width: 300px;
    font-size: 13px;
    padding: 0px 20px;
}
/* .about-section {
  background: #e5e5e5;
  height: 108vh;
} */
img{
    width: 304px;
    height: 228px;
    max-width:300px ;
}
}
</style>
