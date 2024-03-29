# EX01 Developing a Simple Webserver
## Date:
29|03|24

## AIM:
To develop a simple webserver to serve html pages.

## DESIGN STEPS:
### Step 1: 
HTML content creation.

### Step 2:
Design of webserver workflow.

### Step 3:
Implementation using Python code.

### Step 4:
Serving the HTML pages.

### Step 5:
Testing the webserver.

## PROGRAM:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
</head>
<body>
    <div class="card" style="width: 18rem;">
        <img src="MOON.png" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">space</h5>
          <p class="card-text">space is a endless journey around the universe.</p>
          <a href="#" class="btn btn-primary">Go somewhere</a>
        </div>
        <div><div class="card" style="width: 18rem;">
          <img src="vijay.png" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title">Thalapathy Vijay</h5>
            <p class="card-text">Thalapathy Vijay has started his own political party called TVK.</p>
            <a href="#" class="btn btn-primary">Go somewhere</a>
          </div>
          <div class="card" style="width: 18rem;">
            <img src="taylor and travis.png" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Taylor</h5>
              <p class="card-text">Taylor and Travis are exclusively dating.</p>
              <a href="#" class="btn btn-primary">Go somewhere</a>
            </div></div>
            </div>
          </div>
      </div>
    <div id="carouselExampleIndicators" class="carousel slide">
        <div class="carousel-indicators">
          <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
          <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
          <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
        </div>
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="galaxy.png" class="d-block w-100" alt="...">
          </div>
          <div class="carousel-item">
            <img src="earth.png" class="d-block w-100" alt="...">
          </div>
          <div class="carousel-item">
            <img src="astronaut.png" class="d-block w-100" alt="...">
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
      </div>
</body>
</html>


## OUTPUT:
![alt text](<output 1.png>) ![alt text](<output 2.png>) ![alt text](<output 3.png>) ![alt text](<output 4.png>) ![alt text](<output 5.png>)


## RESULT:
The program for implementing simple webserver is executed successfully.
