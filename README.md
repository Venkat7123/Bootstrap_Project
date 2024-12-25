# Project Responsive Web Design using Bootstrap
## Date: 24.11.2024

## AIM:
To create a simple website using Bootstrap.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :
```
travel.html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css" integrity="sha512-KfkfwYDsLkIlwQp6LFnl8zNdLGxu9YAA1QvwINks4PhcElQSvqcyVLLD9aMhXd13uQjoXtEKNosOWaZqXgel0g==" crossorigin="anonymous" referrerpolicy="no-referrer">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <title>One Last Time</title>
</head>

<body class="bg" style="background-image:url('bg.jpg'); background-size: cover; 
                background-position: center; height: 100vh;">

    <nav class="navbar navbar-expand-lg navbar-dark bg-dark mb-5">
        <div class="container">
            <a class="navbar-brand" href="#">One Last Time</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="travel.html">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="place.html">Places</a></li>
                    <li class="nav-item"><a class="nav-link" href="packages.html">Packages</a></li>
                    <li class="nav-item"><a class="nav-link" href="book.html">Contact Us</a></li>
                </ul>
            </div>
        </div>
    </nav>
    <section class="main">
        <div class="container text-center">
            <div class="row">
                <h1 class="h1 mt-5 display-2 pt-5 text-center text-light">Travel All over the World in Affordable Price
                </h1>

            </div>
            <button class="btn btn-info mt-5 mb-5"><a href="place.html" class="nav-link">View Places</a></button>
        </div>
    </section>
    <footer class="text-light mt-5 pt-4 ">
        <div class="container-fluid bg-dark bg-opacity-50 text-center text-md-left mt-5">
            <div class="row">
                <div class="footer-pad">Designed with <i class="fa-solid fa-heart text-danger"></i> by Venkatachalam S</div>
            </div>
        </div>
    </footer>
</body>

</html>

place.html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css" integrity="sha512-KfkfwYDsLkIlwQp6LFnl8zNdLGxu9YAA1QvwINks4PhcElQSvqcyVLLD9aMhXd13uQjoXtEKNosOWaZqXgel0g==" crossorigin="anonymous" referrerpolicy="no-referrer">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <title>Places ~ One Last Time</title>
</head>

<body class="bg-opacity-10" style="background-image:url('bg1.jpg'); background-size: cover; 
                background-position: center; height: 100vh;">
    
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">One Last Time</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="travel.html">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="place.html">Places</a></li>
                    <li class="nav-item"><a class="nav-link" href="packages.html">Packages</a></li>
                    <li class="nav-item"><a class="nav-link" href="book.html">Contact Us</a></li>
                </ul>
            </div>
        </div>
    </nav>
    <div class="container mt-4 pt-2">
        <h1 class="display-6 ms-3 ps-3 text-primary">Our Customers Recommended Places</h1>
    </div>
        <div class="container mt-5">
            <div class="row">
                <div class="col-lg-3 ms-5 me-5 pt-3 rounded bg-secondary bg-opacity-50">
                    <img src="temple.jpg" class="img-thumbnail rounded">
                    <h1 class="text-center pt-1 text-info display-6">Srirangam</h1>
                </div>
                <div class="col-lg-3 ms-5 me-5 pt-3 ps-4 rounded bg-secondary bg-opacity-50">
                    <img src="dubai.jpg" class="img-thumbnail ms-3 rounded">
                    <h1 class="text-center pt-3 text-info display-6">Dubai</h1>
                </div>
                <div class="col-lg-3 ms-5 ps-4 pt-3 rounded bg-secondary bg-opacity-50">
                    <img src="singapore.jpg" class="img-thumbnail ms-2 rounded">
                    <h1 class="text-center text-info display-6">Singapore</h1>
                </div>
            </div>
        </div>

    <footer class="text-light mt-5  ">
        <div class="container-fluid bg-dark bg-opacity-50 text-center text-md-left mt-5">
            <div class="row">
                <div class="footer-pad">Designed with <i class="fa-solid fa-heart text-danger"></i> by Venkatachalam S</div>
            </div>
        </div>
    </footer>
    
</body>

</html>

packages.html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css" integrity="sha512-KfkfwYDsLkIlwQp6LFnl8zNdLGxu9YAA1QvwINks4PhcElQSvqcyVLLD9aMhXd13uQjoXtEKNosOWaZqXgel0g==" crossorigin="anonymous" referrerpolicy="no-referrer">

    <title>Packages ~ One Last Time</title>
</head>

<body class="bg" style="background-image:url('bg2.jpg'); background-size: cover; 
                background-position: center; height: 100vh;">
    
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">One Last Time</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="travel.html">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="place.html">Places</a></li>
                    <li class="nav-item"><a class="nav-link" href="packages.html">Packages</a></li>
                    <li class="nav-item"><a class="nav-link" href="book.html">Contact Us</a></li>
                </ul>
            </div>
        </div>
    </nav>
    <div class="container mt-4 pt-2">
        <h1 class="display-6 text-center ms-3 ps-3 text-danger">Our Top Packages</h1>
    </div>
        <div class="mt-5">
            <div class="row text-center d-flex justify-content-center">
                <div class="col-lg-2 ms-5 me-5 pt-3 rounded bg-info bg-opacity-50">
                    <img src="taj.jpg" class="img-thumbnail rounded">
                    <h3 class=" pt-1 text-warning">Package-1</h3>
                    <h1 class="pt-1 text-light display-6">India <br> Unveiled</h1>
                    <p class=" pt-1 text-success">Discover India's Soul: Authentic Travel Experiences.</p>
                    <button class="btn btn-primary mb-3 mt-4"><a href="#" class="nav-link">View Full Package</a></button>
                </div>
                <div class="col-lg-2 me-5 pt-3 rounded bg-info bg-opacity-50">
                    <img src="saudi.jpg" class="img-thumbnail rounded">
                    <h3 class=" pt-1 text-warning">Package-2</h3>
                    <h1 class="pt-1 text-light display-6">Arabian Adventures</h1>
                    <p class=" pt-1 text-success">Explore Saudi Arabia's Wonders: Cultural Immersion and Desert Escapes.</p>
                    <button class="btn btn-primary mb-3"><a href="#" class="nav-link">View Full Package</a></button>
                </div>
                <div class="col-lg-2 me-5 pt-3 rounded bg-info bg-opacity-50">
                    <img src="thailand.jpg" class="img-thumbnail rounded">
                    <h3 class=" pt-1 text-warning">Package-3</h3>
                    <h1 class="pt-1 text-light display-6">Thailand Unbound</h1>
                    <p class=" pt-1 text-success">Discover the Real Thailand: Beyond the Tourist Trail.</p>
                    <button class="btn btn-primary mt-3 mb-3"><a href="#" class="nav-link">View Full Package</a></button>
                </div>
                <div class="col-lg-2 pt-3 bg-info rounded bg-opacity-50">
                        <img src="france.jpg" class="img-thumbnail rounded opacity-50" alt="">
                        <img src="new.jpg" class="img-thumbnail rounded opacity-50 mt-3" alt="">
                    <button class="btn btn-primary mt-5 "><a href="#" class="nav-link">View All Packages </a></button>
                </div>
            </div>
        </div>
    <footer class="text-light mt-5  ">
        <div class="container-fluid bg-dark bg-opacity-50 text-center text-md-left mt-5">
            <div class="row">
                <div class="footer-pad">Designed with <i class="fa-solid fa-heart text-danger"></i> by Venkatachalam S</div>
            </div>
        </div>
    </footer>
</body>

</html>

book.html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css"
        integrity="sha512-KfkfwYDsLkIlwQp6LFnl8zNdLGxu9YAA1QvwINks4PhcElQSvqcyVLLD9aMhXd13uQjoXtEKNosOWaZqXgel0g=="
        crossorigin="anonymous" referrerpolicy="no-referrer">

    <title>Contact Us ~ One Last Time</title>
    
</head>

<body class="bg" style="background-image:url('bgc.jpg'); background-size: 100% 100%; 
                background-position: center;">

    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">One Last Time</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="travel.html">Home</a></li>
                    <li class="nav-item"><a class="nav-link" href="place.html">Places</a></li>
                    <li class="nav-item"><a class="nav-link" href="packages.html">Packages</a></li>
                    <li class="nav-item"><a class="nav-link" href="book.html">Contact Us</a></li>
                </ul>
            </div> 
        </div>
    </nav>
    <div class="mt-5 container">
        <div class="row d-flex justify-content-between">
        <div class="col-lg-4  bg-secondary bg-opacity-25 mt-5 pt-3 ps-5 ms-4 pb-3 pe-5 me-5 pe-5 rounded float-start">
            <h1 class=" display-5 text-primary">Book Now</h1>
            <form action="" class="text-light">
                <div class="mb-3">
                    <label for="" class="form-label"> Name
                    </label>
                    <input type="text" class="form-control" minlength="3" placeholder="Enter Name" required>
                </div>
                <div class="mb-3">
                    <label for="" class="form-label"> Email
                    </label>
                    <input type="email" class="form-control" placeholder="Enter Email" required>
                </div>
                <div class="mb-3">
                    <label for="" class="form-label"> Phone Number
                    </label>
                    <input type="text" class="form-control" placeholder="Enter Number" maxlength="10" minlength="10"
                        required>
                </div>
                <div class="mb-3">
                    <label for="" class="form-label"> Enter Package Number
                    </label>
                    <input type="number" class="form-control" placeholder="Enter Number"  required>
                </div>
                <button type="submit" class="btn btn-primary">Book Now</button>
            </form>
        </div>
        <div class="col-lg-4  bg-secondary bg-opacity-25  pt-3 ps-5 pb-3 ms-5 pe-5 mt-5 rounded float-end"  >
           <div class="text-dark">
            <h1 class="display-5 text-primary">Contact Us</h1>
            <h3 class="mt-5">One Last Time</h3>
            <h5 class="mt-4"> <i class="fa-solid fa-phone text-primary"></i>+919123456780</h5>
            <h5 class="mt-4"><a href="" class="nav-link"><i class="fa-solid fa-envelope text-primary"></i> support@onelasttime.com</a></h5>
            <h5 class="mt-4"><i class="fa-solid fa-location-dot text-primary"></i> 123, ABC Colony,</h5>
            <h5>&emsp;XYZ Street,</h5>
            <h5>&emsp;Chennai-600000.</h5>
           </div>
        </div>
    </div>
    </div>
    
    <footer class="text-light pt-4">
        <div class="container-fluid bg-dark bg-opacity-50 text-center text-md-left mt-5">
            <div class="row">
                <div class="footer-pad">Designed with <i class="fa-solid fa-heart text-danger"></i> by Venkatachalam S
                </div>
            </div>
        </div>
    </footer>
</body>

</html>
```

## OUTPUT:
![alt text](<Screenshot 2024-12-25 092341.png>) 
![alt text](<Screenshot 2024-12-25 092402.png>) 
![alt text](<Screenshot 2024-12-25 092459.png>) 
![alt text](<Screenshot 2024-12-25 092506.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
