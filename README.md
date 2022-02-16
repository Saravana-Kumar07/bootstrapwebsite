# Web Design using Bootstrap Framework

## AIM:
To design a website using bootstrap framework.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using bootstrap grid system.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :
 ### HOME PAGE:
```
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="utf-8">
  <meta content="width=device-width, initial-scale=1.0" name="viewport">
  <title>BPRD-Website</title>
  <!-- Favicons -->
  <link href="./img/bprd.png" rel="icon">

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css?family=Open+Sans:300,300i,400,400i,600,600i,700,700i|Raleway:300,300i,400,400i,500,500i,600,600i,700,700i|Poppins:300,300i,400,400i,500,500i,600,600i,700,700i" rel="stylesheet">

  <!-- CSS File -->
  <link href="./vendor/bootstrap/css/bootstrap.min.css" rel="stylesheet">
  <link href="./vendor/bootstrap-icons/bootstrap-icons.css" rel="stylesheet">
  <link href="./vendor/boxicons/css/boxicons.min.css" rel="stylesheet">
  <link href="./vendor/glightbox/css/glightbox.min.css" rel="stylesheet">
  <link href="./vendor/swiper/swiper-bundle.min.css" rel="stylesheet">
  <link href="./css/style.css" rel="stylesheet">
</head>

<body>

  <!-- ======= Top Bar ======= -->
  <section id="topbar" class="d-flex align-items-center">
    <div class="container d-flex justify-content-center justify-content-md-between">
      <div class="contact-info d-flex align-items-center">
        <i class="bi bi-envelope-fill"></i><a href="mailto:dg.brpd.nic.in">dg.brpd.nic.in</a>
        <i class="bi bi-phone-fill phone-icon"></i>+91-11-26781312
      </div>
      <div class="social-links d-none d-md-block">
        <a href="#" class="twitter"><i class="bi bi-twitter"></i></a>
        <a href="#" class="facebook"><i class="bi bi-facebook"></i></a>
        <a href="#" class="instagram"><i class="bi bi-instagram"></i></a>
        <a href="#" class="linkedin"><i class="bi bi-linkedin"></i></i></a>
      </div>
    </div>
  </section>

  <!-- ======= Header ======= -->
  <header id="header" class="d-flex align-items-center">
    <div class="container d-flex align-items-center">
      <a href="index.html" class="logo me-auto"><img src="./img/logo.png" alt="" class="img-fluid"></a>
      <h1 class="logo me-auto" style="padding-right: 490px;"><a href="index.html">BPRD</a></h1>
      <nav id="navbar" class="navbar">
        <ul>
          <li><a class="nav-link scrollto active" href="./index.html">Home</a></li>
          <li class="dropdown"><a href="./aboutus.html"><span>About Us</span> <i class="bi bi-chevron-down"></i></a>
            <ul>
              <li><a href="./aboutus.html">Evolution of BPRD</a></li>
              <li><a href="#">Awards/Medals</a></li>
              <li><a href="#">Work Allocation</a></li>
              <li class="dropdown"><a href="#"><span>View More</span> <i class="bi bi-chevron-right"></i></a>
                <ul>
                  <li><a href="#">Organization</a></li>
                  <li><a href="#">Draft Legislation</a></li>
                  <li><a href="#">Contact Us</a></li>
                  <li><a href="#">Citizen's Corner</a></li>
                </ul>
              </li>
            </ul>
            <li class="dropdown"><a href="./spc.html"><span>SPC</span> <i class="bi bi-chevron-down"></i></a>
              <ul>
                <li><a href="./spc.html">Student Police Cadet Programme</a></li>
                <li><a href="#">SPC Web</a></li>
              </ul>
          <li><a class="nav-link scrollto " href="./index.html#portfolio">Gallery</a></li>
          <li><a class="nav-link scrollto" href="#team">Training</a></li>
          <li class="dropdown"><a href="#"><span>View More</span> <i class="bi bi-chevron-down"></i></a>
            <ul>
              <li><a href="#">Research & CA</a></li>
              <li><a href="#">Modernization</a></li>
              <li><a href="#">NPM</a></li>
              <li><a href="#">SPD</a></li>
              <li><a href="#">Admin</a></li>
              <li><a href="#">SP Conf. & Police Expo</a></li>
              <li><a href="#">Publication/ Reports</a></li>
              <li><a href="#">DOPO</a></li>
            </ul>
          </li>
          <li><a class="getstarted scrollto" href="./index.html#contact">Contact</a></li>
        </ul>
        <i class="bi bi-list mobile-nav-toggle"></i>
      </nav><!-- .navbar -->

    </div>
  </header><!-- End Header -->

  <!-- ======= Hero Section ======= -->
  <section id="hero" style="height:65vh;">
         <img class="carousel-item active" src="./img/BPRDSlider1.jpg">
  </section>

  <!-- End Hero -->

  <main id="main">

    <!-- ======= What's New ======= -->
    <section id="featured-services" class="featured-services section-bg">
      <div class="container" style="padding-top: 30px;">
        <h3 class="bi bi-laptop" style="text-align: center;">What's New</h3>
        <div class="row no-gutters" style="padding-top: 30px;">
          <div class="col-lg-4 col-md-6">
            <div class="icon-box">
              <h4 class="title"><a href="">Internship - 17/01 to 28/02 2022</a></h4>
              <p class="description">Invitation of application for the paid Internship Programme at BPR&D for the year 2022-23</p>
            </div>
          </div>
          <div class="col-lg-4 col-md-6">
            <div class="icon-box">
              <h4 class="title"><a href="">Bureau Darpan - 05/0/ to 31/03 2022</a></h4>
              <p class="description">	Directory of Prison Officials in India 2021</p>
            </div>
          </div>
          <div class="col-lg-4 col-md-6">
            <div class="icon-box">
              <h4 class="title"><a href="">Webinar - 04/01/2022 to 31/12/2024</a></h4>
              <p class="description">Proceedings of the Webinar on Woman Safety with Sensitivity</p>
            </div>
          </div>
          <p style="text-align: center;"><a href="">View Old Announcement Here</a></p>
        </div>

      </div>
    </section><!-- End What's New Section -->

    <!-- ======= News & Events Section ======= -->
    <section id="why-us" class="why-us">
      <div class="container">

        <div class="row no-gutters">
          <h2 class="bi bi-chevron-right" style="text-align: center; padding-top: 20px;">News & Events</h2>
          <div class="col-lg-4 col-md-6 content-item">
            <span>01</span>
            <h4>Internship</h4>
            <p>Invitation of application for the paid Internship Programme at BPR&D for the year 2022-23. Last date: 28/02/2022</p>
            <p><a href="https://bprd.nic.in/WriteReadData/News/Internship.pdf">Apply Here</a></p>
          </div>

          <div class="col-lg-4 col-md-6 content-item">
            <span>02</span>
            <h4>Bureau Darpan</h4>
            <p>From : 05/01/2022 To: 31/03/2022</p>
            <p><a href="https://bprd.nic.in/WriteReadData/News/BureauDarpan.pdf">View PDF here</a></p>
          </div>

          <div class="col-lg-4 col-md-6 content-item">
            <span>03</span>
            <h4>Adv of PGVPant 2021-22</h4>
            <p>	पंडित गोविंद वल्लभ पंत पुरस्कार योजना वर्ष 2021-22 का विज्ञापन।. From : 18/11/2021 To: 31/03/2022</p>
            <p><a href="https://bprd.nic.in/WriteReadData/News/Adv%20of%20PGVPant%202021-22.pdf">View PDF here</a></p>
          </div>

          <div class="col-lg-4 col-md-6 content-item">
            <span>04</span>
            <h4>Police Aur Seva</h4>
            <p>Do Visit our Ploice Aur Seva Channel on YouTube</p>
            <p><a href="https://www.youtube.com/channel/UCGhrg_cnnGuhwXfCU16kYow/videos">See the channel here</a></p>
          </div>

          <div class="col-lg-4 col-md-6 content-item">
            <span>05</span>
            <h4>Yoga at Workplace</h4>
            <p>Why is yoga good for you?Yoga improves strength, balance and flexibility.Slow movements and deep breathing increase blood flow and warm up muscles, while holding a pose can build strength.</p>
            <p><a href="https://bprd.nic.in/WhatsNews_Description.aspx?News_id=10308">Watch the video here</a></p>
          </div>

          <div class="col-lg-4 col-md-6 content-item">
            <span>06</span>
            <h4>Cyber Cases Manual</h4>
            <p>Investigative Workflow Manual on Cyber Harassment Cases</p>
            <p><a href="https://bprd.nic.in/WriteReadData/News/BPRD%20Cyber%20harassment%20cases%206-3-21.pdf">See the PDF here</a></p>
          </div>

        </div>

      </div>
    </section><!-- End News & Events Section -->

    <section id="team" class="team section-bg">
      <div class="container">
        <div class="row">
          <div class="col-lg-4 col-md-6 d-flex align-items-stretch">
            <div class="member">
              <h4>PRESS RELEASES</h4><br>
              <img src="./img/press.png" alt="">
              <p style="font-weight: bolder;">1. 51st Foundation Day<br>Date - 17/01/2022</p>
              <p><a href="">View Here</a></p>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 d-flex align-items-stretch">
            <div class="member">
              <h4>TENDERS</h4><br>
              <img src="./img/tender.png" alt="">
              <p style="font-weight: bolder;">No Available Tenders Right Now</p>
              <p><a href="">Click Here To Get Updates</a></p>
            </div>
          </div>
          <div class="col-lg-4 col-md-6 d-flex align-items-stretch">
            <div class="member">
              <h4>DIRECTOR'S MESSAGE</h4><br>
              <img src="./img/dir.jfif" alt="">
              <h4>BALAJI SRIVASTAVA, IPS</h4>
              <span> Director General, BPR&D</span>
              <p>
                “Good Policing cannot be perceived without the BPR&D” 
              </p>
              <p><a href="./dir.html">Read Here</a></p>
            </div>
          </div>
          </div>
          </div>
          </section>
    <!-- ======= Gallery Section ======= -->
    <section id="portfolio" class="portfolio">
      <div class="container">

        <div class="section-title">
          <h2>GALLERY</h2>
          <p>View the latest photos and videos of BPRD here.</p>
        </div>

        <div class="row">
          <div class="col-lg-12 d-flex justify-content-center">
            <ul id="portfolio-flters">
              <li data-filter="*" class="filter-active">All</li>
              <li data-filter=".filter-app">PHOTOS</li>
              <li data-filter=".filter-card">VIDEOS</li>
            </ul>
          </div>
        </div>

        <div class="row portfolio-container">

          <div class="col-lg-4 col-md-6 portfolio-item filter-app">
            <div class="portfolio-wrap">
              <img src="./img/gallery/gallery1.jpg" class="img-fluid" alt="">
              <div class="portfolio-info">
                <h4>National Conference</h4>
                <p>on Criminal Activites and Radicalization in Jails.</p>
              </div>
            </div>
          </div>

          <div class="col-lg-4 col-md-6 portfolio-item filter-app">
            <div class="portfolio-wrap">
              <img src="./img/gallery/foundationday.jfif" class="img-fluid" alt="">
              <div class="portfolio-info">
                <h4>Foundation Day</h4>
                <p>51st Foundation Day </p>
              </div>
            </div>
          </div>

          <div class="col-lg-4 col-md-6 portfolio-item filter-card">
            <div class="portfolio-wrap">
              <img src="./img/gallery/spc.jpg" class="img-fluid" alt="">
              <div class="portfolio-info">
                <h4>Student Police Cadet</h4>
                <p>SPC Theme Song</p>
              </div>
            </div>
          </div>

          <div class="col-lg-4 col-md-6 portfolio-item filter-app">
            <div class="portfolio-wrap">
              <img src="./img/gallery/ips.png" class="img-fluid" alt="">
              <div class="portfolio-info">
                <h4>Attachment of IPS Officers</h4>
                <p>10th November 2021</p>
              </div>
            </div>
          </div>

          <div class="col-lg-4 col-md-6 portfolio-item filter-card">
            <div class="portfolio-wrap">
              <img src="./img/gallery/expo.jpg" class="img-fluid" alt="">
              <div class="portfolio-info">
                <h4>Police Expo</h4>
                <p>Hosted on 2018</p>
              </div>
            </div>
          </div>

          <div class="col-lg-4 col-md-6 portfolio-item filter-app">
            <div class="portfolio-wrap">
              <img src="./img/gallery/conf.png" class="img-fluid" alt="">
              <div class="portfolio-info">
                <h4>Conference on Micro Mission</h4>
                <p>3rd National Conference on Micro Mission</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section><!-- Gallery Section -->

  
    <!-- ======= Contact Section ======= -->
    <section id="contact" class="contact">
      <div class="container">

        <div class="section-title">
          <h2>Contact Us & Get In Touch</h2>
        </div>

        <div class="row">

          <div class="col-lg-5 d-flex align-items-stretch">
            <div class="info">
              <div class="address">
                <i class="bi bi-geo-alt"></i>
                <h4>Location:</h4>
                <p>Bureau of Police Research and Development
                  Ministry of Home Affairs,
                  NH-8, Mahipalpur
                  New Delhi (India)</p>
              </div>

              <div class="email">
                <i class="bi bi-envelope"></i>
                <h4>Email:</h4>
                <p>DG Office: dg.brpd.nic.in</p> 
                <p>ADG Office: adg.brpd.nic.in</p>                 
              </div>

              <div class="phone">
                <i class="bi bi-phone"></i>
                <h4>Call:</h4>
                <p>DG Office: +91-11-26781312</p> 
                <p>ADG Office: +91-11-2678</p>
              </div>
            </div>

          </div>

          <div class="col-lg-7 mt-5 mt-lg-0 d-flex align-items-stretch">
            <form action="forms/contact.php" method="post" role="form" class="php-email-form">
              <div class="row">
                <div class="form-group col-md-6">
                  <label for="name">Your Name</label>
                  <input type="text" name="name" class="form-control" id="name" required>
                </div>
                <div class="form-group col-md-6 mt-3 mt-md-0">
                  <label for="name">Your Email</label>
                  <input type="email" class="form-control" name="email" id="email" required>
                </div>
              </div>
              <div class="form-group mt-3">
                <label for="name">Subject</label>
                <input type="text" class="form-control" name="subject" id="subject" required>
              </div>
              <div class="form-group mt-3">
                <label for="name">Message</label>
                <textarea class="form-control" name="message" rows="10" required></textarea>
              </div>
              <div class="my-3">
                <div class="loading">Loading</div>
                <div class="error-message"></div>
                <div class="sent-message">Your message has been sent. Thank you!</div>
              </div>
              <div class="text-center"><button type="submit">Send Message</button></div>
            </form>
          </div>

        </div>

      </div>
    </section><!-- End Contact Section -->

  </main><!-- End #main -->

  <!-- ======= Footer ======= -->
  <footer id="footer">
    <div class="container">
      <h3>BPRD</h3>
      <p>Bureau of Police Research and Development <br> A part of Ministry Of Home</p>
      <p>This website belongs to "Bureau of Police Research and Development", Ministry of Home Affairs, Govt. Of India Site Designed, Developed and Hosted by National Informatics Centre</p>
      <div class="social-links">
        <a href="#" class="twitter"><i class="bx bxl-twitter"></i></a>
        <a href="#" class="facebook"><i class="bx bxl-facebook"></i></a>
        <a href="#" class="instagram"><i class="bx bxl-instagram"></i></a>
        <a href="#" class="linkedin"><i class="bx bxl-linkedin"></i></a>
      </div>
      <div class="copyright">
        &copy; Copyright <strong><span>BPRD</span></strong>. All Rights Reserved
      </div>
      <div class="credits">
        Designed by <a href="https://bootstrapmade.com/">SARAVANA KUMAR.S</a>
      </div>
    </div>
  </footer><!-- End Footer -->

    <!-- Vendor JS Files -->

  <!-- Template Main JS File -->
  <script src="./js/main.js"></script>
</body>
</html>
```
### SPC PAGE:
```
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="utf-8">
  <meta content="width=device-width, initial-scale=1.0" name="viewport">
  <title>BPRD-Website</title>
  <!-- Favicons -->
  <link href="./img/bprd.png" rel="icon">

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css?family=Open+Sans:300,300i,400,400i,600,600i,700,700i|Raleway:300,300i,400,400i,500,500i,600,600i,700,700i|Poppins:300,300i,400,400i,500,500i,600,600i,700,700i" rel="stylesheet">

  <!-- CSS File -->
  <link href="./vendor/bootstrap/css/bootstrap.min.css" rel="stylesheet">
  <link href="./vendor/bootstrap-icons/bootstrap-icons.css" rel="stylesheet">
  <link href="./vendor/boxicons/css/boxicons.min.css" rel="stylesheet">
  <link href="./vendor/glightbox/css/glightbox.min.css" rel="stylesheet">
  <link href="./vendor/swiper/swiper-bundle.min.css" rel="stylesheet">
  <link href="./css/style.css" rel="stylesheet">
</head>

<body>

  <!-- ======= Top Bar ======= -->
  <section id="topbar" class="d-flex align-items-center">
    <div class="container d-flex justify-content-center justify-content-md-between">
      <div class="contact-info d-flex align-items-center">
        <i class="bi bi-envelope-fill"></i><a href="mailto:dg.brpd.nic.in">dg.brpd.nic.in</a>
        <i class="bi bi-phone-fill phone-icon"></i>+91-11-26781312
      </div>
      <div class="social-links d-none d-md-block">
        <a href="#" class="twitter"><i class="bi bi-twitter"></i></a>
        <a href="#" class="facebook"><i class="bi bi-facebook"></i></a>
        <a href="#" class="instagram"><i class="bi bi-instagram"></i></a>
        <a href="#" class="linkedin"><i class="bi bi-linkedin"></i></i></a>
      </div>
    </div>
  </section>

  <!-- ======= Header ======= -->  <!-- ======= Header ======= -->
  <header id="header" class="d-flex align-items-center">
    <div class="container d-flex align-items-center">
      <a href="index.html" class="logo me-auto"><img src="./img/logo.png" alt="" class="img-fluid"></a>
      <h1 class="logo me-auto" style="padding-right: 490px;"><a href="index.html">BPRD</a></h1>
      <nav id="navbar" class="navbar">
        <ul>
          <li><a class="nav-link scrollto active" href="./index.html">Home</a></li>
          <li class="dropdown"><a href="./aboutus.html"><span>About Us</span> <i class="bi bi-chevron-down"></i></a>
            <ul>
              <li><a href="./aboutus.html">Evolution of BPRD</a></li>
              <li><a href="#">Awards/Medals</a></li>
              <li><a href="#">Work Allocation</a></li>
              <li class="dropdown"><a href="#"><span>View More</span> <i class="bi bi-chevron-right"></i></a>
                <ul>
                  <li><a href="#">Organization</a></li>
                  <li><a href="#">Draft Legislation</a></li>
                  <li><a href="#">Contact Us</a></li>
                  <li><a href="#">Citizen's Corner</a></li>
                </ul>
              </li>
            </ul>
            <li class="dropdown"><a href="./spc.html"><span>SPC</span> <i class="bi bi-chevron-down"></i></a>
              <ul>
                <li><a href="./spc.html">Student Police Cadet Programme</a></li>
                <li><a href="#">SPC Web</a></li>
              </ul>
          <li><a class="nav-link scrollto " href="./index.html#portfolio">Gallery</a></li>
          <li><a class="nav-link scrollto" href="#team">Training</a></li>
          <li class="dropdown"><a href="#"><span>View More</span> <i class="bi bi-chevron-down"></i></a>
            <ul>
              <li><a href="#">Research & CA</a></li>
              <li><a href="#">Modernization</a></li>
              <li><a href="#">NPM</a></li>
              <li><a href="#">SPD</a></li>
              <li><a href="#">Admin</a></li>
              <li><a href="#">SP Conf. & Police Expo</a></li>
              <li><a href="#">Publication/ Reports</a></li>
              <li><a href="#">DOPO</a></li>
            </ul>
          </li>
          <li><a class="getstarted scrollto" href="./index.html#contact">Contact</a></li>
        </ul>
        <i class="bi bi-list mobile-nav-toggle"></i>
      </nav><!-- .navbar -->

    </div>
  </header><!-- End Header -->

  <section id="services" class="services">
    <div class="container">

      <div class="section-title">
        <h2>SPC- STUDENT CADET PROGRAMME</h2>
      </div>

      <div class="row">
        <div class="col-lg-3 order-1 order-lg-1">
          <div class="list-group">
            <button type="button" class="list-group-item list-group-item-action active">SPC Programme</button>
            <button type="button" class="list-group-item list-group-item-action">SPC Web</button>
          </div>
        </div>
        <div class="col-lg-9 pt-4 pt-lg-0 order-2 order-lg-1 content">
          <h3>SPC Programme</h3>
          <p class="fst-italic">
              <dl>
                <br>The Student Police Cadet (SPC) Programme was launched nationallyon the 21st July, 2018 by Shri Rajnath Singh, former Union Home Minister. About6,000 Cadets from different States and UTs participated in the launchprogramme. The Student Police Cadet Programme seeks to build a bridge betweenthe Police and the community by inculcating values and ethics in the schoolgoing students through indoor and outdoor classes and activities.
                <br><br>The Student Police Cadet Programme is a two years long capacitybuilding programme for the student of 8th and 9th standard. It aims to evolvestudents as responsible and capable citizens of our democratic society. Theprogramme is successfully running in more than 11,000 schoolsand 7,18,638 number of students are enrolled as SPC Cadets. BPR&D hasdeveloped the curriculum for Student Police Cadet Programme and it has beendesigned in a way to keep the learning interactive and interesting. BPR&D,through 05 workshops has trained 179 Master Trainers from States and UTs.</dd>
                <dt><br>The Vision</dt>
                <br>To nurture the school going childrento be law abiding community to contribute towards the realization of a NewIndia. 
                <dt><br>The Mission</dt>
                <br>To help character building of futurecitizens,through indoor as well as outdoor activities by providing anenvironment where children of different strata of society will be empowered todetermine the direction for their future and also that of the society.
                <dt><br>The Motto</dt>
                <br>The motto is – "Empathy, Discipline and Integrity".
              </dl>
          </p>
        </div>
      </div>

    </div>
  </section>

  <!-- ======= Footer ======= -->
  <footer id="footer">
    <div class="container">
      <h3>BPRD</h3>
      <p>Bureau of Police Research and Development <br> A part of Ministry Of Home</p>
      <p>This website belongs to "Bureau of Police Research and Development", Ministry of Home Affairs, Govt. Of India Site Designed, Developed and Hosted by National Informatics Centre</p>
      <div class="social-links">
        <a href="#" class="twitter"><i class="bx bxl-twitter"></i></a>
        <a href="#" class="facebook"><i class="bx bxl-facebook"></i></a>
        <a href="#" class="instagram"><i class="bx bxl-instagram"></i></a>
        <a href="#" class="linkedin"><i class="bx bxl-linkedin"></i></a>
      </div>
      <div class="copyright">
        &copy; Copyright <strong><span>BPRD</span></strong>. All Rights Reserved
      </div>
      <div class="credits">
        Designed by <a href="https://bootstrapmade.com/">SARAVANA KUMAR.S</a>
      </div>
    </div>
  </footer><!-- End Footer -->

  <!-- Template Main JS File -->
  <script src="./js/main.js"></script>
</body>
</html>
```
ABOUT US:
```
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="utf-8">
  <meta content="width=device-width, initial-scale=1.0" name="viewport">
  <title>BPRD-Website</title>
  <!-- Favicons -->
  <link href="./img/bprd.png" rel="icon">

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css?family=Open+Sans:300,300i,400,400i,600,600i,700,700i|Raleway:300,300i,400,400i,500,500i,600,600i,700,700i|Poppins:300,300i,400,400i,500,500i,600,600i,700,700i" rel="stylesheet">

  <!-- CSS File -->
  <link href="./vendor/bootstrap/css/bootstrap.min.css" rel="stylesheet">
  <link href="./vendor/bootstrap-icons/bootstrap-icons.css" rel="stylesheet">
  <link href="./vendor/boxicons/css/boxicons.min.css" rel="stylesheet">
  <link href="./vendor/glightbox/css/glightbox.min.css" rel="stylesheet">
  <link href="./vendor/swiper/swiper-bundle.min.css" rel="stylesheet">
  <link href="./css/style.css" rel="stylesheet">
</head>

<body>

  <!-- ======= Top Bar ======= -->
  <section id="topbar" class="d-flex align-items-center">
    <div class="container d-flex justify-content-center justify-content-md-between">
      <div class="contact-info d-flex align-items-center">
        <i class="bi bi-envelope-fill"></i><a href="mailto:dg.brpd.nic.in">dg.brpd.nic.in</a>
        <i class="bi bi-phone-fill phone-icon"></i>+91-11-26781312
      </div>
      <div class="social-links d-none d-md-block">
        <a href="#" class="twitter"><i class="bi bi-twitter"></i></a>
        <a href="#" class="facebook"><i class="bi bi-facebook"></i></a>
        <a href="#" class="instagram"><i class="bi bi-instagram"></i></a>
        <a href="#" class="linkedin"><i class="bi bi-linkedin"></i></i></a>
      </div>
    </div>
  </section>

  <!-- ======= Header ======= -->
  <header id="header" class="d-flex align-items-center">
    <div class="container d-flex align-items-center">
      <a href="index.html" class="logo me-auto"><img src="./img/logo.png" alt="" class="img-fluid"></a>
      <h1 class="logo me-auto" style="padding-right: 490px;"><a href="index.html">BPRD</a></h1>
      <nav id="navbar" class="navbar">
        <ul>
          <li><a class="nav-link scrollto active" href="./index.html">Home</a></li>
          <li class="dropdown"><a href="./aboutus.html"><span>About Us</span> <i class="bi bi-chevron-down"></i></a>
            <ul>
              <li><a href="./aboutus.html">Evolution of BPRD</a></li>
              <li><a href="#">Awards/Medals</a></li>
              <li><a href="#">Work Allocation</a></li>
              <li class="dropdown"><a href="#"><span>View More</span> <i class="bi bi-chevron-right"></i></a>
                <ul>
                  <li><a href="#">Organization</a></li>
                  <li><a href="#">Draft Legislation</a></li>
                  <li><a href="#">Contact Us</a></li>
                  <li><a href="#">Citizen's Corner</a></li>
                </ul>
              </li>
            </ul>
            <li class="dropdown"><a href="./spc.html"><span>SPC</span> <i class="bi bi-chevron-down"></i></a>
              <ul>
                <li><a href="./spc.html">Student Police Cadet Programme</a></li>
                <li><a href="#">SPC Web</a></li>
              </ul>
          <li><a class="nav-link scrollto " href="./index.html#portfolio">Gallery</a></li>
          <li><a class="nav-link scrollto" href="#team">Training</a></li>
          <li class="dropdown"><a href="#"><span>View More</span> <i class="bi bi-chevron-down"></i></a>
            <ul>
              <li><a href="#">Research & CA</a></li>
              <li><a href="#">Modernization</a></li>
              <li><a href="#">NPM</a></li>
              <li><a href="#">SPD</a></li>
              <li><a href="#">Admin</a></li>
              <li><a href="#">SP Conf. & Police Expo</a></li>
              <li><a href="#">Publication/ Reports</a></li>
              <li><a href="#">DOPO</a></li>
            </ul>
          </li>
          <li><a class="getstarted scrollto" href="./index.html#contact">Contact</a></li>
        </ul>
        <i class="bi bi-list mobile-nav-toggle"></i>
      </nav><!-- .navbar -->
    </div>
  </header><!-- End Header -->
  
  <!-- ======= About Us Section ======= -->
<section id="about" class="about">
    <div class="container">

      <div class="section-title">
        <h2>About Us</h2>
      </div>

      <div class="row">
        <div class="col-lg-3 order-1 order-lg-1">
          <div class="list-group">
            <button type="button" class="list-group-item list-group-item-action active">Evolution of BPRD</button>
            <button type="button" class="list-group-item list-group-item-action">Awards/Medals</button>
            <button type="button" class="list-group-item list-group-item-action">Work Allocation</button>
            <button type="button" class="list-group-item list-group-item-action">Organization</button>
            <button type="button" class="list-group-item list-group-item-action">Draft Lefislation</button>
            <button type="button" class="list-group-item list-group-item-action">Contact Us</button>
            <button type="button" class="list-group-item list-group-item-action">Citizen's Corner</button>
          </div>
        </div>
        <div class="col-lg-9 pt-4 pt-lg-0 order-2 order-lg-1 content">
          <h3>Evolution of BPRD</h3>
          <p class="fst-italic">
              <dl>
                <dt>CREATION</dt>
                <br>1.The Government of India vied Resolution No.8/136/68-P.I (Pers.I) dated 28.08.1970 formally established the Bureau of Police Research and Development (BPR&D), under the Ministry of Home Affairs giving a new orientation to then existing Police Research and Advisory Council (1966) for the following reasons and with the primary objective of modernization of police force:
                <dd>1.1. To take direct and active interest in the issues</dd>
                <dd>1.2. To promote a speedy and systematic study of the police problems,</dd>
                <dd>1.3. To apply science and technology in the methods and techniques used by police.</dd>
                In addition and as a secondary, the Resolution mandated an advisory role also for the Bureau.<br>
                2. The Bureau was established with the following two divisions initially with a well laid out charter of duties
                <dd>2.1. Research, Statistics and Publication</dd>
                <dd>2.2. Development</dd>
                <dd>2.3. Training is a vital and growing requirement to improve the competency of police forces in the country. The Gore-Committee (1971) set up by the Government of India studied the training aspects of police and gave several recommendations. The government of India in accepting its recommendations created a Training Division (1973) in addition to the two divisions already existing to function under the Bureau.</dd>
                <dd>2.4. The forensic science services uncompromising & Geese under the Development Division grew over a period and a separate Directorate of Forensic Sciences under the BPR&D came into existence in 1983.</dd>
                <dd>2.5. Further in 1995 Government of India decided to entrust issues relating to Correctional Administration Work to the BPR&D so that problems relating to prisons and implementation of deemed prison reforms can be taken up by the Bureau in a cohesive manner. This set up is operating out of the existing manpower resources.</dd>
                <dd>2.6. During the year 2008, the Government of India further decided to create National Police Mission under the administrative control of BPR&D to transform the police forces in the country into effective instrument for maintenance of internal security and facing the challenges in future, by equipping them with the necessary material, intellectual and organizational resources.</dd>
                <dt>SEPARATION</dt>
                <br>1.Though the Institute of Criminology and Forensic Science (ICFS) was established under the overall supervision and guidance of BPR&D as part of the same exercise, it was allowed to function as a separate entity in 1976; since the ultimate objective of setting up the Institute was to develop a full-fledged academic institution for furthering studies in Criminology and forensic science. The same which has been re-christened in the year 1991 is now functioning as Lok Nayak Jai Prakash Narayan (LNJN), National Institute of Criminology and Forensic Science from 1982. The institute provides training courses for officers of the criminal justice system in the two subjects i.e. Criminology and Forensic Science and carries out research.
                <dd>2. Growth dynamics took over and the need to specialize in each area arose. The National Police Commission (1977) also recommended certain measures requiring implementation. Simultaneously, technological innovations particularly computers held promises of support to many areas of crime control and crime detection besides processing statistical data for the purpose of analysis. The Government of India, therefore, decided to establish a National Crime Records Bureau in 1986 build another Resolution and entrusted statistics and publications work of the Research Division to the newly constituted Bureau along with the plans for their computerization.</dd>
                <dd>3. In an identical move brought about by compulsions of growth, the Government of India decided to give an independent status to the Forensic Science Division by creating a Forensic Science Directorate having an autonomous status under the direct control of the Ministry of Home Affairs.</dd>
              </dl>
          </p>
        </div>
      </div>
    </div>
  </section><!-- End About Us Section -->

  <!-- ======= Footer ======= -->
  <footer id="footer">
    <div class="container">
      <h3>BPRD</h3>
      <p>Bureau of Police Research and Development <br> A part of Ministry Of Home</p>
      <p>This website belongs to "Bureau of Police Research and Development", Ministry of Home Affairs, Govt. Of India Site Designed, Developed and Hosted by National Informatics Centre</p>
      <div class="social-links">
        <a href="#" class="twitter"><i class="bx bxl-twitter"></i></a>
        <a href="#" class="facebook"><i class="bx bxl-facebook"></i></a>
        <a href="#" class="instagram"><i class="bx bxl-instagram"></i></a>
        <a href="#" class="linkedin"><i class="bx bxl-linkedin"></i></a>
      </div>
      <div class="copyright">
        &copy; Copyright <strong><span>BPRD</span></strong>. All Rights Reserved
      </div>
      <div class="credits">
        Designed by <a href="https://bootstrapmade.com/">Saravana kumar.s</a>
      </div>
    </div>
  </footer><!-- End Footer -->

  <!-- Template Main JS File -->
  <script src="./js/main.js"></script>
</body>
</html>

```
### CSS:
```
/*--------------------------------------------------------------
# General
--------------------------------------------------------------*/
body {
  font-family: "Open Sans", sans-serif;
  color: #444444;
}

a {
  text-decoration: none;
  color: #5c7cb8;
}

a:hover {
  color: #5c7cb8;
  text-decoration: none;
}

h1, h2, h3, h4, h5, h6 {
  font-family: "Raleway", sans-serif;
}

/*--------------------------------------------------------------
# Top Bar
--------------------------------------------------------------*/
#topbar {
  background: #fbfbfb;
  font-size: 15px;
  height: 40px;
  padding: 0;
}
#topbar .contact-info a {
  line-height: 0;
  color: #444444;
  transition: 0.3s;
}
#topbar .contact-info a:hover {
  color: #5c7cb8;
}
#topbar .contact-info i {
  color: #5c7cb8;
  line-height: 0;
  margin-right: 5px;
}
#topbar .contact-info .phone-icon {
  margin-left: 15px;
}
#topbar .social-links a {
  color: #6f6f6f;
  padding: 4px 12px;
  display: inline-block;
  line-height: 1px;
  transition: 0.3s;
}
#topbar .social-links a:hover {
  color: #5c7cb8;
}
/*--------------------------------------------------------------
# Header
--------------------------------------------------------------*/
#header {
  background: #fff;
  transition: all 0.5s;
  z-index: 997;
  height: 70px;
}
#header.header-scrolled {
  box-shadow: 0px 2px 15px rgba(0, 0, 0, 0.1);
}
#header .logo {
  font-size: 30px;
  margin: 0;
  padding: 0;
  line-height: 1;
  font-weight: 700;
  letter-spacing: 1px;
  text-transform: uppercase;
}
#header .logo a {
  color: #395bc9;
}
#header .logo img {
  max-height: 40px;
}

.scrolled-offset {
  margin-top: 70px;
}

/*--------------------------------------------------------------
# Navigation Menu
--------------------------------------------------------------*/
/**
* Desktop Navigation 
*/
.navbar {
  padding: 0;
}
.navbar ul {
  margin: 0;
  padding: 0;
  display: flex;
  list-style: none;
  align-items: center;
}
.navbar li {
  position: relative;
}
.navbar a, .navbar a:focus {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 10px 0 10px 30px;
  font-size: 15px;
  color: #222222;
  white-space: nowrap;
  transition: 0.3s;
}
.navbar a i, .navbar a:focus i {
  font-size: 12px;
  line-height: 0;
  margin-left: 5px;
}
.navbar a:hover, .navbar .active, .navbar .active:focus, .navbar li:hover > a {
  color: #5c7cb8;
}
.navbar .getstarted, .navbar .getstarted:focus {
  color: #5c7cb8;
  padding: 8px 25px;
  margin-left: 30px;
  border-radius: 4px;
  border: 2px solid #5c7cb8;
  transition: 0.3s;
  font-size: 14px;
}
.navbar .getstarted:hover, .navbar .getstarted:focus:hover {
  background: #5c7cb8;
  color: #fff;
}
.navbar .dropdown ul {
  display: block;
  position: absolute;
  left: 14px;
  top: calc(100% + 30px);
  margin: 0;
  padding: 10px 0;
  z-index: 99;
  opacity: 0;
  visibility: hidden;
  background: #fff;
  box-shadow: 0px 0px 30px rgba(127, 137, 161, 0.25);
  transition: 0.3s;
}
.navbar .dropdown ul li {
  min-width: 200px;
}
.navbar .dropdown ul a {
  padding: 10px 20px;
  text-transform: none;
}
.navbar .dropdown ul a i {
  font-size: 12px;
}
.navbar .dropdown ul a:hover, .navbar .dropdown ul .active:hover, .navbar .dropdown ul li:hover > a {
  color: #5c7cb8;
}
.navbar .dropdown:hover > ul {
  opacity: 1;
  top: 100%;
  visibility: visible;
}
.navbar .dropdown .dropdown ul {
  top: 0;
  left: calc(100% - 30px);
  visibility: hidden;
}
.navbar .dropdown .dropdown:hover > ul {
  opacity: 1;
  top: 0;
  left: 100%;
  visibility: visible;
}
@media (max-width: 1366px) {
  .navbar .dropdown .dropdown ul {
    left: -90%;
  }
  .navbar .dropdown .dropdown:hover > ul {
    left: -100%;
  }
}

/**
* Mobile Navigation 
*/
.mobile-nav-toggle {
  color: #222222;
  font-size: 28px;
  cursor: pointer;
  display: none;
  line-height: 0;
  transition: 0.5s;
}
.mobile-nav-toggle.bi-x {
  color: #fff;
}

@media (max-width: 991px) {
  .mobile-nav-toggle {
    display: block;
  }

  .navbar ul {
    display: none;
  }
}
.navbar-mobile {
  position: fixed;
  overflow: hidden;
  top: 0;
  right: 0;
  left: 0;
  bottom: 0;
  background: rgba(9, 9, 9, 0.9);
  transition: 0.3s;
  z-index: 999;
}
.navbar-mobile .mobile-nav-toggle {
  position: absolute;
  top: 15px;
  right: 15px;
}
.navbar-mobile ul {
  display: block;
  position: absolute;
  top: 55px;
  right: 15px;
  bottom: 15px;
  left: 15px;
  padding: 10px 0;
  background-color: #fff;
  overflow-y: auto;
  transition: 0.3s;
}
.navbar-mobile a, .navbar-mobile a:focus {
  padding: 10px 20px;
  font-size: 15px;
  color: #222222;
}
.navbar-mobile a:hover, .navbar-mobile .active, .navbar-mobile li:hover > a {
  color: #5c7cb8;
}
.navbar-mobile .getstarted, .navbar-mobile .getstarted:focus {
  margin: 15px;
}
.navbar-mobile .dropdown ul {
  position: static;
  display: none;
  margin: 10px 20px;
  padding: 10px 0;
  z-index: 99;
  opacity: 1;
  visibility: visible;
  background: #fff;
  box-shadow: 0px 0px 30px rgba(127, 137, 161, 0.25);
}
.navbar-mobile .dropdown ul li {
  min-width: 200px;
}
.navbar-mobile .dropdown ul a {
  padding: 10px 20px;
}
.navbar-mobile .dropdown ul a i {
  font-size: 12px;
}
.navbar-mobile .dropdown ul a:hover, .navbar-mobile .dropdown ul .active:hover, .navbar-mobile .dropdown ul li:hover > a {
  color: #5cb874;
}
.navbar-mobile .dropdown > .dropdown-active {
  display: block;
}

/*--------------------------------------------------------------
# Hero Section
--------------------------------------------------------------*/
#hero {
  width: 100%;
  height: 70vh;
  background-color: rgba(9, 9, 9, 0.8);
  overflow: hidden;
  position: relative;
}
#hero .carousel, #hero .carousel-inner, #hero .carousel-item, #hero .carousel-item::before {
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  position: absolute;
  top: 0;
  right: 0;
  left: 0;
  bottom: 0;
}
#hero .carousel-item::before {
  content: "";
  background-color: rgba(45, 103, 60, 0.8);
}
#hero .carousel-container {
  display: flex;
  justify-content: center;
  align-items: center;
  position: absolute;
  bottom: 0;
  top: 0;
  left: 50px;
  right: 50px;
}
#hero .container {
  text-align: center;
}
#hero h2 {
  color: #fff;
  margin-bottom: 20px;
  font-size: 48px;
  font-weight: 700;
}
#hero p {
  -webkit-animation-delay: 0.4s;
  animation-delay: 0.4s;
  margin: 0 auto 30px auto;
  color: #fff;
}
#hero .carousel-inner .carousel-item {
  transition-property: opacity;
  background-position: center top;
}
#hero .carousel-inner .carousel-item,
#hero .carousel-inner .active.carousel-item-start,
#hero .carousel-inner .active.carousel-item-end {
  opacity: 0;
}
#hero .carousel-inner .active,
#hero .carousel-inner .carousel-item-next.carousel-item-start,
#hero .carousel-inner .carousel-item-prev.carousel-item-end {
  opacity: 1;
  transition: 0.5s;
}
#hero .carousel-control-next-icon, #hero .carousel-control-prev-icon {
  background: none;
  font-size: 30px;
  line-height: 0;
  width: auto;
  height: auto;
  background: rgba(47, 110, 55, 0.2);
  border-radius: 50px;
  transition: 0.3s;
  color: rgba(94, 192, 81, 0.5);
  width: 54px;
  height: 54px;
  display: flex;
  align-items: center;
  justify-content: center;
}
#hero .carousel-control-next-icon:hover, #hero .carousel-control-prev-icon:hover {
  background: rgba(255, 255, 255, 0.3);
  color: rgba(255, 255, 255, 0.8);
}
#hero .carousel-indicators li {
  cursor: pointer;
  background: #fff;
  overflow: hidden;
  border: 0;
  width: 12px;
  height: 12px;
  border-radius: 50px;
  opacity: 0.6;
  transition: 0.3s;
}
#hero .carousel-indicators li.active {
  opacity: 1;
  background: #5c7cb8;
}
#hero .btn-get-started {
  font-family: "Raleway", sans-serif;
  font-weight: 500;
  font-size: 14px;
  letter-spacing: 1px;
  display: inline-block;
  padding: 14px 32px;
  border-radius: 4px;
  transition: 0.5s;
  line-height: 1;
  color: #fff;
  -webkit-animation-delay: 0.8s;
  animation-delay: 0.8s;
  background: #5c7cb8;
}
#hero .btn-get-started:hover {
  background: #5c7cb8;
}
@media (max-width: 992px) {
  #hero {
    height: 100vh;
  }
  #hero .carousel-container {
    top: 66px;
  }
}
@media (max-width: 768px) {
  #hero h2 {
    font-size: 28px;
  }
}
@media (min-width: 1024px) {
  #hero .carousel-control-prev, #hero .carousel-control-next {
    width: 5%;
  }
}
@media (max-height: 500px) {
  #hero {
    height: auto;
  }
}

/*--------------------------------------------------------------
# Sections General
--------------------------------------------------------------*/
section {
  padding: 60px 0;
}

.section-bg {
  background-color: #f8fcf9;
}

.section-title {
  text-align: center;
  padding-bottom: 30px;
}
.section-title h2 {
  font-size: 32px;
  font-weight: bold;
  text-transform: uppercase;
  margin-bottom: 20px;
  padding-bottom: 20px;
  position: relative;
}
.section-title h2::before {
  content: "";
  position: absolute;
  display: block;
  width: 120px;
  height: 1px;
  background: #ddd;
  bottom: 1px;
  left: calc(50% - 60px);
}
.section-title h2::after {
  content: "";
  position: absolute;
  display: block;
  width: 40px;
  height: 3px;
  background: #5c7cb8;
  bottom: 0;
  left: calc(50% - 20px);
}
.section-title p {
  margin-bottom: 0;
  font-size: 14px;
  color: #919191;
}


/*--------------------------------------------------------------
# About Us
--------------------------------------------------------------*/
.about .content h3 {
  font-weight: 700;
  font-size: 28px;
}
.about .content ul {
  list-style: none;
  padding: 0;
}
.about .content ul li {
  padding-bottom: 10px;
}
.about .content ul i {
  font-size: 20px;
  padding-right: 4px;
  color: #5c7cb8;
}
.about .content p:last-child {
  margin-bottom: 0;
}

/*--------------------------------------------------------------
# Why Us
--------------------------------------------------------------*/
.why-us {
  padding: 0;
}
.why-us .row {
  overflow: hidden;
}
.why-us .content-item {
  padding: 40px;
  border-left: 1px solid #eee;
  border-bottom: 1px solid #eee;
  margin: -1px;
}
.why-us .content-item span {
  display: block;
  font-size: 24px;
  font-weight: 400;
  color: #5c7cb8;
}
.why-us .content-item h4 {
  font-size: 26px;
  font-weight: 300;
  padding: 0;
  margin: 20px 0;
}
.why-us .content-item p {
  color: #aaaaaa;
  font-size: 15px;
  margin: 0;
  padding: 0;
}
@media (max-width: 768px) {
  .why-us .content-item {
    padding: 40px 0;
  }
}

/*--------------------------------------------------------------
# Portfolio
--------------------------------------------------------------*/
.portfolio .portfolio-item {
  margin-bottom: 30px;
}
.portfolio #portfolio-flters {
  padding: 0;
  margin: 0 auto 20px auto;
  list-style: none;
  text-align: center;
}
.portfolio #portfolio-flters li {
  cursor: pointer;
  display: inline-block;
  padding: 8px 15px 10px 15px;
  font-size: 14px;
  font-weight: 600;
  line-height: 1;
  text-transform: uppercase;
  color: #444444;
  margin-bottom: 5px;
  transition: all 0.3s ease-in-out;
  border-radius: 3px;
}
.portfolio #portfolio-flters li:hover, .portfolio #portfolio-flters li.filter-active {
  color: #fff;
  background: #5c7cb8;
}
.portfolio #portfolio-flters li:last-child {
  margin-right: 0;
}
.portfolio .portfolio-wrap {
  transition: 0.3s;
  position: relative;
  overflow: hidden;
  z-index: 1;
  background: rgba(34, 34, 34, 0.6);
}
.portfolio .portfolio-wrap::before {
  content: "";
  background: rgba(34, 34, 34, 0.6);
  position: absolute;
  left: 0;
  right: 0;
  top: 0;
  bottom: 0;
  transition: all ease-in-out 0.3s;
  z-index: 2;
  opacity: 0;
}
.portfolio .portfolio-wrap img {
  transition: all ease-in-out 0.3s;
}
.portfolio .portfolio-wrap .portfolio-info {
  opacity: 0;
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  z-index: 3;
  transition: all ease-in-out 0.3s;
  display: flex;
  flex-direction: column;
  justify-content: flex-end;
  align-items: flex-start;
  padding: 20px;
}
.portfolio .portfolio-wrap .portfolio-info h4 {
  font-size: 20px;
  color: #fff;
  font-weight: 600;
}
.portfolio .portfolio-wrap .portfolio-info p {
  color: rgba(255, 255, 255, 0.7);
  font-size: 14px;
  text-transform: uppercase;
  padding: 0;
  margin: 0;
  font-style: italic;
}
.portfolio .portfolio-wrap .portfolio-links {
  text-align: center;
  z-index: 4;
}
.portfolio .portfolio-wrap .portfolio-links a {
  color: #fff;
  margin: 0 5px 0 0;
  font-size: 28px;
  display: inline-block;
  transition: 0.3s;
}
.portfolio .portfolio-wrap .portfolio-links a:hover {
  color: #5c7cb8;
}
.portfolio .portfolio-wrap:hover::before {
  opacity: 1;
}
.portfolio .portfolio-wrap:hover img {
  transform: scale(1.2);
}
.portfolio .portfolio-wrap:hover .portfolio-info {
  opacity: 1;
}

/*--------------------------------------------------------------
# Portfolio Details
--------------------------------------------------------------*/
.portfolio-details {
  padding-top: 40px;
}
.portfolio-details .portfolio-details-slider img {
  width: 100%;
}
.portfolio-details .portfolio-details-slider .swiper-pagination {
  margin-top: 20px;
  position: relative;
}
.portfolio-details .portfolio-details-slider .swiper-pagination .swiper-pagination-bullet {
  width: 12px;
  height: 12px;
  background-color: #fff;
  opacity: 1;
  border: 1px solid #5c7cb8;
}
.portfolio-details .portfolio-details-slider .swiper-pagination .swiper-pagination-bullet-active {
  background-color: #5c7cb8;
}
.portfolio-details .portfolio-info {
  padding: 30px;
  box-shadow: 0px 0 30px rgba(34, 34, 34, 0.08);
}
.portfolio-details .portfolio-info h3 {
  font-size: 22px;
  font-weight: 700;
  margin-bottom: 20px;
  padding-bottom: 20px;
  border-bottom: 1px solid #eee;
}
.portfolio-details .portfolio-info ul {
  list-style: none;
  padding: 0;
  font-size: 15px;
}
.portfolio-details .portfolio-info ul li + li {
  margin-top: 10px;
}
.portfolio-details .portfolio-description {
  padding-top: 30px;
}
.portfolio-details .portfolio-description h2 {
  font-size: 26px;
  font-weight: 700;
  margin-bottom: 20px;
}
.portfolio-details .portfolio-description p {
  padding: 0;
}

/*--------------------------------------------------------------
# Team
--------------------------------------------------------------*/
.team .member {
  text-align: center;
  margin-bottom: 20px;
  box-shadow: 0px 0px 12px 0px rgba(34, 34, 34, 0.07);
  padding: 30px 20px;
  background: #fff;
}
.team .member img {
  max-width: 60%;
  border-radius: 50%;
  margin: 0 0 30px 0;
}
.team .member h4 {
  font-weight: 700;
  margin-bottom: 2px;
  font-size: 18px;
}
.team .member span {
  font-style: italic;
  display: block;
  font-size: 13px;
}
.team .member p {
  padding-top: 10px;
  font-size: 14px;
  font-style: italic;
  color: #aaaaaa;
}
.team .member .social {
  margin-top: 15px;
}
.team .member .social a {
  color: #919191;
  transition: 0.3s;
}
.team .member .social a:hover {
  color: #5c7cb8;
}
.team .member .social i {
  font-size: 18px;
  margin: 0 2px;
}

/*--------------------------------------------------------------
# Contact
--------------------------------------------------------------*/
.contact .info {
  border-top: 3px solid #5c7cb8;
  border-bottom: 3px solid #5c7cb8;
  padding: 30px;
  background: #fff;
  width: 100%;
  box-shadow: 0 0 24px 0 rgba(0, 0, 0, 0.12);
}
.contact .info i {
  font-size: 20px;
  color: #5c7cb8;
  float: left;
  width: 44px;
  height: 44px;
  background: #eaf6ed;
  display: flex;
  justify-content: center;
  align-items: center;
  border-radius: 50px;
  transition: all 0.3s ease-in-out;
}
.contact .info h4 {
  padding: 0 0 0 60px;
  font-size: 20px;
  font-weight: 600;
  margin-bottom: 5px;
  color: #222222;
}
.contact .info p {
  padding: 0 0 10px 60px;
  margin-bottom: 20px;
  font-size: 14px;
  color: #555555;
}
.contact .info .social-links {
  padding-left: 60px;
}
.contact .info .social-links a {
  font-size: 18px;
  display: inline-block;
  background: #333;
  color: #fff;
  line-height: 1;
  padding: 8px 0;
  border-radius: 50%;
  text-align: center;
  width: 36px;
  height: 36px;
  transition: 0.3s;
  margin-right: 10px;
}
.contact .info .social-links a:hover {
  background: #5c7cb8;
  color: #fff;
}
.contact .info .email:hover i, .contact .info .address:hover i, .contact .info .phone:hover i {
  background: #5cb874;
  color: #fff;
}
.contact .php-email-form {
  width: 100%;
  border-top: 3px solid #5c7cb8;
  border-bottom: 3px solid #5c7cb8;
  padding: 30px;
  background: #fff;
  box-shadow: 0 0 24px 0 rgba(0, 0, 0, 0.12);
}
.contact .php-email-form .form-group {
  padding-bottom: 8px;
}
.contact .php-email-form .error-message {
  display: none;
  color: #fff;
  background: #ed3c0d;
  text-align: left;
  padding: 15px;
  font-weight: 600;
}
.contact .php-email-form .error-message br + br {
  margin-top: 25px;
}
.contact .php-email-form .sent-message {
  display: none;
  color: #fff;
  background: #5c7cb8;
  text-align: center;
  padding: 15px;
  font-weight: 600;
}
.contact .php-email-form .loading {
  display: none;
  background: #fff;
  text-align: center;
  padding: 15px;
}
.contact .php-email-form .loading:before {
  content: "";
  display: inline-block;
  border-radius: 50%;
  width: 24px;
  height: 24px;
  margin: 0 10px -6px 0;
  border: 3px solid #5c7cb8;
  border-top-color: #eee;
  -webkit-animation: animate-loading 1s linear infinite;
  animation: animate-loading 1s linear infinite;
}
.contact .php-email-form input, .contact .php-email-form textarea {
  border-radius: 0;
  box-shadow: none;
  font-size: 14px;
  border-radius: 4px;
}
.contact .php-email-form input:focus, .contact .php-email-form textarea:focus {
  border-color: #5c7cb8;
}
.contact .php-email-form input {
  height: 44px;
}
.contact .php-email-form textarea {
  padding: 10px 12px;
}
.contact .php-email-form button[type=submit] {
  background: #5c7cb8;
  border: 0;
  padding: 10px 24px;
  color: #fff;
  transition: 0.4s;
  border-radius: 4px;
}
.contact .php-email-form button[type=submit]:hover {
  background: #5c7cb8;
}
@-webkit-keyframes animate-loading {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}
@keyframes animate-loading {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}


/*--------------------------------------------------------------
# Footer
--------------------------------------------------------------*/
#footer {
  background: #090909;
  color: #fff;
  font-size: 14px;
  text-align: center;
  padding: 30px 0;
}
#footer h3 {
  font-size: 36px;
  font-weight: 700;
  color: #fff;
  position: relative;
  font-family: "Poppins", sans-serif;
  padding: 0;
  margin: 0 0 15px 0;
}
#footer p {
  font-size: 15;
  font-style: italic;
  padding: 0;
  margin: 0 0 40px 0;
}
#footer .social-links {
  margin: 0 0 40px 0;
}
#footer .social-links a {
  font-size: 18px;
  display: inline-block;
  background: #5cb874;
  color: #fff;
  line-height: 1;
  padding: 8px 0;
  margin-right: 4px;
  border-radius: 50%;
  text-align: center;
  width: 36px;
  height: 36px;
  transition: 0.3s;
}
#footer .social-links a:hover {
  background: #449d5b;
  color: #fff;
  text-decoration: none;
}
#footer .copyright {
  margin: 0 0 5px 0;
}
#footer .credits {
  font-size: 13px;
}
```
## OUTPUT:
### Home Page:
![git](./HOME.png)
### GALLERY PAGE:
![git](./GALLERY.png)
### CONTACT PAGE:
![git](./CONTACT.png)



## Result:
Thus a website is designed using bootstrap framework.

