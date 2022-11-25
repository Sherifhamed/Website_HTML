# Website_HTML
This website was a part of a graduation project for illustrating the final result analysis of solid waste management using GIS techniques.
<!DOCTYPE html>
<!-- Auther: Sherif Hamed -->
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Solid Waste Management</title>
    <!-- Main Css File  -->
    <link rel="stylesheet" href="style.css" />
    <!-- Normalize: make all websites act the same -->
    <link rel="stylesheet" href="normalize.css" />
    <!-- Add the css file for font icons dealing'Font Aweosome' -->
    <link rel="stylesheet" href="./all.min.css" />
    <!-- Choose the font from Google font -->
    <link rel="stylesheet" href="
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Work+Sans:ital,wght@0,200;0,300;0,500;0,700;0,800;1,400;1,500&display=swap"
      rel="stylesheet"
    />
  </head>
  <body>
    <!-- Start Header -->
    <div class="header">
      <div class="container">
        <header class="item">
          <a href="#Home"><img class="logo" src="logo2.png" alt="" /></a>

          <li><a href="#Home">Home</a></li>
          <li><a href="#Services">Services</a></li>
          <li><a href="#About Us">Workflow</a></li>
          <li><a href="#vision">Vision</a></li>
          <li><a href="#Contact us">Contact us</a></li>
        </header>
      </div>
    </div>
    <!-- End Header -->
    <!-- Temp2 start -->
    <div class="landing-landing" id="Home">
      <div class="container">
        <div class="text">
          <h1>Solid Waste Management</h1>
          <p>
            The collecting, treating, and disposing of solid material that is
            discarded because it has served its purpose or is no longer useful
          </p>
          <button id="button" class="button">
            <a
              href="https://learngis2.maps.arcgis.com/apps/dashboards/af6234ef6444420d8ff18dde1a1a453b"
              target="_blank"
              >View our Dashboard Statistics</a
            >
          </button>
        </div>
        <div class="image">
          <img src="./waste_environment.jpg" alt="" />
        </div>
      </div>
      <a href="#Arrow" class="go-down">
        <i class="fas fa-angle-double-down fa-2x"></i>
      </a>
    </div>
    <!-- Temp2 end -->

    <!-- Start Main Photo -->
    <div class="landing" id="Arrow">
      <div class="intro-text">
        <!-- <h1>Solid Waste Management</h1>
        <p>
          solid-waste management, the collecting, treating, and disposing of
          solid material that is discarded because it has served its purpose or
          is no longer useful.
        </p> -->
      </div>
    </div>
    <!-- End Main Photo -->

    <!-- Start Features -->
    <!-- End Features -->

    <!-- End Features -->

    <!-- Start spatial haeding in services section -->
    <div class="services" id="Services">
      <div class="container">
        <h2 class="special-heading">Services</h2>
        <p>Our Project ran according to sequential steps</p>
        <div class="services-content">
          <div class="col">
            <!-- Start Service -->
            <div class="srv">
              <i class="fa-sharp fa-solid fa-street-view"></i>
              <div class="text">
                <a
                  href="https://storymaps.arcgis.com/stories/c887aca3501f49a6b969e96cc5c5b3f9"
                  target="_blank"
                  ><h3>1- Define study Area</h3></a
                >
                <p>
                  In this section you will know the main problem definition,
                  where the project has been done and the process of collecting
                  data
                </p>
              </div>
            </div>
            <div class="srv" id="effective">
              <i class="fa-solid fa-database"></i>
              <div class="text">
                <a
                  href="https://storymaps.arcgis.com/stories/9a98e11c9c3e4337ae72b0f431d2dd6b"
                  target="_blank"
                  ><h3>3- Effective Solutions</h3></a
                >

                <p>
                  The simplest and most efficient solution will be discussed in
                  this section which describes the final steps for solving the
                  main problem of the project
                </p>
              </div>
            </div>
            <!-- End Service -->
          </div>
          <div class="col">
            <!-- Start Services -->
            <div class="srv">
              <i class="fa-solid fa-dumpster"></i>

              <div class="text">
                <a
                  href="https://storymaps.arcgis.com/stories/3a7c634b9ea04c5497999e1874bde3a5"
                  target="_blank"
                  ><h3>2- Situation Evaluation</h3></a
                >
                <p>
                  This section will be showing the main analysis steps done in
                  the project and the insights which has been concluded
                  from these analysis
                </p>
              </div>
            </div>
            <!-- <div class="srv">
              <i class="fa-solid fa-wand-magic-sparkles"></i>

              <div class="text">
                <a href="https://www.google.com/"
                  ><h3>4- Effective Solutions</h3></a
                >
                <p>
                  Lorem ipsum dolor sit amet consectetur, adipisicing elit.
                  Excepturi eos earum unde facere, nesciunt autem sapiente nobis
                  ab mollitia asperiores similique obcaecati qui dolores quasi
                  molestias! Optio eaque eius suscipit?
                </p>
              </div>
            </div> -->
          </div>
          <div class="col">
            <div class="image image-column">
              <img src="./logo.png" alt="" />
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- End spatial haeding in services section -->
    <!-- End Service -->

    <!-- Feature Start -->
    <div class="features" id="About Us">
      <h2 class="main-title"></h2>
      <div class="container">
        <div class="box quality" id="quality">
          <div class="img-holder">
            <img src="./7-Data-Collection-Techniques.jpg" alt="" />
          </div>
          <h2>Data Collection</h2>
          <p>
            The systematic process of gathering observations, to gain first-hand
            knowledge and original insights into the problem.
          </p>
          <a
            href="https://drive.google.com/file/d/1AwTNLrG_ggZKAVacgjccR43IsKVnTyWf/view?usp=share_link"
            target="_blank"
            >More Details</a
          >
        </div>
        <div class="box time" id="time">
          <div class="img-holder">
            <img src="./Data Analysis.jpg" alt="" />
          </div>
          <h2>Data Analysis</h2>
          <p>
            The process of cleaning, transforming, and modeling data to discover
            useful information for decision-making.
          </p>
          <a
            href="https://drive.google.com/file/d/1FItpjPvDbYgXSK-0w8h1IhqG3Yq3IROV/view?usp=share_link"
            >More Details</a
          >
        </div>
        <div class="box passion" id="passion">
          <div class="img-holder">
            <img src="./Conclusion.png" alt="" />
          </div>
          <h2>Conclusion</h2>
          <p>
            The final section of the project. It summarizes the points made in
            the project and restates the in different words.
          </p>
          <a
            href="https://drive.google.com/file/d/1p8dy-_ejAk9ihg8ebCuHyUVAXSRM4L7S/view"
            target="_blank"
            >More Details</a
          >
        </div>
      </div>
    </div>

    <!-- Feature  end -->

    <!-- video section start -->
    <div class="video" id="vision">
      <div class="container">
        <div class="text">
          <h1><i class="fa-solid fa-eye"></i> Our Vision</h1>
          <p>
            To develop a global brand that will partner with our customers and
            communities to manage & reduce waste from collection to disposal
            while recovering valuable resources and creating clean, renewable
            energy
          </p>
        </div>
        <div class="myvideo">
          <video autoplay loop muted>
            <source src="./Smart.mp4" type="video/mp4" />
          </video>
        </div>
      </div>
    </div>

    <!-- video section end -->
    <!-- Footer Start -->
    <div class="footer" id="Contact us">
      <div class="box-container">
        <div class="box">
          <h3 id="Naming">
            Solid Waste Management
            <i class="fas fa-shopping-basket"></i>
          </h3>
          <p>
            Consider your Waste, Consider your Health, Consider your Environment
          </p>
          <div class="share">
            <a
              href="https://www.facebook.com/sherif.hamed.98?mibextid=ZbWKwL "
              target="_blank"
              class="fab fa-facebook-f"
            ></a>
            <a href="#" class="fab fa-twitter"></a>
            <a href="#" class="fab fa-instagram"></a>
            <a href="#" class="fab fa-linkedin"></a>
          </div>
        </div>

        <div class="box">
          <h3>contact info</h3>

          <a href="#" class="links">
            <i class="fas fa-phone"></i> 01127564874
          </a>
          <a href="#" class="links">
            <i class="fas fa-envelope"></i> sherifhamed@sci.asu.edu.eg
          </a>
          <a href="#" class="links">
            <i class="fas fa-map-marker-alt"></i> Nasr City
          </a>
        </div>

        <div class="box">
          <h3>Quick links</h3>
          <a href="#Home" class="links">
            <i class="fas fa-arrow-right"></i> Home
          </a>
          <a href="#Services" class="links">
            <i class="fas fa-arrow-right"></i> services
          </a>
          <a href="#About Us" class="links">
            <i class="fas fa-arrow-right"></i> Workflow
          </a>
          <a href="#vision" class="links">
            <i class="fas fa-arrow-right"></i> Vision
          </a>
        </div>
      </div>
    </div>

    <!-- footer section ends -->
    <!-- Footer end -->
  </body>
  <!-- <script src="">
    document.querySelector("#Button").addEventListener;
  </script> -->
</html>
<!-- <i class="fa-solid fa-database"></i> Data Collection -->
<!-- <i class="fa-solid fa-chart-mixed"></i> Data Analysis-->
<!-- <i class="fa-regular fa-eyes"></i> Conclusion -->
<!-- <i class="fa-sharp fa-solid fa-street-view"></i> Route -->
