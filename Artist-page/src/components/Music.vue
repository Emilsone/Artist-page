<template>
  <section class="music-section">
    <!-- <h1>Lattest Music</h1>
    <hr class="hr" />
    <div class="music-container">
      <div class="first-image">
        <figure>
          <img
            src="../assets/red.png"
            alt="The Pulpit Rock"
            width="304"
            height="228"
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
            width="304"
            height="228"
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
            width="304"
            height="228"
          />
          <figcaption>Back To The Begining</figcaption>
          <figcaption> Available on Itunes, Spotify </figcaption>
        </figure>
      </div>
    </div> -->
  </section>
</template>
<script>
export default {
  name: "Music",
};
</script>

<style scoped>
h1 {
  text-align: center;
  padding: 20px 10px;
  margin-bottom: 30px;
}
/* .music-section {
  background: #ffffff;
  padding: 80px 30px;
  background-size: cover;
} */
.music-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}
.hr {
  width: 30px;
  position: relative;
  left: 45%;
  bottom: 40px;
}
figure{
  margin: 0px 30px;
}
/* @media  (max-width: 768px) {
  .music-container{
    flex-direction: column;
  }
  figure{
    padding: 20px 0px;
     margin: 0px auto;
  }
} */
</style>
