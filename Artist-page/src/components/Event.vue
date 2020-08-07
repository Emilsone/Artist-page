<template>
  <section class="event-section">
    <div class="event-container">
      <div class="banner-img">
        <img alt=" Young guy " src="../assets/event.png" />
      </div>
      <div class="banner-text">
        <h1>Event Booking</h1> <hr class="hr">
        <p>
          Invite me to come and have fun at your parties and also entertain
          you with my soul touching music. Birthdays, Wedding, Anniversaries, or
          you just want to surprised your loved one? Reach out to me for the
          most heart warming performance. There is also a catch! You get a
          recording of the performance recorded by my personal videographer,
          John Doe. Let’s have fun together.
        </p>
        <button type="submit" class="btn-book">Get In Touch</button>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  name: "Event",
};
</script>
<style scoped>
.event-container {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  padding: 70px 0px;
}
.event-section {
  background: #FFFFFF;
  /* height: 0vh; */
  width: 100vw;
}
.hr {
  width: 39px;
  position: relative;
  /* left: 10%; */
  top: 3%;
}
.btn-book {
  background-color: #f43757;
  border-radius: 30px;
  color: white;
  padding: 10px 40px;
  outline: #f43757;
  margin-top: 20px;
  border: 2px solid #f43757;
  /* margin:0px 30px; */
}
p {
  width: 600px;
  font-size: 16px;
  line-height: 40px;
}
img {
  width: 300px;
  height: 280px;
}
.banner-text {
  padding: 10px 0px;
}
@media (max-width: 768px) {
 p {
  width: 300px;
  font-size: 13px;
  line-height: 30px;
  padding-top: 50px;
 
}
.btn-book{
  margin-top:  10px;
}
.banner-text,.banner-img{
margin: 10px 0px;
}
}

</style>
