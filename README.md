# <!DOCTYPE html>
<html>
<title>Hotel Reservation</title>

<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Raleway">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body,h1,h2,h3,h4,h5,h6 {font-family: "Raleway", Arial, Helvetica, sans-serif}
</style>
<body class="w3-light-grey">

<!-- Navigation Bar -->
<div class="w3-bar w3-white w3-large">
  <a href="#" class="w3-bar-item w3-button w3-red w3-mobile"><i class="fa fa-bed w3-margin-right"></i> Logo (Sample Project)</a>
  <a href="#rooms" class="w3-bar-item w3-button w3-mobile">Rooms</a>
  <a href="#about" class="w3-bar-item w3-button w3-mobile">About</a>
  <a href="#contact" class="w3-bar-item w3-button w3-mobile">Contact</a>
  <a href="#contact" class="w3-bar-item w3-button w3-right w3-light-grey w3-mobile">Book Now</a>
</div>
<!-- Header -->
<header class="w3-display-container w3-content" style="max-width:1500px;">
  <img  src="homepage1.PNG" alt="The Hotel" style="min-width:1000px" width="1500" height="650" opacity="0.5" >
  <div class="w3-display-left w3-padding w3-col l6 m8">
    <div class="w3-container w3-red">
      <h2><i class="fa fa-bed w3-margin-right"></i>Hotel Name</h2>
    </div>
    <div class="w3-container w3-white w3-padding-16">
      <form action="/action_page.php" target="_blank">
        <div class="w3-row-padding" style="margin:0 -16px;">
          <div class="w3-half w3-margin-bottom">
            <label><i class="fa fa-calendar-o"></i> Check In</label>
            <input class="w3-input w3-border" type="text" placeholder="DD MM YYYY" name="CheckIn" required>
          </div>
          <div class="w3-half">
            <label><i class="fa fa-calendar-o"></i> Check Out</label>
            <input class="w3-input w3-border" type="text" placeholder="DD MM YYYY" name="CheckOut" required>
          </div>
        </div>
        <div class="w3-row-padding" style="margin:8px -16px;">
          <div class="w3-half w3-margin-bottom">
            <label><i class="fa fa-male"></i> Adults</label>
            <input class="w3-input w3-border" type="number" value="1" name="Adults" min="1" max="6">
          </div>
          <div class="w3-half">
            <label><i class="fa fa-child"></i> Kids</label>
          <input class="w3-input w3-border" type="number" value="0" name="Kids" min="0" max="6">
          </div>
        </div>
        <button class="w3-button w3-dark-grey" type="submit"><i class="fa fa-search w3-margin-right"></i> Search availability</button>
      </form>
    </div>
  </div>
</header>

