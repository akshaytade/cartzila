# cartzila
first webpage
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> cartzilla.createx.studio/</title>
    <link rel="icon" href="avatar.png" type="image/icon type"> 
</head>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script> 
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css">
<script src="https://code.jquery.com/jquery-3.5.1.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js"></script> 
<link rel="stylesheet" href="cartzilla.css">
<style>
    .dropdown:hover .dropdown-menu{
        display: block;
    }
    .dropdown-menu{
        margin-top: 0;
    }
</style>
<script>
$(document).ready(function(){
    $(".dropdown").hover(function(){
        var dropdownMenu = $(this).children(".dropdown-menu");
        if(dropdownMenu.is(":visible")){
            dropdownMenu.parent().toggleClass("open");
        }
    });
});     
</script>
<body>
    <nav class="navbar navbar-expand-lg bg-light sticky-top">
        <div class="container-fluid"><br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
          <a class="navbar-brand" href="https://cartzilla.createx.studio/index.html"><img src="logo.png" height="35px" width="150px"></a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
            <div class="navbar-nav">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                <div class="nav-item dropdown">
                    <a href="#" class="nav-link dropdown-toggle" data-toggle="dropdown" style="color: black;">
                         <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-geo-alt" viewBox="0 0 16 16">
                      <path d="M12.166 8.94c-.524 1.062-1.234 2.12-1.96 3.07A31.493 31.493 0 0 1 8 14.58a31.481 31.481 0 0 1-2.206-2.57c-.726-.95-1.436-2.008-1.96-3.07C3.304 7.867 3 6.862 3 6a5 5 0 0 1 10 0c0 .862-.305 1.867-.834 2.94zM8 16s6-5.686 6-10A6 6 0 0 0 2 6c0 4.314 6 10 6 10z"/>
                      <path d="M8 8a2 2 0 1 1 0-4 2 2 0 0 1 0 4zm0 1a3 3 0 1 0 0-6 3 3 0 0 0 0 6z"/>
                    </svg>&nbsp;&nbsp;New York</a>
                    <div class="dropdown-menu">    
                        <li class="dropdown-item">Los Angeles</li>
                        <li class="dropdown-item">Chicago</li>
                        <li class="dropdown-item">Houston</li>
                        <li class="dropdown-item">Philadelphia</li>
                        <li class="dropdown-item">San Diego</li>
                        <li class="dropdown-item">Miami</li>
                      </ul>
                    </div>   
                  </div>
                  &nbsp;&nbsp;&nbsp;
                  <div class="vr">
                  </div>&nbsp;&nbsp;&nbsp;
                  <div class="nav-item dropdown">
                    <a href="#" class="nav-link dropdown" data-toggle="dropdown"  style="color: black;"> 
                    Cuisine</a>
                    <div class="dropdown-menu">  
                      <div class="card-group">
                        <div class="card">
                          <img src="burger.svg" height="50px" width="50px" class="card-img-top" alt="...">
                          <div class="card-body">
                            <h5 class="card-title"<center>Burgers & Fries</center></h5>
                          </div>
                        </div>
                        <div class="card">
                          <img src="noodles.svg" height="50px" width="50px" class="card-img-top" alt="...">
                          <div class="card-body">
                            <h5 class="card-title"><center>Noodles</center></h5>
                            </div>
                        </div>
                        <div class="card">
                          <img src="pizza.svg" height="50px" width="50px" class="card-img-top" alt="...">
                          <div class="card-body">
                            <h5 class="card-title"><center>Pizza & Pasta</center></h5>
                            </div>
                        </div>
                      </div>
                      <div class="card-group">
                        <div class="card">
                          <img src="steak.svg" height="50px" width="50px" class="card-img-top" alt="...">
                          <div class="card-body">
                            <h5 class="card-title"><center>Grill & Steaks</center></h5>
                          </div>
                        </div>
                        <div class="card">
                          <img src="fish.svg" height="50px" width="50px" class="card-img-top" alt="...">
                          <div class="card-body">
                            <h5 class="card-title"><center>Fish & Seafood</center></h5>
                            </div>
                        </div>
                        <div class="card">
                          <img src="healthy.svg" height="50px" width="50px" class="card-img-top" alt="...">
                          <div class="card-body">
                            <h5 class="card-title"><center>Healthy Food</center></h5>
                            </div>
                        </div>
                      </div>
                      <div class="card-group">
                        <div class="card">
                          <img src="cuisine.svg" height="50px" width="50px" class="card-img-top" alt="...">
                          <div class="card-body">
                            <h5 class="card-title"><center>Haute Cuisine</center></h5>
                          </div>
                        </div>
                        <div class="card">
                          <img src="chicken.svg" height="50px" width="50px" class="card-img-top" alt="...">
                          <div class="card-body">
                            <h5 class="card-title"><center>Chicken & Snaks</center></h5>
                            </div>
                        </div>
                        <div class="card">
                          <img src="coffee.svg" height="50px" width="50px" class="card-img-top" alt="...">
                          <div class="card-body">
                            <h5 class="card-title"><center>Coffee & Desserts</center></h5>
                            </div>
                        </div>
                      </div>
                      
                            <li class="dropdown-item">
                              <div class="d-flex justify-content-center">
                                <center>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                                  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                                </center>
                                <center>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                                  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                                </center>
                              <center>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                                &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 
                              </center>
                              </div>
                            </li>
                    </div>   
                  </div>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                  <li class="nav-item">
                    <a class="nav-link active" aria-current="page" href="https://cartzilla.createx.studio/index.html" style="color: black;">Back to main demo</a>
                  </li>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                  <li class="nav-item">
                    <a class="nav-link active" aria-current="page" href="#" style="color: black;"><img src="mag.png" alt=""></a>
                  </li>
                  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                     <a class="nav-link" href="#" style="color: black;"><img src="icons8-person-32.png" height="30px" width="30px" ></a>
                  </div>
            </div>
          </div>
        </div>
      </nav>
      <div class="sub1">
        <div style="color: white; margin-left: 80px;"><br><br><br>
        <img src="hom-removebg-preview.png" height="30px" width="30px"><a href="https://cartzilla.createx.studio/index.html">Home</a>
        <img src="icon-4-removebg-preview.png" height="30px" width="30px"><a href="">All Categoris</a><img src="icon_5-removebg-preview.png" height="30px" width="30px">Burger & Frice
            <br><h1><b>Burger & Frice</b></h1>
    </div>
    <img class="seti" src="burger2.png" height="250px" width="340px">
    </div><br><br>
    <div class="card-group">
        <div class="card">
          <img src="burger.svg" height="50px" width="50px" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title"><center>Burgers & Fries</center></h5>
          </div>
        </div>
        <div class="card">
          <img src="noodles.svg" height="50px" width="50px" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title"><center>Noodles</center></h5>
            </div>
        </div>
        <div class="card">
          <img src="pizza.svg" height="50px" width="50px" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title"><center>Pizza & Pasta</center></h5>
            </div>
        </div>
        <div class="card">
          <img src="steak.svg" height="50px" width="50px" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title"><center>Grill & Steaks</center></h5>
          </div>
        </div>
        <div class="card">
          <img src="fish.svg" height="50px" width="50px" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title"><center>Fish & Seafood</center></h5>
            </div>
        </div>
        <div class="card">
          <img src="healthy.svg" height="50px" width="50px" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title"><center>Healthy Food</center></h5>
            </div>
        </div>
        <div class="card">
          <img src="cuisine.svg" height="50px" width="50px" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title"><center>Haute Cuisine</center></h5>
          </div>
        </div>
        <div class="card">
          <img src="chicken.svg" height="50px" width="50px" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title"><center>Chicken & Snaks</center></h5>
            </div>
        </div>
        <div class="card">
          <img src="coffee.svg" height="50px" width="50px" class="card-img-top" alt="...">
          <div class="card-body">
            <h5 class="card-title"><center>Coffee & Desserts</center></h5>
            </div>
        </div>
      </div><br>
      <div class="shadow mc1" style="margin-left: 30px;" >
       <img src="011.jpg" height="260px" width="380px" style="border-radius: 20px;">
        <center><img style="margin-top: -30px;" src="01.png" height="90px" width="170px"><br><h4>McDonald's</h4>Burger Salad French Frice & Drinks</center>
        </div>
        <div class="shadow mc1" style="margin-left: 490px; margin-top: -400px;" >
            <img src="012.jpg" height="260px" width="380px" style="border-radius: 20px;">
             <center><img style="margin-top: -30px;" src="02.png" height="90px" width="170px"><br><h4>Kentucky Fried Chiken</h4>Fried Chiken, Burgers,Sandwiches,French Fries</center>
             </div>
             <div class="shadow mc1" style="margin-left: 950px;  margin-top: -400px;" >
                <img src="013.jpg" height="260px" width="380px" style="border-radius: 20px;">
                 <center><img style="margin-top: -30px;" src="03.png" height="90px" width="170px"><br><h4>Burger King</h4>Burger Salad French Frice & Drinks</center>
                 </div><br>
                 <div class="shadow mc1" style="margin-left: 30px;" >
       <img src="014.jpg" height="260px" width="380px" style="border-radius: 20px;">
        <center><img style="margin-top: -30px;" src="04.png" height="90px" width="170px"><br><h4> Logan's Roadhouse</h4>Grill,Steaks,Burger Salad French Frice & Drinks</center>
        </div>
        <div class="shadow mc1" style="margin-left: 490px; margin-top: -400px;" >
            <img src="015.jpg" height="260px" width="380px" style="border-radius: 20px;">
             <center><img style="margin-top: -30px;" src="05.png" height="90px" width="170px"><br><h4>Carrabba's</h4>Grill,Sreaks,Burger Salad French Frice & Drinks</center>
             </div>
             <div class="shadow mc1" style="margin-left: 950px;  margin-top: -400px;" >
                <img src="016.jpg" height="260px" width="380px" style="border-radius: 20px;">
                 <center><img style="margin-top: -30px;" src="06.png" height="90px" width="170px"><br><h4>Bonefish Grill</h4>Grill,Fish,Burger Salad French Frice & Drinks</center>
                 </div><br>
                 <div class="shadow mc1" style="margin-left: 30px;" >
       <img src="017.jpg" height="260px" width="380px" style="border-radius: 20px;">
        <center><img style="margin-top: -30px;" src="07.png" height="90px" width="170px"><br><h4>Domino's Pizza</h4>Pizza,Burger Salad French Frice & Drinks</center>
        </div>
        <div class="shadow mc1" style="margin-left: 490px; margin-top: -400px;" >
            <img src="018.jpg" height="260px" width="380px" style="border-radius: 20px;">
             <center><img style="margin-top: -30px;" src="08.png" height="90px" width="170px"><br><h4>Hardee's</h4>Burger Salad French Frice & Drinks</center>
             </div>
             <div class="shadow mc1" style="margin-left: 950px;  margin-top: -400px;" >
                <img src="019.jpg" height="260px" width="380px" style="border-radius: 20px;">
                 <center><img style="margin-top: -30px;" src="09.png" height="90px" width="170px"><br><h4>Ruth's Chris Steak House</h4>Grill,Steaks,Burger Salad French Frice & Drinks</center>
                 </div><br>
                 
                 <div class="footer">
                  <div style="margin-left: 50px;"><br><br><br>
                    <h3 style="color: white; ">Cartzilla</h3>
                    <div class="dropdown">
                      <button class="btn btn-secondary dropdown-toggle" type="button" id="dropdownMenuButton1" data-bs-toggle="dropdown" aria-expanded="false">
                        <img src="en.png">Eng/$
                      </button>
                      <ul class="dropdown-menu" aria-labelledby="dropdownMenuButton1">
                        <li><a class="dropdown-item" href="#"><img src="fr.png">Francais</a></li>
                        <li><a class="dropdown-item" href="#"><img src="de.png">Deutsch</a></li>
                        <li><a class="dropdown-item" href="#"><img src="it.png">Italiano</a></li>
                      </ul>
                    </div>
                  </div>
                  <div style="margin-left: 270px; margin-top: -90px;">
                    <div style="color: white;">
                      <h4>Joint Us</h4>
                      Carrers <br>
                      Restaurants <br>
                      Become a Courior <br>
                      About
                    </div>
                   </div>
                   <div style="margin-left: 500px; margin-top: -130px; color: white;">
                    <h4>Let us help you</h4>
                    Help Center <br>
                    Support <br>
                    Contacts
                   </div>
                   <div style="margin-left: 750px; margin-top: -105px; color: white;">
                  <h4>Follow us</h4>
                  Facebook <br>
                  Twitter <br>
                    Instagram
                  </div>
                  <div style="margin-left: 950px; margin-top: -105px; color: white;">
                  <h4>Download our App</h4>
                  <a href="https://play.google.com/store/search?q=dmart+ready+online+grocery+shopping&c=apps">
                    <img src="play.svg" height="70px" width="140px"></a>
                  <img src="store.svg"  height="70px" width="140px"><br>
                  </div><br><br><br>
                  <hr style="color: white;"><br>
                  <div style="margin-left: 40px; color: white;">
                  @All rights reversed. Made by Akshay Tade
                  </div>
                  <div style="margin-left: 900px; margin-top: -20px; color: white;">
                    <h6>Privacy policy &nbsp;&nbsp;&nbsp; Terms & conditions &nbsp;&nbsp;&nbsp; Cookis Policy</h6>
                  
                  </div>
                </div>
             
</body>
</html>
