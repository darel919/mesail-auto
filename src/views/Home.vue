<template>
  <div class="home">

    <div class="first-sector">
      <div class="first-sector-text">
        <h1>We Provide</h1>
        <h1 style="font-weight:bolder;">Great Quality</h1>
        <h1>Cars and Bikes.</h1>
        <div class="first-sector-btn">Contact Us</div>
      </div>
      <img src="@/../public/img/Group 5 (2).png"/>
    </div>

    <div class="second-sector">
      <div class="second-sector-img">
        <img src="@/../public/img/Group 5.png"/>
      </div>
      <div class="second-sector-text">
        <div class="second-sector-text-title">
          <h1>About Us</h1>
          <div class="second-sector-text-title-line"></div>
        </div>
        <h2>We are a trusted car & motorcycle dealership
        run by a group of young and passionate automotive enthusiasts, We specializes in providing Great Quality ready to use vehicles, dedicated to help indonesian people who needs an Affordable and Reliable Cars & Motorcycles for their daily Commuter.</h2>
        <router-link to="/about"> 
          <div class="second-sector-btn">
            Learn More
          </div>
        </router-link>
      </div>
    </div>

    <div class="third-sector">
      <div class="third-sector-left">
        <div class="third-sector-left-text">
          <h3>What We Do?</h3>
          <h1>We help people save their money.</h1>
        </div>
        <img src="@/../public/img/splash.png"/>
      </div>
      <div class="third-sector-right">
        <div class="third-sector-right-text">
          <h3>By purchasing a used cars or bike, you can directly save up to 40% of your money upfront.
          </h3>
          <h2>This is because, brand new vehicles have a depreciation in value of around 20-40% in its first year, and around 60% in 5 years of usage when you sell it.</h2>
          <h2>But when you purchase a used car/bike the value will not decrease as much because the depreciation has already been done, so you will get the same item for much cheaper and save up your cash.</h2>
        </div>
      </div>
    </div>

    <div class="fourth-sector">
      <div class="fourth-sector-left">
        <h1>Brand New</h1>
        <img src="@/../public/img/Group 6.png"/>
        <h2>Honda Vario 125 CBS-ISS (2021)</h2>
        <h3>Rp21,910,000</h3>
        <h4>*OTR Jakarta according to Honda</h4>
      </div>
      <h1>Or</h1>
      <div class="fourth-sector-right">
        <div class="fourth-sector-right-title">
          <h1>Used</h1>
          <h2>(Like new condition)</h2>
        </div>
        <img src="@/../public/img/vario.png"/>
        <h2>Honda Vario 125 CBS-ISS (2017)</h2>
        <h3>Rp13,000,000</h3>
        <h4>(around 40% cheaper)</h4>
      </div>
    </div>

    <div class="fifth-sector">
      <div class="fifth-sector-left">
        <h1>The process</h1>
        <div class="fifth-sector-left-line2">
          <h1>Behind</h1>
          <h1 style="color:red;">.</h1>
        </div>
        <img src="@/../public/img/P1330042 2.png"/>
      </div>
      <div class="fifth-sector-right">
        <h2>We Hunt</h2>
        <h3>Every year, people buy new cars and motorcycles and after some period of usage and driven miles, some of them are being sold for many different reasons, that is where we come in.</h3>
        <h2>We Inspect</h2>
        <h3>Our team of technician will make sure the condition of the cars and bike before we bring it home to our garage, usually they check on whether the bike’s registration are valid, and whether there are any damage that needed to be repaired.</h3>
        <h2>We Prepare</h2>
        <h3>Every unit that we provide has to meet a certain quality standard before given to the client, we make sure that every component are in a great condition, and the vehicle itself are nice to drive, plus we always give every vehicle a Detailing Treatment as a compliment to our clients, and as a way to give our lovely goodbye to every vehicle that we take care.</h3>
      </div>
    </div>

    <div class="sixth-sector">
      <div class="sixth-sector-left">
        <h1>Come and say Hi!</h1>
        <h2>We're located at:</h2>
        <h3>Perumahan Bumi Sawangan Indah</h3>
        <h3>Jl. Karet Atas No. 9, Pengasinan, Sawangan</h3>
        <h3>Depok, Jawa Barat</h3>
        <h3>16518</h3>
        <h1>Or visit our social media</h1>
        <div class="sixth-sector-left-icons">
          <a href="https://facebook.com/mesailauto" target="_blank" title="Open Mesailauto's Facebook">
          <ion-icon class="fb" name="logo-facebook"></ion-icon>
          </a>
          <a href="https://instagram.com/mesailauto" target="_blank" title="Open Mesailauto's Instagram">
          <ion-icon class="ig" name="logo-instagram"></ion-icon>
          </a>
          <a href="https://youtube.com/mesailauto" target="_blank" title="Open Mesailauto's YouTube">
          <ion-icon class="yt" name="logo-youtube"></ion-icon>
          </a>
        </div>
        <h1>Our Contacts:</h1>
        <h2>(+62 812 8722 8633)</h2>
        <a href="mailto:mesailauto@gmail.com">
        <h2>mesailauto@gmail.com</h2>
        </a>
      </div>
      <div class="sixth-sector-right">
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3964.804689312419!2d106.75166061477023!3d-6.419136295355611!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e69e93c676735a3%3A0xfbc4b5734f63a059!2sMesail%20Auto!5e0!3m2!1sid!2sid!4v1631788756087!5m2!1sid!2sid" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
      </div>
    </div>

  <h4>Made by Mesail Auto 2021</h4>
  </div>
