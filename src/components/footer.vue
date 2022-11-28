<template>
  <div class="end" style="background-color:white">
    <center>
    <img src="../img/logo.png" alt="" style="margin-top:5%"> </center>

    <div class="footer">
    <div>
      <h5><b>Overview</b></h5>
      <p>Shipping</p>
      <p>Refund</p>
      <p>Promotion</p>
    </div>

    <div>
    <h5><b>Company</b></h5>
      <p>About</p>
      <p>Career</p>
      <p>Contact Us</p>
    </div>

    <div>
    <h5><b>Explore</b></h5>
      <p>Terms & Conds</p>
      <p>Privacy Policy</p>
      <p>For Developer</p>
    </div>

    <div>
    <h5><b>Special Letter</b></h5>
      <input type="text" id="inputnama" placeholder=" Your Email Address">
      <button type="submit" id="sendemail" style="background-color:pink; height:29px;"><img src="../img/tele-icon.png" alt=""></button>
      <!-- <button type="submit" id="sendemail">send</button> -->
    </div>
</div>
</div>
</template>

<script>
export default {
name: 'FooterComponent',
  props: {
    msg: String
  }
}
</script>

<style>
.footer {
  display: flex;
  justify-content: space-around;
  margin-top: 5%;
}
</style>