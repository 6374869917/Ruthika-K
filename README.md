
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <link rel="stylesheet" href="styles.css">
    <link rel="stylesheet" href="style.css">
    <link rel="statesheet" href="stylessess.css">
</head>
<body> 
    <header>
        <div class="logo">
            <h1 style="font-size: xx-large;">
                <img src="https://st2.depositphotos.com/4483779/6691/v/450/depositphotos_66916419-stock-illustration-auto-on-the-road-logo.jpg" alt="Driving School Logo">
                RK Driving School
            </h1>
        </div>
        <nav>
            <ul>
                <ul class="nav-links">
                <li><a href="home.html" class="nav-link">Home</a></li>
                <li><a href="about.html" class="nav-link">About</a></li>
                <li><a href="testimonials.html" class="nav-link">Testimonials</a></li>
                <li><a href="gallery.html" class="nav-link">Gallery</a></li>
                <li><a href="contact.html" class="nav-link">Contact</a></li>
            </ul>
            </ul>
        </nav>
        <script src="script.js"></script>
    </header>
    <div class="slider">
        <div class="slides">
            <input type="radio" name="radio-btn" id="radio1">
            <input type="radio" name="radio-btn" id="radio2">
            <div class="slide first">
                <img src="https://static.vecteezy.com/system/resources/previews/025/441/328/non_2x/driving-school-driver-license-tiny-people-studying-in-drive-lesson-and-passing-exams-online-use-laptop-traffic-rules-road-signs-modern-flat-cartoon-style-illustration-on-white-background-vector.jpg" alt="Image 1">
            </div>
            <div class="slide">
                <img src="https://images.unsplash.com/photo-1449965408869-eaa3f722e40d?fm=jpg&q=60&w=3000&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8ZHJpdmluZ3xlbnwwfHwwfHx8MA%3D%3D" alt="Image 2">
            </div>
        </div>
        <div class="navigation">
            <div class="prev" onclick="prevSlide()">&#10094;</div>
            <div class="next" onclick="nextSlide()">&#10095;</div>
        </div>
    </div>
    <script src="script.js"></script>
    <br>
    <br>
    <section id="about" class="section">
        <h2 style="font-size: xx-large; color: rgb(10, 64, 77);">About</h2>
        <br>
        <p style="font-size: larger; color: black;">
            We aim to provide the best driving lessons with a focus on safety and confidence.<br>
            To empower our customers with the skills, confidence, and knowledge they need to drive safely <br>
            and responsibly on the road. To train 10,000 new drivers every year with a 99% pass rate and a<br>
            100% satisfaction rate. It should use simple and concise words that convey your driving school's<br>
            message and tone. It should also use positive and optimistic language.
        </p>
    </section>
    <br>
    <h1 style="font-size: xx-large; color: rgb(10, 64, 77); text-align: center;">Testimonials</h1>
    <!-- Custom styles -->
    <style>
        .testimonial {
            padding: 0px;
            margin-bottom: 30px;
            background-color:rgba(170, 223, 238, 0.954)  ;
            border: 1px solid rgba(170, 223, 238, 0.954)  ;
            border-radius: 5px;
            text-align: center;
        }
        .testimonial .testimonial-text {
            font-style: inherit;
            font-size: larger;
            color: black;
        }
        .testimonial .testimonial-author {
            border-radius: 50%;
            margin-top: 10px;
            font-weight: bold;
        }
    </style>
    <div class="container">
        <div class="row">
            <div class="col-lg-10 offset-lg-1">
                <div id="testimonialCarousel" class="carousel slide" data-ride="carousel">
                    <div class="carousel-inner">
                        <div class="carousel-item active">
                            <div class="testimonial">
                                <p class="testimonial-text">"Lorem ipsum dolor sit amet, consectetur adipiscing elit. <br>
                                    Nulla convallis libero in nunc consequat, id gravida velit volutpat".<br></p>
                                <p class="testimonial-author">- John Doe</p>
                            </div>
                        </div>
                        <div class="carousel-item">
                            <div class="testimonial">
                                <p class="testimonial-text">"Phasellus vitae tortor nec neque pretium suscipit.<br>
                                    Donec venenatis ligula in libero elementum, ac placerat eros suscipit."</p>
                                <p class="testimonial-author">- Jane Smith</p>
                            </div>
                        </div>
                        <div class="carousel-item">
                            <div class="testimonial">
                                <p class="testimonial-text">"Fusce vel orci ac dolor malesuada suscipit.<br>
                                    Integer non turpis sit amet ligula egestas vehicula a in justo."</p>
                                <p class="testimonial-author">- Alice Brown</p>
                            </div>
                        </div>
                    </div>
                    <a class="carousel-control-prev" href="#testimonialCarousel" role="button" data-slide="prev">
                        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                        <span class="sr-only">Previous</span>
                    </a>
                    <a class="carousel-control-next" href="#testimonialCarousel" role="button" data-slide="next">
                        <span class="carousel-control-next-icon" aria-hidden="true"></span>
                        <span class="sr-only">Next</span>
                    </a>
                </div>
            </div>
        </div>
    </div>
    <!-- Bootstrap JS and dependencies (jQuery is required) -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.4/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
    <br><br>
    <h1 style="font-size: xx-large; color: rgb(10, 64, 77); text-align: center;">Gallery</h1>
    <br>
    <section class="driving-gallery">
        <div class="item-container">
            <div class="image-container">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR7PPXwdG3v9g1HzDB5g4ObPATfkYlg0-ZHBg&s" alt="Driving Lesson 1" class="driving-img">
                <div class="overlay"></div>
            </div>
        </div>
        <div class="item-container">
            <div class="image-container">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQW2LEJpPh-E0KOlJEZKHX6zswu9mx02yNjrw&s" alt="Driving Lesson 3" class="driving-img">
                <div class="overlay"></div>
            </div>
        </div>
        <div class="item-container">
            <div class="image-container">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTpI02Ap8-13QCN3RQBK4v683hYewl9Xttx-Q&s" alt="Driving Lesson 4" class="driving-img">
                <div class="overlay"></div>
            </div>
        </div>
    </section>
    <br>
    <style>
        .form-container {
            max-width: 500px;
            margin: auto;
            padding: 20px;
            border-radius: 10px;
            background-image: url('https://png.pngtree.com/background/20210710/original/pngtree-driving-school-enrollment-poster-background-material-picture-image_1044636.jpg'); /* Replace with your image URL */
            background-size: cover;
            background-position: center;
            font-weight:bold ;
        }
        .form-container h2 {
            margin-bottom: 20px;
            font-weight:bold ;
        }

    </style>
    <div class="form-container">
        <h2 style="font-weight:bold;color:rgb(10, 64, 77) ;text-align: center;">Eligibility Check</h2>
        <br>
        <form id="eligibilityForm">
            <div class="form-group">
                <label for="age">Age:</label>
                <input type="number" id="age" name="age" class="form-control" required>
            </div>
            <div class="form-group">
                <label for="license">Do you have a valid learner's permit?</label>
                <select id="license" name="license" class="form-control" required>
                    <option value="yes">Yes</option>
                    <option value="no">No</option>
                </select>
            </div>
            <div class="form-group">
                <label for="residence">Are you a resident of the city?</label>
                <select id="residence" name="residence" class="form-control" required>
                    <option value="yes">Yes</option>
                    <option value="no">No</option>
                </select>
            </div>
            <div class="form-group">
                <label for="medical">Do you have any medical conditions that might affect driving?</label>
                <select id="medical" name="medical" class="form-control" required>
                    <option value="yes">Yes</option>
                    <option value="no">No</option>
                </select>
            </div>
            <button style="background-color:rgb(10, 64, 77) ;color:white;" type="submit" class="btn btn-primary">Check Eligibility</button>
        </form>
    </div>

    <!-- Modal -->
    <div class="modal fade" id="eligibilityModal" tabindex="-1" aria-labelledby="eligibilityModalLabel" aria-hidden="true">
        <div class="modal-dialog">
            <div class="modal-content">
                <div class="modal-header">
                    <h5 class="modal-title" id="eligibilityModalLabel">Eligibility Check Result</h5>
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close">
                        <span aria-hidden="true">&times;</span>
                    </button>
                </div>
                <div class="modal-body" id="result">
                </div>
                <div class="modal-footer">
                    <button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
                </div>
            </div>
        </div>
    </div>

    <script>
        document.getElementById('eligibilityForm').addEventListener('submit', function(event) {
            event.preventDefault();
            
            const age = parseInt(document.getElementById('age').value, 10);
            const license = document.getElementById('license').value;
            const residence = document.getElementById('residence').value;
            const medical = document.getElementById('medical').value;
            
            let resultMessage = '';
            
            if (age < 18) {
                resultMessage = 'Sorry, you must be at least 18 years old to enroll.';
            } else if (license === 'no') {
                resultMessage = 'You need a valid learner\'s permit to enroll.';
            } else if (residence === 'no') {
                resultMessage = 'You need to be a resident of the city to enroll.';
            } else if (medical === 'yes') {
                resultMessage = 'Please consult with your doctor before enrolling.';
            } else {
                resultMessage = 'You are eligible to enroll in our driving school!';
            }
            
            document.getElementById('result').innerText = resultMessage;
            $('#eligibilityModal').modal('show');
        });
    </script>

    <br>

    <footer class="footer">
        <div class="footer-content">
            <div class="footer-section useful-links">
                <h2 style="color:rgba(170, 223, 238, 0.954) ;">Useful Links</h2>
                <ul>
                    <li><a href="home.html">Home</a></li>
                    <li><a href="about.html">About</a></li>
                    <li><a href="product.html">Product</a></li>
                    <li><a href="testimonial.html">Testimonial</a></li>
                    <li><a href="contact.html">Contact</a></li>
                </ul>
            </div>
            <div class="footer-section address">
                <h2 style="color:rgba(170, 223, 238, 0.954) ;">Contact Details</h2>
                <p style="font-size: larger;">
                    No.24/1 Pachaiyappa Street,<br>
                    Opposite to Anna Arch,<br>
                    Arumbakkam, Chennai,<br>
                    Tamil Nadu-600106
                </p>
                <p style="font-size: larger;">
                    Email: rk@drivingschool.com<br>
                    Phone: 6375879918
                </p>
            </div>
        </div>
        <div class="social-media">
            <a href="https://www.facebook.com" target="_blank"><i class="fab fa-facebook-f"></i></a>
            <a href="https://www.twitter.com" target="_blank"><i class="fab fa-twitter"></i></a>
            <a href="https://www.instagram.com" target="_blank"><i class="fab fa-instagram"></i></a>
        </div>
    </footer>
    <footer>
        <div class="footer-bottom">
            <p style="text-align: center;">&copy; 2024 RK Driving School. All Rights Reserved.</p>
        </div>
    </footer>
</body>
</html>
