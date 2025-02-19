<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hotel TGB</title>
    <link rel="stylesheet" href="css/bootstrap.min.css">
    <script src="jquery.min.js"></script>
    <script src="js/bootstrap.min.js"></script>
    
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        nav a.navbar-brand {
            font-size: 1.5rem;
            font-weight: bold;
        }
        nav .nav-link {
            font-size: 1.1rem;
            color: #ffffff;
        }
        header {
            text-align: center;
        }
        footer {
            background-color: #818486;
            color: white;
            text-align: center;
            padding: 20px 0;
        }
    </style>
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container-fluid">
            <img src="logo.png" width="100px" height="100px">
            <a class="navbar-brand" href="#">THE GRAND BHAGWATI</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item"><a class="nav-link" href="about">ABOUT US</a></li>
                    <li class="nav-item"><a class="nav-link" href="#accommodations">ACCOMMODATIONS</a></li>
                    <li class="nav-item"><a class="nav-link" href="#dining">DINING</a></li>
                    <li class="nav-item"><a class="nav-link" href="#events">EVENTS</a></li>
                    <li class="nav-item"><a class="nav-link" href="#packages">PACKAGES</a></li>
                    <li class="nav-item"><a class="nav-link" href="#takeaway">TAKE AWAY</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">CONTACT US</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <header>
            <img src="img1.png">
    </header>

    <section id="about" class="text-center">
        <div class="container">
            <h2>About Us</h2>
            <p>The Grand Bhagwati is a chain of hotels known for its excellent food, distinguished hospitality, magnificent banquet space, and outdoor catering segment across India.</p>
        </div>
    </section>

    <section id="booking-details" class="bg-light text-center">
        <div class="container">
            <h2>Booking Details</h2>
            <form id="hotel-booking-form" class="p-4 shadow-lg bg-white rounded">
                <div class="form-group">
                    <label for="check-in-date">Check-In Date:</label>
                    <input type="date" name="check-in" class="form-control" required >
                </div>
                <div class="form-group">
                    <label for="check-out-date">Check-Out Date:</label>
                    <input type="date" name="check-out" class="form-control" required>
                </div>
                <div class="form-group">
                    <label for="room-type">Room Type:</label>
                    <select id="room-type" name="room-type" class="form-control" required>
                        <option value="single">Single Room</option>
                        <option value="double">Double Room</option>
                        <option value="suite">Suite</option>
                    </select>
                </div>
                <div class="form-group">
                    <label for="guest-count">Number of Guests:</label>
                    <input type="number" name="guests" class="form-control" min="1" required>
                </div>
                <button type="submit" class="btn btn-primary btn-block">Book Now</button>
            </form>
        </div>
    </section>
    <section id="contact" class="text-center">
        <div class="container">
            <h2>Contact Us</h2>
            <p>Email: info@hoteltgb.com</p>
            <p>Phone: +1234567890</p>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>© 2025 Hotel TGB. All rights reserved.</p>
        </div>
    </footer>
    <section id="about" class="container my-5">
        <h2 class="text-center mb-4">About Us</h2>
        <img src="at1.png">
    </section>
</body>
</html>
