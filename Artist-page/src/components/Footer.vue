<template>
  <footer class="footer-section">
    <section class="footer">
      <div class="icon-text">
        <h1>JohnnyB.</h1>
      </div>
      <div class="icon-text">
        <p>Copyright, Turner Beacons Record 2020</p>
      </div>
      <div class="icon-text">
          <span><i class="fa fa-facebook-square" aria-hidden="true"></i></span>
          <span><i class="fa fa-instagram" aria-hidden="true"></i></span>
          <span><i class="fa fa-twitter" aria-hidden="true"></i></span>
          <span><i class="fa fa-linkedin" aria-hidden="true"></i></span>
          <span><i class="fa fa-youtube" aria-hidden="true"></i></span>
      </div>
    </section>
  </footer>
</template>
<script>
export default {
    name:"Footer"
}
</script>
<style scoped>
.footer-section{
    background-color: #E5E5E5;
    width: 100vw;

} 
.footer{
  display: flex;
  justify-content: space-around;
  align-items: center;
}
span i{
  padding: 10px;
  font-size: 20px;
}
.icon-text{
padding: 10px 0px;
}
@media (max-width: 768px) {
  .footer{
    flex-direction: column;
    padding: 30px 0px;
    margin-top: 10%;
  }
  .footer{
    font-size: 12px;
  }
} 
</style>


