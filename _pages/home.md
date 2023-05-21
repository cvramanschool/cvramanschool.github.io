---
layout: home
title: HOME
permalink: /
subtitle: 
#subtitle: <a href='#'>Affiliations</a>. Address. Contacts. Moto. Etc.

news: true  # includes a list of news items
latest_posts: false  # includes a list of the newest posts
selected_papers: false # includes a list of papers marked as "selected={true}"
social: false  # includes social icons at the bottom of the page
---


<style>
  #slideshow {
    position: relative;
    width: 100%;
    height: 0;
    padding-bottom: 56.25%; /* Aspect ratio of 16:9 for responsive height */
    overflow: hidden;
  }

  #slideshow img {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: auto;
    object-fit: cover;
  }

  #slideshow + p {
    margin-top: 20px;
  }
</style>

<div id="slideshow">
  <img src="{{ site.baseurl }}/assets/custom_images/admissions.png" width="70%" alt="Image A">
  <img src="{{ site.baseurl }}/assets/custom_images/landing_page.jpg" width="70%" alt="Image B">
  <img src="{{ site.baseurl }}/assets/custom_images/10results2023.jpg" width="70%"alt="Image B">
</div>


<script>
  var slideshow = document.querySelector("#slideshow");
  var images = slideshow.querySelectorAll("img");
  var currentImage = 0;

  function showNextImage() {
    images[currentImage].style.display = "none";
    currentImage = (currentImage + 1) % images.length;
    images[currentImage].style.display = "block";
  }

  setInterval(showNextImage, 2000); // Change the duration (in milliseconds) between each image

  // Show the first image initially
  images[currentImage].style.display = "block";
</script>

 Welcome to CV Raman school!

We are delighted to extend a warm greeting to students, parents, and visitors to our esteemed institution. CV Raman school is a place where excellence in education meets a nurturing environment, fostering the growth and development of every individual.

At our school, we believe that education is not just about imparting knowledge but also about cultivating character, critical thinking skills, and a passion for lifelong learning. Our dedicated team of highly qualified educators is committed to providing a holistic learning experience that goes beyond textbooks, encouraging students to explore, discover, and realize their full potential.

With state-of-the-art facilities and a rich curriculum, we strive to create an engaging and inclusive learning environment that caters to the unique needs and interests of each student. From the early years to higher grades, we offer a diverse range of academic programs, extracurricular activities, and support services that promote academic excellence, personal growth, and a well-rounded education.

At our school, we recognize the importance of a strong partnership between home and school. We value open communication and encourage active participation from parents and guardians, as we believe that together we can provide the best possible educational experience for our students.

We invite you to explore our website to learn more about our academic programs, faculty, facilities, and the vibrant school community we have created. Should you have any questions or require further information, please do not hesitate to reach out to us. We look forward to embarking on this educational journey with you and making a positive impact in the lives of our students.


