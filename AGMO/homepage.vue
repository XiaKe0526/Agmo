<template> 
  <div> 
    <Navbar /> 
 
    <div class="wrapper"> 
      <div class="image"> 
        <img src="/images/intro.png" alt="Intro Image" style="width: 100%; height: 650px;" /> 
      </div> 
      <div class="content"> 
        <h1>AGMO GROUP</h1> 
        <p>We are a digital solutions and application development specialist. Our solutions involve digitalising our customers’ business operations through the development of mobile and web applications as well as provision of digital platform-based services.</p> 
      </div> 
    </div> 
 
    <div class="about"> 
      <div class="box"> 
        <hr/> 
        <h3>WHAT WE DO</h3> 
      </div> 
      <div class="box"> 
        <p>We are a digital solutions and application development specialist. Our solutions involve digitalising our customers’ business operations through the development of mobile and web applications as well as provision of digital platform-based services. 
          <span style="color: rgb(81, 191, 246); text-decoration: none;"> 
            <a href="#">Know More About Us</a> 
          </span> 
        </p> 
      </div> 
    </div> 
 
    <div class="counter-up"> 
      <div class="title-progress"> 
        <hr /> 
        <h2>We Always Make Progress</h2> 
      </div> 
 
      <div class="content-progress"> 
        <div class="box"> 
          <div class="counter">130</div> 
          <div class="text">Employees</div> 
        </div> 
        <div class="box"> 
          <div class="counter">100</div> 
          <div class="text">Employees</div> 
        </div> 
        <div class="box"> 
          <div class="counter">8</div> 
          <div class="text">Awards</div> 
        </div> 
      </div> 
    </div> 
 
    <div class="vision-mission"> 
      <div class="vi-mi"> 
        <img src="/images/vision.png" alt="Vision" /> 
        <h2>Our Vision</h2> 
        <p>To become one of the leading digital solutions provider</p> 
      </div> 
      <div class="vi-mi"> 
        <img src="/images/mission.png" alt="Mission" /> 
        <h2>Our Mission</h2> 
        <p>To make lives better with technology</p> 
      </div> 
    </div> 
 
    <div> 
      <h2>Our Business</h2> 
      <div class="business"> 
        <div class="image"> 
          <img src="/images/business.png" alt="Business" style="width: 1500px; height: 300px;" /> 
          <div class="content1"> 
            <h3>Our Group Structure</h3> 
            <p>Our Subsidiaries and Joint Venture Company</p> 
          </div> 
        </div> 
      </div> 
    </div> 
 
    <div class="wrapper"> 
      <div> 
        <img src="/images/contact.png" alt="Contact" style="width: 1500px; height: 350px;" /> 
      </div> 
 
      <div class="message"> 
        <hr /> 
        <h2>SEND US A MESSAGE</h2> 
        <p>Send us a feedback, we look forward to hearing from you.</p> 
        <p>Email address</p> 
        <p><a href="mailto:hello@agmostudio.com" style="color: rgb(81, 191, 246);">hello@agmostudio.com</a></p> 
        <p><a href="mailto:ir@agmostudio.com" style="color: rgb(81, 191, 246);">ir@agmostudio.com</a></p> 
        <p>Give Us A Call</p> 
        <p style="color: rgb(81, 191, 246);">03-7664 8515</p> 
        <p>Our Company Address</p> 
        <p style="color: rgb(81, 191, 246);">Level 38, MYEG Tower, Empire City Damansara, Jalan PJU 8, Damansara Perdana, 47820 Petaling Jaya, Selangor, Malaysia.</p> 
      </div> 
    </div> 
 
    <iframe 
      src="https://www.google.com/maps/embed?pb=..." 
      width="1500" 
      height="600" 
      style="border:0;" 
      allowfullscreen="" 
      loading="lazy" 
    ></iframe> 
 
    <footer> 
      <div class="footer"> 
        <!-- Footer content here --> 
      </div> 
    </footer> 
  </div> 
</template> 
 
<script> 
import Navbar from '~/components/Navbar.vue' 
 
export default { 
  components: { 
    Navbar, 
  }, 
} 
</script> 
 
<style scoped> 
/* Add your styles here */ 
</style>
