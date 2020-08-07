<template>
  <section class="testimonial-section">
    <h1>What People Had To Say About Me</h1>
    <hr class="hr" />
    <div class="testimonial-container">
      <div class="first-image">
        <figure>
          <img
            src="../assets/male-one.png"
            alt="The Pulpit Rock"
            width=""
            height=""
          />
          <figcaption>
            JohnnyB is a very young talented <br />man. I love his music so
            much,<br />
            he’s going to make it big!
          </figcaption>
          <figcaption>Puff Jazzy</figcaption>
        </figure>
      </div>
      <div class="second-image">
        <figure>
          <img
            src="../assets/male-two.png"
            alt="The Pulpit Rock"
            width=""
            height=""
          />
          <figcaption>
            JohnnyB performed so well at my<br />
            60th birthday, my guests and I<br />
            really enjoyed his performance.
          </figcaption>
          <figcaption>James Harden</figcaption>
        </figure>
      </div>
      <div class="third-image">
        <figure>
          <img
            src="../assets/male-dup.png"
            alt="The Pulpit Rock"
            width=""
            height=""
          />
          <figcaption>
            JohnnyB is a very young talented <br />man. I love his music so
            much,<br />
            he’s going to make it big!
          </figcaption>
          <figcaption>Puff Jazzy</figcaption>
        </figure>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  name: "Testimonial",
};
</script>
<style scoped>
.testimonial-container {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
}
.testimonial-section {
  background-color: #161a22;
  height: 70vh;
  color: #ffffff;
  padding: 50px 0px;
  width: 100vw;
}
h1 {
  text-align: center;
  padding: 0px 10px;
}
.hr {
  width: 30px;
  position: relative;
  left: 37%;
}
figcaption {
  text-align: center;
  padding: 20px 0px;
}
img {
  margin: auto;
  display: block;
}
figure {
  margin: 20px 20px;
  margin-top: 50px;
}
@media screen and (max-width: 768px) {
  .testimonial-container {
    flex-direction: column;
    /* padding: 50px 0px; */
  }
  .testimonial-section {
    height: 200vh;
    margin-top: 30%;
  }
  h1 {
    text-align: center;
    padding: 0px 10px;
    font-size: 18px;
  }
}
/* @media only screen and (max-width: 500px) {
  .testimonial-section{
    height: 140vh; 
    padding: 50px 0px;
  }
} */
/* @media screen and (max-width: 699px) and (min-width: 520px) {
   .testimonial-section{
    height: 200vh; 
  }
} */
</style>