<!-- Page content -->
<div class="w3-content" style="max-width:1532px;">

  <div class="w3-container w3-margin-top" id="rooms">
    <h3>Rooms</h3>
    <p>Make yourself at home is our slogan. We offer the best beds in the industry. Sleep well and rest well.</p>
  </div>
  
  <div class="w3-row-padding">
    <div class="w3-col m3">
      <label><i class="fa fa-calendar-o"></i> Check In</label>
      <input class="w3-input w3-border" type="text" placeholder="DD MM YYYY">
    </div>
    <div class="w3-col m3">
      <label><i class="fa fa-calendar-o"></i> Check Out</label>
      <input class="w3-input w3-border" type="text" placeholder="DD MM YYYY">
    </div>
    <div class="w3-col m2">
      <label><i class="fa fa-male"></i> Adults</label>
      <input class="w3-input w3-border" type="number" placeholder="1">
    </div>
    <div class="w3-col m2">
      <label><i class="fa fa-child"></i> Kids</label>
      <input class="w3-input w3-border" type="number" placeholder="0">
    </div>
    <div class="w3-col m2">
      <label><i class="fa fa-search"></i> Search</label>
      <button class="w3-button w3-block w3-black">Search</button>
    </div>
  </div>

  <div class="w3-row-padding w3-padding-16">
    <div class="w3-third w3-margin-bottom">
      <img src="single_room.jpg" alt="Norway" style="width:100%">
      <div class="w3-container w3-white">
        <h3>Single Room</h3>
        <h6 class="w3-opacity">From INR 999-1499</h6>
        <p>Single bed</p>
        <p>15m<sup>2</sup></p>
        <p class="w3-large"><i class="fa fa-bath"></i> <i class="fa fa-phone"></i> <i class="fa fa-wifi"></i></p>
        <button class="w3-button w3-block w3-black w3-margin-bottom">Choose Room</button>
      </div>
    </div>
    <div class="w3-third w3-margin-bottom">
      <img src="double_room.jpg" alt="Norway" style="width:100%">
      <div class="w3-container w3-white">
        <h3>Double Room</h3>
        <h6 class="w3-opacity">From INR 1499-2999</h6>
        <p>Queen-size bed</p>
        <p>25m<sup>2</sup></p>
        <p class="w3-large"><i class="fa fa-bath"></i> <i class="fa fa-phone"></i> <i class="fa fa-wifi"></i> <i class="fa fa-tv"></i></p>
        <button class="w3-button w3-block w3-black w3-margin-bottom">Choose Room</button>
      </div>
    </div>
    <div class="w3-third w3-margin-bottom">
      <img src="delux_room.jpg" alt="Norway" style="width:100%">
      <div class="w3-container w3-white">
        <h3>Deluxe Room</h3>
        <h6 class="w3-opacity">From INR 2999-4999 </h6>
        <p>King-size bed</p>
        <p>40m<sup>2</sup></p>
        <p class="w3-large"><i class="fa fa-bath"></i> <i class="fa fa-phone"></i> <i class="fa fa-wifi"></i> <i class="fa fa-tv"></i> <i class="fa fa-glass"></i> <i class="fa fa-cutlery"></i></p>
        <button class="w3-button w3-block w3-black w3-margin-bottom">Choose Room</button>
      </div>
    </div>
  </div>

  <div class="w3-row-padding" id="about">
    <div class="w3-col l4 12">
      <h3>About</h3>
		<h6>Our hotel is one of a kind. It is truely amazing. Surrounded by beautiful tropical gardens, our buildings are an attractive part of the lush, tropical mountainside. The rooms are cozy, yet elegant, spacious and comfortable. Each room is designed with the environment in mind. For example, large windows help to bring the outdoors inside.Give us a chance to serve you . You will surely have greate experience . </h6>
    <p>We accept: <i class="fa fa-credit-card w3-large"></i> <i class="fa fa-cc-mastercard w3-large"></i> <i class="fa fa-cc-amex w3-large"></i> <i class="fa fa-cc-cc-visa w3-large"></i><i class="fa fa-cc-paypal w3-large"></i></p>
    </div>
    <div class="w3-col l8 12">
      <!-- Image of location/map -->
      <img src="map.PNG"  style="width:90%; height:350px;  float:right">
    </div>
  </div>
  
  <div class="w3-row-padding w3-large w3-center" style="margin:32px 0">
    <div class="w3-third"><i class="fa fa-map-marker w3-text-red"></i> New Delhi , India </div>
    <div class="w3-third"><i class="fa fa-phone w3-text-red"></i> Phone: +91 **********</div>
    <div class="w3-third"><i class="fa fa-envelope w3-text-red"></i> Email: mail@mail.com</div>
  </div>

  <div class="w3-panel w3-red w3-leftbar w3-padding-32">
    <h6><i class="fa fa-info w3-deep-orange w3-padding w3-margin-right"></i> On demand, we can offer playstation, babycall, children care, dog equipment, etc.</h6>
  </div>

  <div class="w3-container">
    <h3>Our Hotels</h3>
    <h6>You can find our hotels all over India</h6>
  </div>
  
  <div class="w3-row-padding w3-padding-16 w3-text-white w3-large">
    <div class="w3-half w3-margin-bottom">
      <div class="w3-display-container">
        <img src="mumbai.jpg" alt="jaipur" style="width:100%">
        <span class="w3-display-bottomleft w3-padding">Mumbai </span>
      </div>
    </div>
    <div class="w3-half">
      <div class="w3-row-padding" style="margin:0 -16px">
        <div class="w3-half w3-margin-bottom">
          <div class="w3-display-container">
            <img src="jaipur.jpg" alt="jaipur" style="width:100%">
            <span class="w3-display-bottomleft w3-padding">jaipur</span>
          </div>
        </div>
        <div class="w3-half w3-margin-bottom">
          <div class="w3-display-container">
            <img src="kerala.jpg" alt="kerala" style="width:100%">
            <span class="w3-display-bottomleft w3-padding">Kerala</span>
          </div>
        </div>
      </div>
      <div class="w3-row-padding" style="margin:0 -16px">
        <div class="w3-half w3-margin-bottom">
          <div class="w3-display-container">
            <img src="manali.jpg" alt="manali" style="width:100%">
            <span class="w3-display-bottomleft w3-padding">Manali </span>
          </div>
        </div>
        <div class="w3-half w3-margin-bottom">
          <div class="w3-display-container">
            <img src="goa.jpg" alt="goa" style="width:100%">
            <span class="w3-display-bottomleft w3-padding">Goa</span>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="w3-container w3-padding-32 w3-black w3-opacity w3-card w3-hover-opacity-off" style="margin:32px 0;">
    <h2>Get the best offers first!</h2>
    <p>Join our newsletter.</p>
    <label>E-mail</label>
    <input class="w3-input w3-border" type="text" placeholder="Your Email address">
    <button type="button" class="w3-button w3-red w3-margin-top">Subscribe</button>
  </div>

  <div class="w3-container" id="contact">
    <h2>Contact</h2>
    <p>If you have any questions, do not hesitate to ask them.</p>
    <i class="fa fa-map-marker w3-text-red" style="width:30px"></i> New Delhi , India <br>
    <i class="fa fa-phone w3-text-red" style="width:30px"></i> Phone: +91 **********<br>
    <i class="fa fa-envelope w3-text-red" style="width:30px"> </i> Email: mail@mail.com<br>
    <form action="/action_page.php" target="_blank">
      <p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Name" required name="Name"></p>
      <p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Email" required name="Email"></p>
      <p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Message" required name="Message"></p>
      <p><button class="w3-button w3-black w3-padding-large" type="submit">SEND MESSAGE</button></p>
    </form>
  </div>

