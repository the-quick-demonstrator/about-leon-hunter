<html lang="en">

<!-- This is a comment -->

<head>

    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <meta name="description" content="">
    <meta name="author" content="Leon Hunter">


    <!-- Bootstrap core CSS -->
    <link href="vendor/bootstrap/css/bootstrap.min.css" rel="stylesheet">

    <!-- Custom fonts for this template -->
    <link href="https://fonts.googleapis.com/css?family=Saira+Extra+Condensed:500,700" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css?family=Muli:400,400i,800,800i" rel="stylesheet">
    <link href="vendor/fontawesome-free/css/all.min.css" rel="stylesheet">

    <!-- Custom styles for this template -->
    <link href="css/resume.min.css" rel="stylesheet">

</head>

<body id="page-top">

<nav class="navbar navbar-expand-lg navbar-dark bg-primary fixed-top" id="sideNav">
    <a class="navbar-brand js-scroll-trigger" href="#page-top">
        <span class="d-block d-lg-none">Leon Hunter</span>
        <span class="d-none d-lg-block">
        <img class="img-fluid img-profile rounded-circle mx-auto mb-2" src="img/profile.jpg" alt="Profile Picture">
      </span>
    </a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
            aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav">
            <li class="nav-item">
                <a class="nav-link js-scroll-trigger" href="#about">About</a>
            </li>
            <li class="nav-item">
                <a class="nav-link js-scroll-trigger" href="#experience">Experience</a>
            </li>
            <li class="nav-item">
                <a class="nav-link js-scroll-trigger" href="#education">Education</a>
            </li>
            <li class="nav-item">
                <a class="nav-link js-scroll-trigger" href="#skills">Skills</a>
            </li>
            <li class="nav-item">
                <a class="nav-link js-scroll-trigger" href="#interests">Interests</a>
            </li>
            <li class="nav-item">
                <a class="nav-link js-scroll-trigger" href="#awards">Awards</a>
            </li>
        </ul>
    </div>
</nav>

<div class="container-fluid p-0">

    <section class="resume-section p-3 p-lg-5 d-flex align-items-center" id="about">
        <div class="w-100">
            <h1 class="mb-0">Leon
                <span class="text-primary">Hunter</span>
            </h1>
            <div class="subheading mb-5">555 Cyberpunk Place · New Castle, DE 19720 · (302) 312-4489 ·
                <a href="mailto:xleonhunter@gmail.com">xleonhunter@gmail.com</a>
            </div>
            <p class="lead mb-5">Experienced T-shaped Engineer, Curriculum Developer, and Technical Instructor with a demonstrated history of managing and up-skilling teams of Junior engineers. Highly skilled in Cloud Native Application Development using Java8+, Spring, Mockito, and ReactJS.</p>
            <div class="social-icons">
                <a href="https://www.linkedin.com/in/leon-hunter">
                    <i class="fab fa-linkedin-in"></i>
                </a>
                <a href="https://github.com/git-leon">
                    <i class="fab fa-github"></i>
                </a>
            </div>
        </div>
    </section>

    <hr class="m-0">

    <section class="resume-section p-3 p-lg-5 d-flex justify-content-center" id="experience">
        <div class="w-100">
            <h2 class="mb-5">Experience</h2>

            {% include resume-item.html
                start-time="December 2021"
                end-time="present"
                title="Vice President Software Engineer"
                location="JPMorgan Chase, Chief Technology Office"
                description="Member of the Artifacts Engineering team. Created systems to migrate artifacts from legacy NAS mounts to AWS EKS Artifactory artifacts using Spring Boot and GraphQL."
            %}

            {% include resume-item.html
                start-time="December 2021"
                end-time="present"
                title="Adjunct Professor: Data Structures 2"
                location="Delaware State University"
                description="Responsible for teaching and instructing students in advanced data structures and algorithms."
            %}

        </div>
    </section>

    <hr class="m-0">

    <section class="resume-section p-3 p-lg-5 d-flex align-items-center" id="education">
        <div class="w-100">
            <h2 class="mb-5">Education</h2>

            <div class="resume-item d-flex flex-column flex-md-row justify-content-between mb-5">
                <div class="resume-content">
                    <h3 class="mb-0">Delaware State University</h3>
                    <div class="subheading mb-3">Bachelor of Science</div>
                    <div>Computer Science - Applied Software Engineering, Minor in Mathematics</div>
                </div>
                <div class="resume-date text-md-right">
                    <span class="text-primary">2011 - 2015</span>
                </div>
            </div>
        </div>
    </section>

    <hr class="m-0">

    <section class="resume-section p-3 p-lg-5 d-flex align-items-center" id="skills">
        <div class="w-100">
            <h2 class="mb-5">Skills</h2>

            <div class="subheading mb-3">Programming Languages & Tools</div>
            <ul class="list-inline dev-icons">
                <li class="list-inline-item">
                    <i class="fab fa-java"></i>
                </li>
                <li class="list-inline-item">
                    <i class="fab fa-react"></i>
                </li>
                <li class="list-inline-item">
                    <i class="fab fa-aws"></i>
                </li>
                <!-- Add more icons as needed -->
            </ul>

            <div class="subheading mb-3">Workflow</div>
            <ul class="fa-ul mb-0">
                <li>
                    <i class="fa-li fa fa-check"></i>
                    Cloud Native Application Development
                </li>
                <li>
                    <i class="fa-li fa fa-check"></i>
                    TDD & Continuous Integration
                </li>
                <li>
                    <i class="fa-li fa fa-check"></i>
                    DevOps & Container Orchestration
                </li>
            </ul>
        </div>
    </section>

    <hr class="m-0">

    <section class="resume-section p-3 p-lg-5 d-flex align-items-center" id="interests">
        <div class="w-100">
            <h2 class="mb-5">Interests</h2>
            <p>In addition to software development, I enjoy spending time outdoors, skateboarding, and visiting the beach in the warmer months. Indoors, I enjoy hosting intellectual debates with friends.</p>
        </div>
    </section>

    <hr class="m-0">

    <section class="resume-section p-3 p-lg-5 d-flex align-items-center" id="awards">
        <div class="w-100">
            <h2 class="mb-5">Certifications & Awards</h2>
            <ul class="fa-ul mb-0">
                <li>
                    <i class="fa-li fa fa-trophy text-warning"></i>
                    Published Biomedical Engineer - Technology Interface International Journal 2013
                </li>
                <li>
                    <i class="fa-li fa fa-trophy text-warning"></i>
                    Code For Good Hackathon 2nd Place - 2013
                </li>
                <li>
                    <i class="fa-li fa fa-trophy text-warning"></i>
                    Excellence in Critical Thinking - William Penn High School 2011
                </li>
            </ul>
        </div>
    </section>

</div>

<!-- Bootstrap core JavaScript -->
<script src="vendor/jquery/jquery.min.js"></script>
<script src="vendor/bootstrap/js/bootstrap.bundle.min.js"></script>

<!-- Plugin JavaScript -->
<script src="vendor/jquery-easing/jquery.easing.min.js"></script>

<!-- Custom scripts for this template -->
<script src="js/resume.min.js"></script>

</body>

</html>
