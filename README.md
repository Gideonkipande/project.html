<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Morans Modern Hospital</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <style>
        h1 {
            font-size: x-large;
            font-weight: bolder;
            font-style: inherit;
        }
        .column {
            display: inline;
            float: left;
        }
        img {
            height: 150px;
            width: 200px;
            align-items: right;
            justify-content: flex-end;
        }
        video {
            height: 200px;
            width: 300px;
        }
        body {
    font-family: Arial, sans-serif;
}

.card-container {
    display: flex;
    flex-wrap: wrap;
    gap: 16px; /* Space between cards */
    justify-content: center; /* Center cards horizontally */
}

.card {
    background: #f9f9f9;
    border: 1px solid #ddd;
    border-radius: 8px;
    padding: 16px;
    width: 200px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

        /* General Body Styling */
body {
    font-family: Arial, sans-serif;
    color: #333;
    margin: 0;
    padding: 0;
    background-color:turquoise;
}

/* Header Styling */
header {
    background-color: #007bff;
    color: #333;
    padding: 10px 0;
    text-align: center;
}

header h1 {
    margin: 20px;
    border: 10px;
    font-size: 2.5em;
    background-image: url('c:\Users\Samuel\Downloads\background-1789175_1920.png');
}

.nav-bar {
    margin-bottom: 10px;
}

.nav-bar .nav-link {
    border-radius: 5px;
}

.nav-bar .nav-link.active {
    background-color: #fff;
    color: #007bff;
}

/* Banner Styling */
#banner {
    background-image: url('path/to/banner-image.jpg'); /* Add your banner image */
    background-size: cover;
    background-position: center;
    color: #fff;
    text-align: center;
    padding: 60px 20px;
}

#banner h2 {
    font-size: 2em;
}

#banner p {
    font-size: 1.2em;
}

#banner button {
    background-color: #007bff;
    color: #fff;
    border: none;
    padding: 10px 20px;
    border-radius: 5px;
    cursor: pointer;
    font-size: 1em;
    margin-top: 10px;
}

/* Wrapper Styling */
#wrapper {
    padding: 20px;
}

/* Service Cards Styling */
.cards {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: space-between;
}

.cards article {
    background-color: #fff;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    padding: 20px;
    width: calc(33% - 20px);
    box-sizing: border-box;
}

.cards .logo img {
    height: 60px;
    width: auto;
}

.cards img {
    max-width: 100%;
    height: auto;
}

.cards h2 {
    font-size: 1.5em;
    margin-top: 0;
}

.cards h3 {
    font-size: 1.2em;
}

/* Two Section Styling */
#two {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    padding: 20px;
}

#two article {
    flex: 1 1 calc(33% - 20px);
    background-color: #fff;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    padding: 20px;
    text-align: center;
}

#two img {
    max-width: 100%;
    height: auto;
    border-radius: 5px;
}

#two h4 {
    font-size: 1.2em;
    margin-top: 10px;
}

/* Section Styling */
section {
    margin-bottom: 20px;
}

/* Footer Styling */
footer {
    background-color: #007bff;
    color: #fff;
    padding: 20px;
    text-align: center;
}

footer .inner-1, footer .inner-2, footer .inner-3, footer .inner-4, footer .inner-5 {
    margin-bottom: 10px;
}

footer h5, footer h6 {
    margin: 10px 0;
}

footer ul {
    list-style-type: none;
    padding: 0;
}

footer ul li {
    margin-bottom: 10px;
}

footer ul li a {
    color: #fff;
    text-decoration: none;
}

footer ul li a:hover {
    text-decoration: underline;
}

/* Chatbox Styling */
.chatbox {
    position: fixed;
    bottom: 10px;
    right: 10px;
    width: 300px;
    background-color: #fff;
    border: 1px solid #ddd;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.chatbox-header {
    background-color: #007bff;
    color: #fff;
    padding: 10px;
    border-top-left-radius: 10px;
    border-top-right-radius: 10px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.chatbox-header i {
    margin-right: 10px;
}

.chatbox-messages {
    max-height: 200px;
    overflow-y: auto;
    padding: 10px;
}

.chatbox-input {
    display: flex;
    padding: 10px;
    border-top: 1px solid #ddd;
}

.chatbox-input input {
    flex: 1;
    padding: 10px;
    border: 1px solid #ddd;
    border-radius: 5px;
}

.chatbox-input button {
    background-color: #007bff;
    color: #fff;
    border: none;
    padding: 10px;
    border-radius: 5px;
    margin-left: 10px;
    cursor: pointer;
}

/* Responsive Design */
@media (max-width: 768px) {
    .cards article, #two article {
        flex: 1 1 100%;
        width: 100%;
    }

    .nav-bar {
        display: block;
    }

    .nav-bar .nav-link {
        display: block;
        margin-bottom: 5px;
    }
}

    
    </style>