<!-- End page content -->
</div>

<!-- Footer -->
<footer class="w3-padding-32 w3-black w3-center w3-margin-top">
  <h5>Find Us On</h5>
  <div class="w3-xlarge w3-padding-16">
    <i class="fa fa-facebook-official w3-hover-opacity"></i>
    <i class="fa fa-instagram w3-hover-opacity"></i>
    <i class="fa fa-snapchat w3-hover-opacity"></i>
    <i class="fa fa-pinterest-p w3-hover-opacity"></i>
    <i class="fa fa-twitter w3-hover-opacity"></i>
    <i class="fa fa-linkedin w3-hover-opacity"></i>
  </div>
  
</footer>

<!-- Add Google Maps -->
<script>
function myMap() {
  myCenter=new google.maps.LatLng(41.878114, -87.629798);
  var mapOptions= {
    center:myCenter,
    zoom:12, scrollwheel: false, draggable: false,
    mapTypeId:google.maps.MapTypeId.ROADMAP
  };
  var map=new google.maps.Map(document.getElementById("googleMap"),mapOptions);

  var marker = new google.maps.Marker({
    position: myCenter,
  });
  marker.setMap(map);
}
</script>
<script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyBu-916DdpKAjTmJNIgngS6HL_kDIKU0aU&callback=myMap"></script>
<!--
To use this code on your website, get a free API key from Google.
Read more at: https://www.w3schools.com/graphics/google_maps_basic.asp
-->

</body>
</html>
