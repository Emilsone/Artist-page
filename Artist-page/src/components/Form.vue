<template>
  <section class="section-form">
    <h1>Get In Touch</h1>
    <hr class="hr" />
    <p>
      Got an event you would like me to perform at? Or you want me to perform at
      your event? Or you even want an<br />
      autograph? Fill the contact form and we can do these and more. You will
      get a response as soon as we get your message
    </p>
    <div class="container-form">
      <form action="">
        <div class="form-container">
          <div class="input-one">
            <h6>Name</h6>
            <input type="text" name="" id="" />
          </div>
          <div class="input-two">
            <h6>Email Adress</h6>
            <input type="text" name="" id="" />
          </div>
        </div>
        <div class="text-area">
          <div class="text-box">
            <h6 class="message">Message</h6>
            <textarea name="message" rows="6" cols="40"> </textarea>
          </div>
        </div>
        <button type="submit" class="btn-message">Send Message</button>
      </form>
    </div>
  </section>
</template>
<script>
export default {
  name: "Form",
};
</script>
<style scoped>
.section-form{
  margin-top: 20%;
}
h1,
p {
  text-align: center;
  padding: 20px 40px;
  line-height: 23px;
}
p{
  font-size: 13px;
}
.hr {
  width: 30px;
  position: relative;
  left: 45%;
  bottom: 15px;
}
.form-container {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
}
.input-one,
.input-two {
  margin: 5px;
}
.text-area {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  margin-top: 40px;
}
.btn-message {
  margin: 20px;
  position: relative;
  left: 24%;
  padding: 8px 17px;
  background-color: #f43757;
  border-radius: 30px;
  outline: transparent;
  border: 2px solid #f43757;
}
input[type="text"] {
  width: 340px;
  display: block;
  background-color: rgb(230, 230, 227);
  padding: 16px;
  border: none;
  outline-color: transparent;
}
textarea {
  width: 700px;
  display: block;
  background-color: rgb(230, 230, 227);
  resize:none;
}
h6{
  padding: 10px;
  font-size: 15px;
}
@media (max-width: 768px) {
  .form-container {
    flex-direction: column;
  }
  textarea {
    width: 300px;
    margin: auto;
    resize:none;
  }
  .input-one,
  .input-two {
    margin: auto;
  }
   .message {
  padding-left: 50px;
  font-size: 15px;
}
  .text-area {
    flex-direction: column;
  }
}
@media (max-width: 500px) {
  input[type="text"] {
    width: 300px;
    display: block;
    background-color: rgb(230, 230, 227);
    padding: 16px;
    border: none;
    outline-color: transparent;
  }
  textarea {
    margin: auto;
    height: 300px;
  }
  .text-area {
    margin: auto;
    resize: none;
  }
  .message {
  padding-left: 32px;
  font-size: 15px;
}
}
</style>