</head>
<body>
    <!--header-->
    <header>
            <nav id="menu" class="nav-bar">
                <ul class="nav nav-pills nav-fill gap-2 p-1 small bg-primary rounded-5 shadow-sm" id="pillNav2" role="tablist" style="--bs-nav-link-color: var(--bs-white); --bs-nav-pills-link-active-color: var(--bs-primary); --bs-nav-pills-link-active-bg: var(--bs-white);">
                    <li class="nav-item" role="presentation">
                      <button class="nav-link active rounded-5" id="home-tab2" data-bs-toggle="tab" type="button" role="tab" aria-selected="true">Home</button>
                    </li>
                    <li class="nav-item" role="presentation">
                      <button class="nav-link rounded-5" id="profile-tab2" data-bs-toggle="tab" type="button" role="tab" aria-selected="false">Profile</button>
                    </li>
                    <li class="nav-item" role="presentation">
                      <button class="nav-link rounded-5" id="contact-tab2" data-bs-toggle="tab" type="button" role="tab" aria-selected="false">Contact</button>
                    </li>
                  </ul>
                
        </nav>
        <h1>MORANS MODERN HOSPITAL</h1>
    </header>
    <!--Banner-->
    <section id="banner">
        <div class="inner">
            <div class="logo"><span class="icon fa-gem"></span></div>
            <h2>We Care About You</h2>
            <p>Morans Mordern Hospital is a world class hospital with modern technology equipments to serve you best because we care abut your health.</p>
            <button type="button" id="sign-up" class="text">Sign Up</button>
            <video src="c:\Users\Samuel\Downloads\144012-784164325_small.mp4"> <button type="button" onclick="play-video">play</button></video>
            
        </div>
    </section>

    <!--Wrapper-->
    <section id="wrapper" style="align-items: first baseline;">

        <!--One-->
        <section id="one">
            <div class="inner">
                <img src="" alt="">
                <div class="cards">
                    <h2>Our Best Services</h2>
                    <article>
                        <div class="logo"><span class="icon fa-gem"><img src="c:\Users\Samuel\Downloads\laurel-wreath-150577_1920.png" alt=""></span></div>
                        <h3>All Speciallist</h3>
                        <p>
                            <ul>
                                <li>Dr Kipande - Surgeon</li>
                                <li>Dr Josephine - Neurologist</li>
                                <li>Dr Alice - Surgeon</li>
                            </ul>
                        </p>
                    </article>
                    <article>
                        <i id="material-icon" class="image"><img src="c:\Users\Samuel\Downloads\ai-generated-8607702.jpg" alt=""></i>
                        <h3>Private And Secure</h3>
                        <p> we care for your privacy and our doctors are trained to keep client informtion and details very confidential.</p>
                    </article>
                    <article>
                        <div class="logo"><span class="icon"><img src="c:\Users\Samuel\Downloads\hospital-2388239_1920.png" alt=""></span></div>
                        <h3>Million Custormers</h3>
                        <p>We have wide range of Custormers accross the entire country and international community as well.</p>
                    </article>
                    <article>
                        <div class="chatbox">
                            <div class="chatbox-header">
                                <i class="fas fa-hospital-alt"></i>
                                Send feedback
                                <div>
                                    <div id="chatbox-messages" class="chatbox-messages"></div>
                                    <div class="chatbox-input">
                                        <input type="text" id="chatbox-input" placeholder="Type a message...">
                                        <button onclick="sendMessage()"><i class="fas fa-paper-plane"></i>Send</button>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </article>
                </div>
            </div>
        </section>

        <!--Two-->
        <section id="two" class="cards">
            <article class="card-grid">
                <i class="icon">
                    <img src="c:\Users\Samuel\Downloads\ai-generated-9035834_1920.jpg" alt="">
                    <h4>Baby Health</h4>
                </i>
            </article>
            <article class="two-2">
                <i class="icon">
                    <img src="c:\Users\Samuel\Downloads\stomach-7111043_1920.jpg" alt="">
                    <h4>Stomack</h4>
                </i>
            </article>
            <article class="two-3">
                <div>
                    <i class="material-icon">
                        <img src="c:\Users\Samuel\Downloads\face-3554218_1920.jpg" alt="">
                        <h4>Phsychiatry</h4>
                    </i>
                </div>
            </article>
            <article class="two-4">
                <div>
                <i class="material-icon">
                    <img src="c:\Users\Samuel\Downloads\urology-7467570_1920.png" alt="">
                    <h4>Urology</h4>
                </i>
                </div>
            </article>
            <article class="two-5">
                <div> 
               <img src="c:\Users\Samuel\Downloads\woman-5995387_1920.png" alt="">
                        <h4>Dermotology</h4>
                </div>
            </article>
            <article class="two-6">
                <div>
                    <i class="material-icon">
                        <img src="c:\Users\Samuel\Downloads\virus-7584126_1920.png" alt="">
                         <h4>Infectious Disease</h4>
                    </i>
                </div>
            </article>
        </section>

        <!--Three-->
        <section id="three">
            <h3>Are You Looking For:</h3>
             <article>
                <div class="inner-1">
                    <a href="#" class="special">Doctors</a>
                    <p>Find the best doctors for your solution</p>
                    
                </div>
             </article>
             <article>
                <div class="inner-2">
                     <a href="#" class="special">Consult</a>
                     <p>Consult our best doctors</p>
                </div>
             </article>
             <article>
                <div class="inner-3">
                    <a href="#" class="special"> Pharmacy</a>
                    <p>Acquire suitable medicines from the best pharmaceutical companies worldwide</p>
                </div>
             </article>
             <article>
                <div class="inner-4">
                     <a href="#" class="special">Diagnostics</a>
                     <p>Get diagnosed from the best and experinced doctors.</p>
                </div>
             </article>

        </section>

        <!--Four-->
        <section id="four">
            <h3>Our Best Doctors</h3>
            <div class="column">
            <article class="inner-1">
                <a href="#" class="image"><img src="c:\Users\Samuel\Downloads\doctor-2337835.jpg" alt=""></a>
                <h4>Dr.Alex,Ph.D</h4>
                <p>Ph.D in Medicine</p>
            </article>
            <article class="inner-2">
                <a href="#" class="image"><img src="c:\Users\Samuel\Downloads\doctor-5997500_1920.jpg" alt=""></a>
                <h4>Dr.Robert,Ph.D</h4>
                <p>Ph.D in Aurology</p>
            </article>
            <article class="inner-3">
                <a href="#" class="image"> <img src="c:\Users\Samuel\Downloads\woman-2141808.jpg" alt=""></a>
                <h4>Dr.Angel,Ph.D</h4>
                <p>Ph.D in Audiology.Barchelor of arts in Optometry</p>
            </article>
            <article class="inner-4">
                <a href="#" class="image"><img src="c:\Users\Samuel\Downloads\doctor-5997511_1280.jpg" alt=""></a>
                <h4>Dr.Rusino,Ph.D</h4>
                <p>Ph.D in Neuroscience and psychology</p>
            </article>
            </div>
        </section>

        <!--Five-->
        <section id="five" class="wrapper">
            <div class="inner">
            <h3 class="major">Easy Steps And Get Your Solution</h3>
            <article>
                <a href="#" class="icon"><img src="c:\Users\Samuel\Downloads\computer-1149148.jpg" alt=""></a>
                <h4>Check Doctors Profile</h4>
                <p>Get doctors information here</p>
            </article>
            <article>
                <a href="#" class="icon"><img src="c:\Users\Samuel\Downloads\doctor-5710152_1920.jpg" alt=""></a>
                <h4>Request Consultation</h4>
                <p>Request consultation from the nearest doctor.</p>
            </article>
            <article>
                <a href="#" class="icon"><img src="c:\Users\Samuel\Downloads\doctor-1228627.jpg" alt=""></a>
                <h4>Receive Your Consultation</h4>
                <p>get your consultation results</p>
            </article>
            <article>
                <a href="#" class="icon"><img src="c:\Users\Samuel\Downloads\stethoscope-2617700.jpg" alt=""></a>
                <h4>Get Your Solution</h4>
                <p>Get the best solution to your query</p>
            </article>
            </div>
        </section>

        <!--six-->
        <section id="six" class="wrapper">
            <div class="inner"></div>
            <h3>Best Doctor Anywher Anytime</h3>
            <a href="#" class="image"><img src="c:\Users\Samuel\Downloads\corona-4983590_1920.jpg" alt=""></a>
            <p>Here at Morans Hospital you'll find the best doctor anytime and anywhere else in the world.</p>
            <button type="button" onclick="fetch" class="find-your-doctor">Find Your Doctor</button>
        </section>

        <!--seven-->
        <section id="seven" class="wrapper">
            <div class="inner">
                <h3>Urgent Online Solution To Your Care</h3>
                <a href="#" class="image"><img src="c:\Users\Samuel\Downloads\doctor-6701410_1280.jpg" alt=""></a>
                <p>Get easy an fast solution to your with emmediate success</p>
                <a href="#"><button type="button" class="Take Appointment">Take Appointment</button></a>
            </div>
        </section>
        <!--Eight-->
        <section id="eight" class="wrapper">
            <div class="inner">
                <a href="#" class="image"><img src="c:\Users\Samuel\Downloads\male-2101801_1920.jpg" alt="">
                    <h4>@Gideon_Nyambura</h4>
                    <p>Thank you for saving my <son class="...">Son</son></p>
                </a>
            </div>
            <div class="inner">
                <a href="#" class="image"><img src="c:\Users\Samuel\Downloads\people-7393631_1920.jpg" alt="">
                <h4>@David_Ntabo</h4>
                <p>...The prescription you gave me worked perfectly</p>
                </a>
            </div>
        </section>

        <!--Nine-->
        <section id="nine">
            <div class="inner">
                <article>
                <h4>Want To Register Easilly?</h4>
                <button type="button" class="submit" value="#"> Submit Here</button>
                </article>
            </div>
        </section>
    </section>

        <!--Ten-->
        <footer id="ten">
            <div class="inner-1">
                <h5><div><span class="logo"><img src="" alt=""></span></div>
                Morans Mordern Hospital
                </h5>
                <p>Follow us on our social media pages.We value your feedback</p>
                <ul>
                    <li class="icon solid fa-phone">(000) 000-0000</li>
					<li class="icon solid fa-envelope"><a href="#">information@untitled.tld</a></li>						    
                    <li class="icon brands fa-twitter"><a href="#">twitter.com/untitled-tld</a></li>
					<li class="icon brands fa-facebook-f"><a href="#">facebook.com/untitled-tld</a></li>
					<li class="icon brands fa-instagram"><a href="#">instagram.com/untitled-tld</a></li>
                </ul>
            </div>
            <div class="inner-2">
                <h5>Services</h5>
                <ul>
                    <li><a href="#">Delivery support</a></li>
                    <li><a href="#">Contact Us</a></li>
                    <li><a href="#">Terms of Use</a></li>
                    <li><a href="#">Privacy Policy</a></li>
                </ul>
            </div>
            <div class="inner-3">
                <h5>Feature</h5>
                <ul>
                    <li><a href="#">home</a></li>
                    <li><a href="#">Services</a></li>
                    <li><a href="#">Doctors</a></li>
                    <li><a href="#">About Us</a></li>
                </ul>
            </div>
            <div class="inner-4">
                <h5>User</h5>
                <ul>
                    <li><a href="#">User Login</a></li>
                    <li><a href="#">User Register</a></li>
                    <li><a href="#">Forgot Password</a></li>
                    <li><a href="#">Account Setting</a></li>
            </div>
        </div>
        <div class="inner-5">
         <div class="logo"><img src="" alt=""></div>
         <h6>Copyright</h6>
        </div>
            </footer>
            <script>
    // Function to play video
    function playVideo() {
        const video = document.querySelector('video');
        if (video) {
            video.play();
        }
    }

    // Function to send message in chatbox
    function sendMessage() {
        const input = document.getElementById('chatbox-input');
        const message = input.value.trim();
        
        if (message !== '') {
            const messageContainer = document.createElement('div');
            messageContainer.className = 'message';
            messageContainer.textContent = message;
            
            const chatboxMessages = document.getElementById('chatbox-messages');
            chatboxMessages.appendChild(messageContainer);
            
            input.value = '';
            
            // Scroll to the bottom
            chatboxMessages.scrollTop = chatboxMessages.scrollHeight;
        }
    }

    // Optional: Add functionality to send message when pressing Enter
    document.getElementById('chatbox-input').addEventListener('keydown', function(event) {
        if (event.key === 'Enter') {
            event.preventDefault();
            sendMessage();
        }
    });

    // Function for fetching doctors (for demonstration, log a message)
    function findYourDoctor() {
        console.log('Fetching doctors...');
        // Implement actual fetch functionality here
    }

    // Attach event listener for play button
    document.addEventListener('DOMContentLoaded', function() {
        const playButton = document.querySelector('video + button');
        if (playButton) {
            playButton.addEventListener('click', playVideo);
        }

        const findDoctorButton = document.querySelector('#six .find-your-doctor');
        if (findDoctorButton) {
            findDoctorButton.addEventListener('click', findYourDoctor);
        }
    });


<svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-0-circle-fill" viewBox="0 0 16 16">
  <path d="M8 4.951c-1.008 0-1.629 1.09-1.629 2.895v.31c0 1.81.627 2.895 1.629 2.895s1.623-1.09 1.623-2.895v-.31c0-1.8-.621-2.895-1.623-2.895"/>
  <path d="M16 8A8 8 0 1 1 0 8a8 8 0 0 1 16 0m-8.012 4.158c1.858 0 2.96-1.582 2.96-3.99V7.84c0-2.426-1.079-3.996-2.936-3.996-1.864 0-2.965 1.588-2.965 3.996v.328c0 2.42 1.09 3.99 2.941 3.99"/>
</svg>

            </script>
            <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
</body>
</html> 