</template>

<script>

export default {
  name: 'Home',
  created() {
    document.title = "Welcome to MesailAuto";
  }

}
</script>

<style>
/* for phone mode */
@media screen and (max-width: 870px) {

.first-sector, .second-sector, .third-sector, .fourth-sector, .fifth-sector, .sixth-sector {
  flex-direction: column;
  line-height: 1.75;
}
.first-sector-text {
  /* margin-left: 125px; */
  width: 100%;
  position: absolute;
  color:whitesmoke;
  /* background: yellowgreen; */
  z-index:99;
}
.first-sector-text h1 {
  font-size: 30px;
  text-align: center;
  margin:0;
  font-weight:lighter;
}
.first-sector-btn {
  background: red;
  margin: 30px auto 0 auto;
  padding: 15px 20px 15px 20px;
  width: 175px;
  font-weight:bolder;
  font-size: 20px;
  transition: 0.2s;
}
.first-sector-btn:hover {
  background: white;
  color:Red;
  transition: 0.2s;
}
.app {
  width: 100%;
}
img {
  width: 100%;
}
.sixth-sector-right iframe {
  width: 90vw;
  height: 700px;
}
.second-sector {
  display: flex;
  background: whitesmoke;
  align-items: center;
}
.second-sector-img {
    padding: 100px 5% 20px 5%;
}
.second-sector-text-title {
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.second-sector-text-title-line {
  background: red;
  width: 55%;
  height: 7px;
}
.second-sector-text {
  padding: 0 5% 0 5%;
  text-align: left;
}
.second-sector-btn {
  border: 5px red solid;
  width: 150px;
  padding: 10px;
  font-size: 20px;
  text-align: center;
  font-weight: bolder;
  transition:0.3s;
}
.second-sector-btn:hover {
  background: red;
  color:whitesmoke;
  transition: 0.3s;
}
.third-sector {
  display: flex;
  align-items: center;
  padding: 150px 5% 0 5%;
  background: whitesmoke;
  text-align: left;
}
.third-sector-left-text h3 {
  font-weight: lighter;
  font-size: 27px;
}
.third-sector-left-text h1 {
  font-weight: bolder;
  font-size: 35px;
}
.third-sector-right-text h3 {
  font-weight: bolder;
  font-size: 25px;
}
.third-sector-right-text h2 {
  font-weight: lighter;
  font-size: 20px;
}
.fourth-sector{
  background: whitesmoke;
  display: flex;
  align-items: center;
  justify-content:space-evenly ;
  padding: 30px 5% 100px 5%;
}
.fourth-sector-right-title {
  display: flex;
  align-items: center;
  justify-content: center;
}
.fourth-sector-right-title h2 {
  font-weight: lighter;
  font-size: 16px;
}
.fourth-sector-left h1 {
  font-weight: bolder;
}
.fifth-sector {
  display: flex;
  align-items: center;
  justify-content: space-around;
  color:white;
  background-size: cover;
  /* background-blend-mode:darken; */
  background:black;
  /* background: url('https://mesailauto.com/img/P1330042%202.5caa16f9.png'), rgba(0, 0, 0, 0.8); */
  text-align: left;
  padding: 50px;
}
.fifth-sector-left-line2 {
  display: flex;
}
.fifth-sector h1{
 font-size: 60px;
 margin:0;
}
.fifth-sector-right h2 {
  font-weight: bolder;
  font-size: 35px;
}
.fifth-sector-right h3 {
  font-weight: lighter;
  font-size: 17px;
  line-height: 1.8;
}
}
/* pc mode */
@media screen and (min-width: 870px) {
  .home {
    line-height: 1.4;
  }
.first-sector img {
  width: 100%;
}
.first-sector-text {
  margin-left: 125px;
  position: absolute;
  color:whitesmoke;
  /* background: yellowgreen; */
  z-index:99;
}
.first-sector-text h1 {
  font-size: 70px;
  text-align: left;
  margin:0;
  font-weight:lighter;
}
.first-sector-btn {
  background: red;
  margin-top: 40px;
  padding: 20px 30px 20px 30px;
  width: 180px;
  font-weight:bolder;
  font-size: 25px;
  transition: 0.2s;
}
.first-sector-btn:hover {
  background: white;
  color:Red;
  transition: 0.2s;
}
.second-sector-img img {
  width: 525px;
}
.second-sector {
  display: flex;
  background: whitesmoke;
  align-items: center;
  justify-content: space-between;
  padding: 75px 5% 75px 5%;
}
.second-sector-text-title {
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.second-sector-text-title-line {
  background: red;
  width: 95%;
  height: 7px;
  margin-top:10px;
}
.second-sector-text {
  padding: 0 5% 0 5%;
  text-align: left;
}
.second-sector-btn {
  border: 5px red solid;
  width: 200px;
  padding: 20px;
  font-size: 25px;
  text-align: center;
  font-weight: bolder;
  transition:0.3s;
}
.second-sector-btn:hover {
  background: red;
  color:whitesmoke;
  transition: 0.3s;
}
.third-sector-left img {
  width: auto;
  max-width: 550px;
}
.third-sector {
  display: flex;
  align-items: center;
  padding: 100px 3% 100px 3%;
  justify-content: space-evenly;
  background: whitesmoke;
  text-align: left;
}
.third-sector-left, .third-sector-right {
  padding: 3%;
}
.third-sector-left-text h3 {
  font-weight: lighter;
  font-size: 32px;
}
.third-sector-left-text h1 {
  font-weight: bolder;
  font-size: 45px;
}
.third-sector-right-text h3 {
  font-weight: bolder;
  font-size: 27px;
}
.third-sector-right-text h2 {
  font-weight: lighter;
  font-size: 24px;
}
.fourth-sector img {
  width: 400px;
}
.fourth-sector{
  background: whitesmoke;
  display: flex;
  align-items: center;
  justify-content:space-evenly ;
  padding: 50px 35px 50px 35px;
}
.fourth-sector-right-title {
  display: flex;
  align-items: center;
  justify-content: center;
}
.fourth-sector-right-title h2 {
  font-weight: lighter;
}
.fourth-sector-left h1 {
  font-weight: bolder;
}
.fifth-sector img {
  padding-top:50px;
  width: 100%;
  min-width: 475px;
  max-width: 550px;
}
.fifth-sector {
  display: flex;
  align-items: center;
  justify-content: space-evenly;
  color:white;
  background-size: cover;
  background-blend-mode:darken;
  background: url('https://mesailauto.com/img/P1330042%202.61aec082.png'), rgba(0, 0, 0, 0.8);
  text-align: left;
  padding: 50px 5% 50px 5%;
}
.fifth-sector-left-line2 {
  display: flex;
}
.fifth-sector h1{
 font-size: 80px;
 margin:0;
}
.fifth-sector-right {
  /* width: 50%; */
  padding: 100px;
}
.fifth-sector-right h2 {
  font-weight: bolder;
  font-size: 35px;
}
.fifth-sector-right h3 {
  font-weight: lighter;
  font-size: 20px;
}
.sixth-sector-right iframe {
  width: 45vw;
  height: 700px;
}
}
.first-sector, .second-sector, .third-sector, .fourth-sector, .fifth-sector, .sixth-sector {
 transition: all 0.4s;
}
.home {
background:whitesmoke;
transition: all 0.4s;
/* padding: 50px 50px 50px 50px; */
}
.first-sector {
 display: flex;
 flex-direction: row;
 align-items: center;
 width: 100%;
 height: 100%;
}
.second-sector-text h2 {
  font-weight: lighter;
}
.second-sector-text-title h1 {
  width: 200px;
  font-weight:bolder;
}
.sixth-sector {
  display: flex;
  align-items: center;
  background: whitesmoke;
  padding: 50px;
  text-align: left;
  justify-content: space-between;
}
.sixth-sector-left h1 {
  padding: 10px 0 10px 0;
}
.sixth-sector-left h2 {
  font-weight: lighter;
}
.sixth-sector-left h3 {
  font-weight: lighter;
}
.sixth-sector-left-icons {
  display: flex;
  justify-content: space-evenly;
}
.sixth-sector-left-icons ion-icon{
  font-size: 60px;
}
.fb, .yt, .ig {
  visibility: visible;
  transition: 0.25s;
  user-select: none;
  /* pointer-events: none; */
}
.fb:hover {
  color:blue;
}
.ig:hover {
  color:chocolate
}
.yt:hover {
  color:red;
}
</style>
