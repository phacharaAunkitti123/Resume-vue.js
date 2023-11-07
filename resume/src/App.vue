<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
    <div class="sidebar">
      <div class="profile-yellow">
        <img alt="profile" class="logo" src="./assets/profile.png" width="135" height="170" />
        <div class="yellow-box">
          <div class="name">PHACHARA AUNKITTI</div>
          <div class="job">Position : Database Administrator (DBA)</div>
        </div>
      </div>
      <div class="side-data">
        <div class="contact">
          <div class="tel">
            <img src="./assets/tel.jpg" alt="telephone icon">
            <div class="data">+66828187389</div>
          </div>
          <div class="mail">
            <img src="./assets/mail.jpg" alt="mail icon">
            <div class="email">phacharaaunkitti816@gmail.com</div>
          </div>
          <div class="link">
            <img src="./assets/link.jpg" alt="link icon">
            <div class="github">github.com/phacharaAunkitti123</div>
          </div>
          <div class="location">
            <img src="./assets/location.jpg" alt="location icon">
            <div class="house">33/7,Bophoi,Kanchanaburi,<br>Thailand
            </div>
          </div>

          <div class="education">
            Education
            <div class="information">
              Graduated From
              <p>Visuttharangsi School</p>
              <p>GPA 3.61 &nbsp &nbsp 2013-2019</p> <br>
              Software Engineering
              <p>Burapha University</p>
              <p>GPA 3.81 &nbsp &nbsp 2020-2023</p>
            </div>
          </div>
        </div>
      </div>
      <img src="./assets/sea.png" alt="sea_picture" width="240" height="825">

      <div>

        <div class="right-column">
          <div class="aboutme">
            <h2>About me</h2>
            <div class="yellow-box2"></div>
            <div class="info">
              I am a seasoned database administrator recognized for consistently <br> delivering successful
              projects on time and within budget. My skills <br>extend to assessing organizational requirements and
              leading
              cross-functional teams, ensuring smooth project execution and enhanced operational efficiencies. I maintain
              current knowledge of emerging technologies, and my expertise lies in database management, data modeling, and
              query optimization. Committed to providing innovative database solutions that align with business goals, I
              excel in dynamic environments and am dedicated to long-term growth and impact in <br>the field.</div>
          </div>
          <div class="history">
            <h3>History</h3>
            <div class="yellow-box2"></div>
            <h4>ClickNext Bangkok - Hardware Maintenance System</h4>
            <div class="info2">
              At ClickNext Bangkok, I collaborated with a talented team of nine members on the Hardware Maintenance System
              project. Using PHP (Laravel Framework), SQL, HTML, and CSS, we developed a robust system with efficient
              backend functionalities and user-friendly front-end interfaces. Through continuous collaboration, code
              reviews, and debugging, we ensured a reliable and efficient system. Our successful delivery of a
              high-quality solution aligned with ClickNext Bangkok's objectives.</div>
          </div>
        </div>

      </div>
    </div>


  </header>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;700;900&display=swap');

header {
  line-height: 1.5;
  text-align: center;
}

h2 {
  position: absolute;
  text-align: left;
  font-family: 'Kanit', sans-serif;
  font-size: 40px;
  font-weight: 500;
  padding-top: 200px;
  padding-left: 30px;
}

h3 {
  position: absolute;
  text-align: left;
  font-family: 'Kanit', sans-serif;
  font-size: 40px;
  font-weight: 500;
  padding-top: 200px;
  padding-left: 30px;
}

h4 {
  position: absolute;
  text-align: left;
  font-family: 'Kanit', sans-serif;
  font-size: 16px;
  font-weight: 500;
  padding-top: 265px;
  padding-left: 30px;
}

p {
  text-align: left;
  font-family: 'Kanit', sans-serif;
  font-size: 12px;
  font-weight: 300;
  padding-top: 5px;
}

.logo {
  display: flex;
  position: absolute;
  background: #fff;
  padding: 10px;
  margin-left: 25px;
  margin-top: 35px;
}

.sea {
  position: absolute;
}

.sidebar {
  display: flex;
  text-align: center;
  border: 10px;
}

.profile-yellow {
  display: flex;
  flex-direction: row;
}

.yellow-box {
  position: absolute;
  width: 600px;
  height: 150px;
  background-color: rgba(244, 214, 68, 0.7);
  border: 0px solid #ccc;
  z-index: 2;
  margin-left: 160px;
  margin-top: 43px;
}

.yellow-box2 {
  position: absolute;
  width: 500px;
  height: 3px;
  background-color: rgba(244, 214, 68, 0.7);
  border: 0px solid #ccc;
  z-index: 2;
  margin-top: 255px;
}

.name {
  font-size: 40px;
  text-align: center;
  font-family: 'Poppins', sans-serif;
  font-weight: 900;
  margin-top: 20px;
}

.job {
  font-size: 20px;
  text-align: center;
  font-family: 'Kanit', sans-serif;
  font-weight: 300;

}

.right-column {
  display: flex;
  position: absolute;
  width: 520px;
  height: 825px;
  background-color: white;
  border: 1px solid #ccc;
  z-index: 1;
  /* Ensure the right column is above the sea background */
}

.side-data {
  display: flex;
  flex-direction: column;
}

.contact {
  display: flex;
  position: absolute;
  flex-direction: row;
  margin-top: 250px;
  margin-left: 25px;
}

.tel {
  position: absolute;
  display: flex;
  width: 23;
  height: 23;

}

.mail {
  position: absolute;
  display: flex;
  margin-top: 40px;
  width: 23;
  height: 23;
}

.link {
  position: absolute;
  display: flex;
  margin-top: 80px;
  width: 23;
  height: 23;
}

.location {
  position: absolute;
  display: flex;
  margin-top: 120px;
  width: 23;
  height: 23;
}

.data {
  position: absolute;
  color: white;
  font-size: 12px;
  padding-left: 30px;
  padding-top: 3px;
}

.email {
  position: absolute;
  color: white;
  font-size: 12px;
  padding-left: 30px;
  padding-top: 1px;
}

.github {
  position: absolute;
  color: white;
  font-size: 12px;
  padding-left: 30px;
  padding-top: 1px;
}

.house {
  position: absolute;
  color: white;
  font-size: 12px;
  padding-left: 30px;
  padding-top: 1px;
  text-align: left;
}

.education {
  color: white;
  font-size: 25px;
  font-family: 'Kanit', sans-serif;
  font-weight: 100px;
  margin-top: 200px;
}

.information {
  text-align: left;
  font-family: 'Kanit', sans-serif;
  font-size: 15px;
  font-weight: 400;
  padding-top: 8px;
}


.history {
  margin-top: 300px;
}

.info {
  font-family: 'Kanit', sans-serif;
  font-weight: 300;
  position: absolute;
  color: black;
  margin-top: 265px;
  text-align: left;
  padding-left: 30px;
}

.info2 {
  font-family: 'Kanit', sans-serif;
  font-weight: 300;
  position: absolute;
  color: black;
  margin-top: 290px;
  text-align: left;
  padding-left: 30px;
}
</style>
