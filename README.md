<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta2/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-BmbxuPwQa2lc/FVzBcNJ7UAyJxM6wuqIj61tLrc4wSX0szH/Ev+nYRRuWlolflfl"
      crossorigin="anonymous"
    />
  </head>
  <body class="bg-secondary">
    <!-- <div class="container">
      <div class="row text-center">
        <div class="col-md-4 bg-warning">hello</div>
        <div class="col-md-4 offset-md-1 bg-light">hello</div>
        <div class="col-md-10 offset-md-2 bg-danger">hello</div>
      </div>
    </div> -->
    <div
      id="carouselExampleIndicators"
      class="carousel slide"
      data-bs-ride="carousel"
    >
      <div class="carousel-indicators">
        <button
          type="button"
          data-bs-target="#carouselExampleIndicators"
          data-bs-slide-to="0"
          class="active"
          aria-current="true"
          aria-label="Slide 1"
        ></button>
        <button
          type="button"
          data-bs-target="#carouselExampleIndicators"
          data-bs-slide-to="1"
          aria-label="Slide 2"
        ></button>
        <button
          type="button"
          data-bs-target="#carouselExampleIndicators"
          data-bs-slide-to="2"
          aria-label="Slide 3"
        ></button>
      </div>
      <div class="carousel-inner bg-dark">
        <div class="carousel-item active">
          <div class="w-75 mx-auto py-5">
            <div class="row">
              <div class="col-md-4 p-5">
                <div class="p-5 bg-light">hello</div>
              </div>
              <div class="col-md-4 p-5">
                <div class="p-5 bg-light">hello</div>
              </div>
              <div class="col-md-4 p-5">
                <div class="p-5 bg-light">hello</div>
              </div>
            </div>
          </div>
        </div>
        <div class="carousel-item">
          <div class="w-75 mx-auto py-5">
            <div class="row">
              <div class="col-md-4 p-5">
                <div class="p-5 bg-light">hello</div>
              </div>
              <div class="col-md-4 p-5">
                <div class="p-5 bg-light">hello</div>
              </div>
              <div class="col-md-4 p-5">
                <div class="p-5 bg-light">hello</div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <button
        class="carousel-control-prev"
        type="button"
        data-bs-target="#carouselExampleIndicators"
        data-bs-slide="prev"
      >
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button
        class="carousel-control-next"
        type="button"
        data-bs-target="#carouselExampleIndicators"
        data-bs-slide="next"
      >
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>

    <script
      src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta2/dist/js/bootstrap.bundle.min.js"
      integrity="sha384-b5kHyXgcpbZJO/tY9Ul7kGkf1S0CWuKcCD38l8YkeH8z8QjE0GmW1gYU5S9FOnJ0"
      crossorigin="anonymous"
    ></script>
  </body>
</html>
