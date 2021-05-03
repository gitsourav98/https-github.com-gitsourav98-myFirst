# https-github.com-gitsourav98-myFirst
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/css/bootstrap.min.css" 
    rel="stylesheet" integrity="sha384-eOJMYsd53ii+scO/bJGFsiCZc+5NDVN2yr8+0RDqr0Ql0h+rP48ckxlpbzKgwra6" 
    crossorigin="anonymous">
    <script src="https://kit.fontawesome.com/yourcode.js" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css"
     crossorigin="anonymous">
    <link rel="stylesheet" href="Ecom.css">
    <title>E-comerce</title>
</head>
<body>
    <header>
      <!--for navbar-->
        <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
            <div class="container-fluid">
              <a class="navbar-brand" href="#">
                <img src="./Elogo1C.jpg" alt="" width="30" height="30" class="d-inline-block align-text-top">
                <span>Webikart</span></a>
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent"
               aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                  <li class="nav-item">
                    <a class="nav-link active" aria-current="page" href="#">Home</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link active" aria-current="page" href="#">About Us</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link active" aria-current="page" href="#">Contact Us</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link active" aria-current="page" href="#">FAQ'S</a>
                  </li>
                  <!-- <li class="nav-item">
                    <a class="nav-link" href="#">Link</a>
                  </li> -->
                  <!-- <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                      Dropdown
                    </a>
                    <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                      <li><a class="dropdown-item" href="#">Action</a></li>
                      <li><a class="dropdown-item" href="#">Another action</a></li>
                      <li><hr class="dropdown-divider"></li>
                      <li><a class="dropdown-item" href="#">Something else here</a></li>
                    </ul>
                  </li> -->
                  <!-- <li class="nav-item">
                    <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Disabled</a>
                  </li> -->
                </ul>
                <form class="d-flex">
                   <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                  <button class="btn btn-outline-success" type="submit">Search</button>
                  
                </form> &nbsp;
                <button class="btn btn-warning"><strong>Cart</strong><span class="badge bg-secondary">0</span></button>
                
              </div>
            </div>
          </nav>
    </header>
    <div class="container">
      <img src="./1.jpeg" alt="This a Picture" class="img-fluid">
      <div class="centered">
          <h1>
              Welcome to Webikart
          </h1>
          <h3>
              Your Most Trustworthy E-Commerce Website
          </h3>
          <button class="SignUp btn-secondary"><a href="./login.html" rel="noopener noreferrer">Sign Up</a></button>
          <button class="LogIn btn-secondary"><a href="./login.html" rel="noopener noreferrer">Login</a></button>
      </div>
    </div>
    <!-- <div class="row row-cols-1 row-cols-md-3 g-3">
      <div class="col">
        <div class="card">
          <img src="./Apple 7.jpg" class="card-img-top" width="30" height="300" alt="...">
          <div class="card-body">
            <h5 class="card-title">Apple iphone7</h5>
            <p class="card-text"><Price:1>48599.00</Price:1></p>
            <button class="buy btn-primary">Buy Me</button>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card">
          <img src="./Apple-iPhone-11.jpg" class="card-img-top" width="30" height="300" alt="...">
          <div class="card-body">
            <h5 class="card-title">Apple iphone11</h5>
            <p class="card-text"><Price:1>70999.00</Price:1></p>
            <button class="buy btn-primary">Buy Me</button>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card">
          <img src="./One Plus.jpg" class="card-img-top" width="30" height="300" alt="...">
          <div class="card-body">
            <h5 class="card-title">One Plus</h5>
            <p class="card-text"><Price:1>29999.00</Price:1></p>
            <button class="buy btn-primary">Buy Me</button>
        </div>
      </div>
    
      <div class="col">
        <div class="card">
          <img src="./Oppo A53.jpg" class="card-img-top" width="30" height="300" alt="...">
          <div class="card-body">
            <h5 class="card-title">Oppo A53</h5>
            <p class="card-text"><Price:1>23999.00</Price:1></p>
            <button class="buy btn-primary">Buy Me</button>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card">
          <img src="./Vivo 5G.jpg" class="card-img-top" width="30" height="300" alt="...">
          <div class="card-body">
            <h5 class="card-title">Vivo 5G</h5>
            <p class="card-text"><Price:1>46999.00</Price:1></p>
            <button class="buy btn-primary">Buy Me</button>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card">
          <img src="./Nokia.png" class="card-img-top" width="30" height="300" alt="...">
          <div class="card-body">
            <h5 class="card-title">Nokia</h5>
            <p class="card-text"><Price:1>25999.00</Price:1></p>
            <button class="buy btn-primary">Buy Me</button>
          </div>
        </div>
      </div>
    </div> -->
   <!-- ------------------------------------->
     
    <div class="row row-cols-1 row-cols-md-3 g-4">
        <div class="col">
          <div class="card h-100">
            <img src="./Apple 7.jpg" class="card-img-top" height="350px" width="30px" alt="...">
            <div class="card-body">
              <h5 class="card-title">Apple iphone7</h5>
              <p class="card-text"><Price:1>₹25999.00</Price:1></p>
              <button class="btn btn-primary btn-sm" type="button">Details</button>
            </div>
            <div class="card-footer">
              <button class="btn btn-primary">Buy Me</button>
              <button class="btn btn-secondary">Add to Cart</button>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card h-100">
            <img src="./Apple-iPhone-11.jpg" class="card-img-top" height="350px" width="30px" alt="...">
            <div class="card-body">
              <h5 class="card-title">Apple iphone11</h5>
              <p class="card-text"><Price:1>₹25999.00</Price:1></p>
              <button class="btn btn-primary btn-sm" type="button">Details</button>
            </div>
            <div class="card-footer">
              <button class="btn btn-primary">Buy Me</button>
              <button class="btn btn-secondary">Add to Cart</button>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card h-100">
            <img src="./Nokia.png" class="card-img-top" height="350px" width="30px" alt="...">
            <div class="card-body">
              <h5 class="card-title">Nokia</h5>
              <p class="card-text"><Price:1>₹25999.00</Price:1></p>
              <button class="btn btn-primary btn-sm" type="button">Details</button>
            </div>
            <div class="card-footer">
              <button class="btn btn-primary">Buy Me</button>
              <button class="btn btn-secondary">Add to Cart</button>
            </div>
          </div>
        </div>
      </div>
   
      <div class="row row-cols-1 row-cols-md-3 g-4">
        <div class="col">
          <div class="card h-100">
            <img src="./One Plus.jpg" class="card-img-top" height="350px" width="30px" alt="...">
            <div class="card-body">
              <h5 class="card-title">One Plus</h5>
              <p class="card-text"><Price:1>₹25999.00</Price:1></p>
              <button class="btn btn-primary btn-sm" type="button">Details</button>
            </div>
            <div class="card-footer">
              <button class="btn btn-primary">Buy Me</button>
              <button class="btn btn-secondary">Add to Cart</button>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card h-100">
            <img src="./Oppo A53.jpg" class="card-img-top" height="350px" width="30px" alt="...">
            <div class="card-body">
              <h5 class="card-title">Oppo A53</h5>
              <p class="card-text"><Price:1>₹25999.00</Price:1></p>
              <button class="btn btn-primary btn-sm" type="button">Details</button>
            </div>
            <div class="card-footer">
              <button class="btn btn-primary">Buy Me</button>
              <button class="btn btn-secondary">Add to Cart</button>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card h-100">
            <img src="./Vivo 5G.jpg" class="card-img-top" height="350px" width="30px" alt="...">
            <div class="card-body">
              <h5 class="card-title">Vivo 5G</h5>
              <p class="card-text"><Price:1>₹25999.00</Price:1> </p>
              <button class="btn btn-primary btn-sm" type="button">Details</button>
            </div>
            <div class="card-footer">
              <button class="btn btn-primary">Buy Me</button>
              <button class="btn btn-secondary">Add to Cart</button>
            </div>
          </div>
        </div>
      </div>
    <footer>
      <h5>About Us:</h5>
      <p class="AboutUs">Lorem ipsum dolor sit amet consectetur adipisicing elit.
         Aliquam cumque minima porro quo vero suscipit sed nemo quasi sequi amet.
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatem officia cumque hic nihil cum, 
        laboriosam explicabo sed quos animi nesciunt dolore odit quisquam, 
        repellendus atque deleniti tempora. Iure, dolorem officia.</p>
        <h5>Contact Us:</h5>
        <div class="social">
          <a href="https://www.facebook.com/profile.php?id=100009917104341" target="_blank"><i class="fa fa-facebook" aria-hidden="true" ></i></a>
          <a href="#" target="_blank"><i class="fa fa-envelope" aria-hidden="true" ></i></a>
          <a href="#" target="_blank"><i class="fa fa-linkedin" aria-hidden="true"></i></a>
          
      </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/js/bootstrap.bundle.min.js" 
    integrity="sha384-JEW9xMcG8R+pH31jmWH6WWP0WintQrMb4s7ZOdauHnUtxwoG2vI5DkLtS3qm9Ekf"
     crossorigin="anonymous"></script>
</body>
</html>
