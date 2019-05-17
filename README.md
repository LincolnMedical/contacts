/* FontAwesome for working BootSnippet :> */

@import url('https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css');
#team {
    background: #eee !important;
}

.btn-primary:hover,
.btn-primary:focus {
    background-color: #108d6f;
    border-color: #108d6f;
    box-shadow: none;
    outline: none;
}

.btn-primary {
    color: #fff;
    background-color: #007b5e;
    border-color: #007b5e;
}

section {
    padding: 60px 0;
}

section .section-title {
    text-align: center;
    color: #007b5e;
    margin-bottom: 50px;
    text-transform: uppercase;
}

#team .card {
    border: none;
    background: #ffffff;
}

.image-flip:hover .backside,
.image-flip.hover .backside {
    -webkit-transform: rotateY(0deg);
    -moz-transform: rotateY(0deg);
    -o-transform: rotateY(0deg);
    -ms-transform: rotateY(0deg);
    transform: rotateY(0deg);
    border-radius: .25rem;
}

.image-flip:hover .frontside,
.image-flip.hover .frontside {
    -webkit-transform: rotateY(180deg);
    -moz-transform: rotateY(180deg);
    -o-transform: rotateY(180deg);
    transform: rotateY(180deg);
}

.mainflip {
    -webkit-transition: 1s;
    -webkit-transform-style: preserve-3d;
    -ms-transition: 1s;
    -moz-transition: 1s;
    -moz-transform: perspective(1000px);
    -moz-transform-style: preserve-3d;
    -ms-transform-style: preserve-3d;
    transition: 1s;
    transform-style: preserve-3d;
    position: relative;
}

.frontside {
    position: relative;
    -webkit-transform: rotateY(0deg);
    -ms-transform: rotateY(0deg);
    z-index: 2;
    margin-bottom: 30px;
}

.backside {
    position: absolute;
    top: 0;
    left: 0;
    background: white;
    -webkit-transform: rotateY(-180deg);
    -moz-transform: rotateY(-180deg);
    -o-transform: rotateY(-180deg);
    -ms-transform: rotateY(-180deg);
    transform: rotateY(-180deg);
    -webkit-box-shadow: 5px 7px 9px -4px rgb(158, 158, 158);
    -moz-box-shadow: 5px 7px 9px -4px rgb(158, 158, 158);
    box-shadow: 5px 7px 9px -4px rgb(158, 158, 158);
}

.frontside,
.backside {
    -webkit-backface-visibility: hidden;
    -moz-backface-visibility: hidden;
    -ms-backface-visibility: hidden;
    backface-visibility: hidden;
    -webkit-transition: 1s;
    -webkit-transform-style: preserve-3d;
    -moz-transition: 1s;
    -moz-transform-style: preserve-3d;
    -o-transition: 1s;
    -o-transform-style: preserve-3d;
    -ms-transition: 1s;
    -ms-transform-style: preserve-3d;
    transition: 1s;
    transform-style: preserve-3d;
}

.frontside .card,
.backside .card {
    min-height: 312px;
}

.backside .card a {
    font-size: 18px;
    color: #007b5e !important;
}

.frontside .card .card-title,
.backside .card .card-title {
    color: #007b5e !important;
}

.frontside .card .card-body img {
    width: 120px;
    height: 120px;
    border-radius: 50%;
}


<link href="//maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" id="bootstrap-css" rel="stylesheet" />
<script src="//maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js">
</script>
<script src="//cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js">
</script><!------ Include the above in your HEAD tag ----------><!-- Team -->
<section class="pb-5" id="team">
  <div class="container">
    <h5 class="section-title h1">OUR STAFF
    </h5>
    <h5 class="section-title h1"> 
    </h5>
    <div class="row"><!-- Team member -->
      <div class="col-xs-12 col-sm-6 col-md-4">
        <div class="image-flip" ontouchstart="this.classList.toggle('hover');">
          <div class="mainflip">
            <div class="frontside">
              <div class="card">
                <div class="card-body text-center">
                  <p><img alt="card image" class="img-fluid" height="296" src="https://staff.lincoln.ac.uk/profile/image/ranker" width="222" />
                  </p>
                  <h4 class="card-title">Rick Anker
                  </h4>
                  <p class="card-text">This is basic card with image on top, title, description and button.
                  </p>
                  <a class="btn btn-primary btn-sm" href="#"><i class="fa fa-plus"></i></a>
                </div>
              </div>
            </div>
            <div class="backside">
              <div class="card">
                <div class="card-body text-center mt-4">
                  <h4 class="card-title">Sunlimetech
                  </h4>
                  <p class="card-text">This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.
                  </p>
                  <ul class="list-inline">
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-facebook"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-twitter"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-skype"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-google"></i> </a></li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- ./Team member --><!-- Team member -->
      <div class="col-xs-12 col-sm-6 col-md-4">
        <div class="image-flip" ontouchstart="this.classList.toggle('hover');">
          <div class="mainflip">
            <div class="frontside">
              <div class="card">
                <div class="card-body text-center">
                  <p><img alt="card image" class="img-fluid" src="https://www.lincoln.ac.uk/home/media/responsive2017/collegeofscience/medicalschool/Jill,Pinner,Profile,Image.jpg" />
                  </p>
                  <h4 class="card-title">Laura Bennett
                  </h4>
                  <p class="card-text">This is basic card with image on top, title, description and button.
                  </p>
                  <a class="btn btn-primary btn-sm" href="#"><i class="fa fa-plus"></i></a>
                </div>
              </div>
            </div>
            <div class="backside">
              <div class="card">
                <div class="card-body text-center mt-4">
                  <h4 class="card-title">Sunlimetech
                  </h4>
                  <p class="card-text">This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.
                  </p>
                  <ul class="list-inline">
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-facebook"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-twitter"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-skype"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-google"></i> </a></li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- ./Team member --><!-- Team member -->
      <div class="col-xs-12 col-sm-6 col-md-4">
        <div class="image-flip" ontouchstart="this.classList.toggle('hover');">
          <div class="mainflip">
            <div class="frontside">
              <div class="card">
                <div class="card-body text-center">
                  <p><img alt="card image" class="img-fluid" src="https://www.lincoln.ac.uk/home/media/responsive2017/collegeofscience/medicalschool/Alistair,Warren,Profile,Image.jpg" />
                  </p>
                  <h4 class="card-title">Kerry Blagden
                  </h4>
                  <p class="card-text">This is basic card with image on top, title, description and button.
                  </p>
                  <a class="btn btn-primary btn-sm" href="#"><i class="fa fa-plus"></i></a>
                </div>
              </div>
            </div>
            <div class="backside">
              <div class="card">
                <div class="card-body text-center mt-4">
                  <h4 class="card-title">Sunlimetech
                  </h4>
                  <p class="card-text">This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.
                  </p>
                  <ul class="list-inline">
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-facebook"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-twitter"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-skype"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-google"></i> </a></li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- ./Team member --><!-- Team member -->
      <div class="col-xs-12 col-sm-6 col-md-4">
        <div class="image-flip" ontouchstart="this.classList.toggle('hover');">
          <div class="mainflip">
            <div class="frontside">
              <div class="card">
                <div class="card-body text-center">
                  <p><img alt="card image" class="img-fluid" src="https://www.lincoln.ac.uk/home/media/responsive2017/collegeofscience/medicalschool/Skantha,Spotlight.jpg" />
                  </p>
                  <h4 class="card-title">Max Bodmer
                  </h4>
                  <p class="card-text">This is basic card with image on top, title, description and button.
                  </p>
                  <a class="btn btn-primary btn-sm" href="#"><i class="fa fa-plus"></i></a>
                </div>
              </div>
            </div>
            <div class="backside">
              <div class="card">
                <div class="card-body text-center mt-4">
                  <h4 class="card-title">Sunlimetech
                  </h4>
                  <p class="card-text">This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.
                  </p>
                  <ul class="list-inline">
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-facebook"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-twitter"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-skype"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-google"></i> </a></li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- ./Team member --><!-- Team member -->
      <div class="col-xs-12 col-sm-6 col-md-4">
        <div class="image-flip" ontouchstart="this.classList.toggle('hover');">
          <div class="mainflip">
            <div class="frontside">
              <div class="card">
                <div class="card-body text-center">
                  <p><img alt="card image" class="img-fluid" src="https://www.lincoln.ac.uk/home/media/responsive2017/collegeofscience/medicalschool/Gill,Garden,Image.jpg" />
                  </p>
                  <h4 class="card-title">Ellie Davison
                  </h4>
                  <p class="card-text">This is basic card with image on top, title, description and button.
                  </p>
                  <a class="btn btn-primary btn-sm" href="#"><i class="fa fa-plus"></i></a>
                </div>
              </div>
            </div>
            <div class="backside">
              <div class="card">
                <div class="card-body text-center mt-4">
                  <h4 class="card-title">Sunlimetech
                  </h4>
                  <p class="card-text">This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.
                  </p>
                  <ul class="list-inline">
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-facebook"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-twitter"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-skype"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-google"></i> </a></li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- ./Team member --><!-- Team member -->
      <div class="col-xs-12 col-sm-6 col-md-4">
        <div class="image-flip" ontouchstart="this.classList.toggle('hover');">
          <div class="mainflip">
            <div class="frontside">
              <div class="card">
                <div class="card-body text-center">
                  <p><img alt="card image" class="img-fluid" src="https://www.lincoln.ac.uk/home/media/responsive2017/collegeofscience/medicalschool/Runa,Image.jpg" />
                  </p>
                  <h4 class="card-title">Ahmet Durgungoz
                  </h4>
                  <p class="card-text">This is basic card with image on top, title, description and button.
                  </p>
                  <a class="btn btn-primary btn-sm" href="#"><i class="fa fa-plus"></i></a>
                </div>
              </div>
            </div>
            <div class="backside">
              <div class="card">
                <div class="card-body text-center mt-4">
                  <h4 class="card-title">Sunlimetech
                  </h4>
                  <p class="card-text">This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.
                  </p>
                  <ul class="list-inline">
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-facebook"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-twitter"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-skype"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-google"></i> </a></li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- ./Team member --></div>
    <div class="row"><!-- Team member -->
      <div class="col-xs-12 col-sm-6 col-md-4">
        <div class="image-flip" ontouchstart="this.classList.toggle('hover');">
          <div class="mainflip">
            <div class="frontside">
              <div class="card">
                <div class="card-body text-center">
                  <p><img alt="card image" class="img-fluid" src="https://www.lincoln.ac.uk/home/media/responsive2017/collegeofscience/medicalschool/Danny,McLaughlin,Square.jpg" />
                  </p>
                  <h4 class="card-title">Gill Garden
                  </h4>
                  <p class="card-text">This is basic card with image on top, title, description and button.
                  </p>
                  <a class="btn btn-primary btn-sm" href="#"><i class="fa fa-plus"></i></a>
                </div>
              </div>
            </div>
            <div class="backside">
              <div class="card">
                <div class="card-body text-center mt-4">
                  <h4 class="card-title">Sunlimetech
                  </h4>
                  <p class="card-text">This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.
                  </p>
                  <ul class="list-inline">
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-facebook"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-twitter"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-skype"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-google"></i> </a></li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- ./Team member --><!-- Team member -->
      <div class="col-xs-12 col-sm-6 col-md-4">
        <div class="image-flip" ontouchstart="this.classList.toggle('hover');">
          <div class="mainflip">
            <div class="frontside">
              <div class="card">
                <div class="card-body text-center">
                  <p><img alt="card image" class="img-fluid" src="https://www.lincoln.ac.uk/home/media/responsive2017/collegeofscience/medicalschool/Jill,Pinner,Profile,Image.jpg" />
                  </p>
                  <h4 class="card-title">Laura Bennett
                  </h4>
                  <p class="card-text">This is basic card with image on top, title, description and button.
                  </p>
                  <a class="btn btn-primary btn-sm" href="#"><i class="fa fa-plus"></i></a>
                </div>
              </div>
            </div>
            <div class="backside">
              <div class="card">
                <div class="card-body text-center mt-4">
                  <h4 class="card-title">Sunlimetech
                  </h4>
                  <p class="card-text">This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.
                  </p>
                  <ul class="list-inline">
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-facebook"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-twitter"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-skype"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-google"></i> </a></li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- ./Team member --><!-- Team member -->
      <div class="col-xs-12 col-sm-6 col-md-4">
        <div class="image-flip" ontouchstart="this.classList.toggle('hover');">
          <div class="mainflip">
            <div class="frontside">
              <div class="card">
                <div class="card-body text-center">
                  <p><img alt="card image" class="img-fluid" src="https://www.lincoln.ac.uk/home/media/responsive2017/collegeofscience/medicalschool/Alistair,Warren,Profile,Image.jpg" />
                  </p>
                  <h4 class="card-title">Kerry Blagden
                  </h4>
                  <p class="card-text">This is basic card with image on top, title, description and button.
                  </p>
                  <a class="btn btn-primary btn-sm" href="#"><i class="fa fa-plus"></i></a>
                </div>
              </div>
            </div>
            <div class="backside">
              <div class="card">
                <div class="card-body text-center mt-4">
                  <h4 class="card-title">Sunlimetech
                  </h4>
                  <p class="card-text">This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.
                  </p>
                  <ul class="list-inline">
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-facebook"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-twitter"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-skype"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-google"></i> </a></li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- ./Team member --><!-- Team member -->
      <div class="col-xs-12 col-sm-6 col-md-4">
        <div class="image-flip" ontouchstart="this.classList.toggle('hover');">
          <div class="mainflip">
            <div class="frontside">
              <div class="card">
                <div class="card-body text-center">
                  <p><img alt="card image" class="img-fluid" src="https://www.lincoln.ac.uk/home/media/responsive2017/collegeofscience/medicalschool/Skantha,Spotlight.jpg" />
                  </p>
                  <h4 class="card-title">Max Bodmer
                  </h4>
                  <p class="card-text">This is basic card with image on top, title, description and button.
                  </p>
                  <a class="btn btn-primary btn-sm" href="#"><i class="fa fa-plus"></i></a>
                </div>
              </div>
            </div>
            <div class="backside">
              <div class="card">
                <div class="card-body text-center mt-4">
                  <h4 class="card-title">Sunlimetech
                  </h4>
                  <p class="card-text">This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.
                  </p>
                  <ul class="list-inline">
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-facebook"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-twitter"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-skype"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-google"></i> </a></li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- ./Team member --><!-- Team member -->
      <div class="col-xs-12 col-sm-6 col-md-4">
        <div class="image-flip" ontouchstart="this.classList.toggle('hover');">
          <div class="mainflip">
            <div class="frontside">
              <div class="card">
                <div class="card-body text-center">
                  <p><img alt="card image" class="img-fluid" src="https://www.lincoln.ac.uk/home/media/responsive2017/collegeofscience/medicalschool/Gill,Garden,Image.jpg" />
                  </p>
                  <h4 class="card-title">Ellie Davison
                  </h4>
                  <p class="card-text">This is basic card with image on top, title, description and button.
                  </p>
                  <a class="btn btn-primary btn-sm" href="#"><i class="fa fa-plus"></i></a>
                </div>
              </div>
            </div>
            <div class="backside">
              <div class="card">
                <div class="card-body text-center mt-4">
                  <h4 class="card-title">Sunlimetech
                  </h4>
                  <p class="card-text">This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.
                  </p>
                  <ul class="list-inline">
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-facebook"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-twitter"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-skype"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-google"></i> </a></li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- ./Team member --><!-- Team member -->
      <div class="col-xs-12 col-sm-6 col-md-4">
        <div class="image-flip" ontouchstart="this.classList.toggle('hover');">
          <div class="mainflip">
            <div class="frontside">
              <div class="card">
                <div class="card-body text-center">
                  <p><img alt="card image" class="img-fluid" src="https://www.lincoln.ac.uk/home/media/responsive2017/collegeofscience/medicalschool/Runa,Image.jpg" />
                  </p>
                  <h4 class="card-title">Ahmet Durgungoz
                  </h4>
                  <p class="card-text">This is basic card with image on top, title, description and button.
                  </p>
                  <a class="btn btn-primary btn-sm" href="#"><i class="fa fa-plus"></i></a>
                </div>
              </div>
            </div>
            <div class="backside">
              <div class="card">
                <div class="card-body text-center mt-4">
                  <h4 class="card-title">Sunlimetech
                  </h4>
                  <p class="card-text">This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.
                  </p>
                  <ul class="list-inline">
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-facebook"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-twitter"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-skype"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-google"></i> </a></li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- ./Team member --></div>
    <div class="row"><!-- Team member -->
      <div class="col-xs-12 col-sm-6 col-md-4">
        <div class="image-flip" ontouchstart="this.classList.toggle('hover');">
          <div class="mainflip">
            <div class="frontside">
              <div class="card">
                <div class="card-body text-center">
                  <p><img alt="card image" class="img-fluid" src="https://www.lincoln.ac.uk/home/media/responsive2017/collegeofscience/medicalschool/Danny,McLaughlin,Square.jpg" />
                  </p>
                  <h4 class="card-title">Jessica Hodgson
                  </h4>
                  <p class="card-text"><span class="fa fa-envelope"></span>  <span style="font-size:16px;"><a class="email" href="mailto:jhodgson@lincoln.ac.uk" style="background-image: initial; background-position: 0px 0px; background-size: initial; background-repeat: initial; background-attachment: initial; background-origin: initial; background-clip: initial; color: rgb(66, 139, 202);">jhodgson@lincoln.ac.uk</a></span>
                  </p>
                  <dl>
                    <dd 14px="" font-size:="" helvetica="" open="" style="line-height: 1.42857; color: rgb(51, 51, 51); font-family: "><span class="fa fa-phone"></span>  <a class="phone" href="tel:01522835084" style="background-image: initial; background-position: 0px 0px; background-size: initial; background-repeat: initial; background-attachment: initial; background-origin: initial; background-clip: initial; color: rgb(66, 139, 202);">01522 83 5084</a>
                    </dd>
                  </dl>
                  <a class="btn btn-primary btn-sm" href="#"><i class="fa fa-plus"></i></a>
                </div>
              </div>
            </div>
            <div class="backside">
              <div class="card">
                <div class="card-body text-center mt-4">
                  <h4 class="card-title">Sunlimetech
                  </h4>
                  <p class="card-text">This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.
                  </p>
                  <ul class="list-inline">
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-facebook"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-twitter"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-skype"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-google"></i> </a></li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- ./Team member --><!-- Team member -->
      <div class="col-xs-12 col-sm-6 col-md-4">
        <div class="image-flip" ontouchstart="this.classList.toggle('hover');">
          <div class="mainflip">
            <div class="frontside">
              <div class="card">
                <div class="card-body text-center">
                  <p><img alt="card image" class="img-fluid" src="https://www.lincoln.ac.uk/home/media/responsive2017/collegeofscience/medicalschool/Jill,Pinner,Profile,Image.jpg" />
                  </p>
                  <h4 class="card-title">Aiden Jayanth
                  </h4>
                  <p><span class="fa fa-envelope"></span>  <a class="email" href="mailto:jhodgson@lincoln.ac.uk" style="color: rgb(66, 139, 202); background: 0px 0px rgb(255, 255, 255); text-align: center;">ajayanth@lincoln.ac.uk</a>
                  </p>
                  <p><span class="fa fa-phone"></span><span font-size:="" helvetica="" open="" style="color: rgb(51, 51, 51); font-family: ">  </span><a class="phone" font-size:="" helvetica="" href="tel:01522835084" open="" style="color: rgb(66, 139, 202); text-decoration-line: underline; background: 0px 0px rgb(255, 255, 255); font-family: ">01522 83 5084</a>
                  </p>
                  <a class="btn btn-primary btn-sm" href="#"><i class="fa fa-plus"></i></a>
                </div>
              </div>
            </div>
            <div class="backside">
              <div class="card">
                <div class="card-body text-center mt-4">
                  <h4 class="card-title">Sunlimetech
                  </h4>
                  <p class="card-text">This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.
                  </p>
                  <ul class="list-inline">
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-facebook"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-twitter"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-skype"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-google"></i> </a></li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- ./Team member --><!-- Team member -->
      <div class="col-xs-12 col-sm-6 col-md-4">
        <div class="image-flip" ontouchstart="this.classList.toggle('hover');">
          <div class="mainflip">
            <div class="frontside">
              <div class="card">
                <div class="card-body text-center">
                  <p><img alt="card image" class="img-fluid" src="https://www.lincoln.ac.uk/home/media/responsive2017/collegeofscience/medicalschool/Alistair,Warren,Profile,Image.jpg" />
                  </p>
                  <h4 apple="" class="card-title" color="" color:="" helvetica="" segoe="" style="font-family: -apple-system, BlinkMacSystemFont, " text-align:="" ui="">Emma Jestico
                  </h4>
                  <p class="card-text" style="text-align: center;"><span class="fa fa-envelope"></span>  <a class="email" href="mailto:jhodgson@lincoln.ac.uk" style="color: rgb(66, 139, 202); text-decoration-line: underline; background-image: initial; background-position: 0px 0px; background-size: initial; background-repeat: initial; background-attachment: initial; background-origin: initial; background-clip: initial;">ejestico@lincoln.ac.uk</a>
                  </p>
                  <dl style="text-align: center;">
                    <dd 14px="" font-size:="" helvetica="" open="" style="line-height: 1.42857; color: rgb(51, 51, 51);"><span class="fa fa-phone"></span>  <a class="phone" href="tel:01522835084" style="color: rgb(66, 139, 202); background-image: initial; background-position: 0px 0px; background-size: initial; background-repeat: initial; background-attachment: initial; background-origin: initial; background-clip: initial;">01522 83 5084</a>
                    </dd>
                  </dl>
                  <a class="btn btn-primary btn-sm" href="#"><i class="fa fa-plus"></i></a>
                </div>
              </div>
            </div>
            <div class="backside">
              <div class="card">
                <div class="card-body text-center mt-4">
                  <h4 class="card-title">Sunlimetech
                  </h4>
                  <p class="card-text">This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.
                  </p>
                  <ul class="list-inline">
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-facebook"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-twitter"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-skype"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-google"></i> </a></li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- ./Team member --><!-- Team member -->
      <div class="col-xs-12 col-sm-6 col-md-4">
        <div class="image-flip" ontouchstart="this.classList.toggle('hover');">
          <div class="mainflip">
            <div class="frontside">
              <div class="card">
                <div class="card-body text-center">
                  <p><img alt="card image" class="img-fluid" src="https://www.lincoln.ac.uk/home/media/responsive2017/collegeofscience/medicalschool/Skantha,Spotlight.jpg" />
                  </p>
                  <h4 apple="" class="card-title" color="" color:="" helvetica="" segoe="" style="font-family: -apple-system, BlinkMacSystemFont, " text-align:="" ui="">Skantha Kandiah
                  </h4>
                  <p class="card-text" style="text-align: center;"><span class="fa fa-envelope"></span>  <a class="email" href="mailto:jhodgson@lincoln.ac.uk" style="color: rgb(66, 139, 202); text-decoration-line: underline; background-image: initial; background-position: 0px 0px; background-size: initial; background-repeat: initial; background-attachment: initial; background-origin: initial; background-clip: initial;">skandiah@lincoln.ac.uk</a>
                  </p>
                  <dl style="text-align: center;">
                    <dd 14px="" font-size:="" helvetica="" open="" style="line-height: 1.42857; color: rgb(51, 51, 51);"><span class="fa fa-phone"></span>  <a class="phone" href="tel:01522835084" style="color: rgb(66, 139, 202); background-image: initial; background-position: 0px 0px; background-size: initial; background-repeat: initial; background-attachment: initial; background-origin: initial; background-clip: initial;">01522 83 5084</a>
                    </dd>
                  </dl>
                  <a class="btn btn-primary btn-sm" href="#"><i class="fa fa-plus"></i></a>
                </div>
              </div>
            </div>
            <div class="backside">
              <div class="card">
                <div class="card-body text-center mt-4">
                  <h4 class="card-title">Sunlimetech
                  </h4>
                  <p class="card-text">This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.
                  </p>
                  <ul class="list-inline">
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-facebook"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-twitter"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-skype"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-google"></i> </a></li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- ./Team member --><!-- Team member -->
      <div class="col-xs-12 col-sm-6 col-md-4">
        <div class="image-flip" ontouchstart="this.classList.toggle('hover');">
          <div class="mainflip">
            <div class="frontside">
              <div class="card">
                <div class="card-body text-center">
                  <p><img alt="card image" class="img-fluid" src="https://www.lincoln.ac.uk/home/media/responsive2017/collegeofscience/medicalschool/Gill,Garden,Image.jpg" />
                  </p>
                  <h4 apple="" class="card-title" color="" color:="" helvetica="" segoe="" style="font-family: -apple-system, BlinkMacSystemFont, " text-align:="" ui="">Rachael King
                  </h4>
                  <p class="card-text" style="text-align: center;"><span class="fa fa-envelope"></span>  <a class="email" href="mailto:jhodgson@lincoln.ac.uk" style="color: rgb(66, 139, 202); text-decoration-line: underline; background-image: initial; background-position: 0px 0px; background-size: initial; background-repeat: initial; background-attachment: initial; background-origin: initial; background-clip: initial;">Rking@lincoln.ac.uk</a>
                  </p>
                  <dl style="text-align: center;">
                    <dd 14px="" font-size:="" helvetica="" open="" style="line-height: 1.42857; color: rgb(51, 51, 51);"><span class="fa fa-phone"></span>  <a class="phone" href="tel:01522835084" style="color: rgb(66, 139, 202); background-image: initial; background-position: 0px 0px; background-size: initial; background-repeat: initial; background-attachment: initial; background-origin: initial; background-clip: initial;">01522 83 5084</a>.
                    </dd>
                  </dl>
                  <a class="btn btn-primary btn-sm" href="#"><i class="fa fa-plus"></i></a>
                </div>
              </div>
            </div>
            <div class="backside">
              <div class="card">
                <div class="card-body text-center mt-4">
                  <h4 class="card-title">Sunlimetech
                  </h4>
                  <p class="card-text">This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.
                  </p>
                  <ul class="list-inline">
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-facebook"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-twitter"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-skype"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-google"></i> </a></li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- ./Team member --><!-- Team member -->
      <div class="col-xs-12 col-sm-6 col-md-4">
        <div class="image-flip" ontouchstart="this.classList.toggle('hover');">
          <div class="mainflip">
            <div class="frontside">
              <div class="card">
                <div class="card-body text-center">
                  <p><img alt="card image" class="img-fluid" src="https://www.lincoln.ac.uk/home/media/responsive2017/collegeofscience/medicalschool/Runa,Image.jpg" />
                  </p>
                  <h4 apple="" class="card-title" color="" color:="" helvetica="" segoe="" style="font-family: -apple-system, BlinkMacSystemFont, " text-align:="" ui="">Danny Mclaughlin
                  </h4>
                  <p class="card-text" style="text-align: center;"><span class="fa fa-envelope"></span>  <a class="email" href="mailto:jhodgson@lincoln.ac.uk" style="color: rgb(66, 139, 202); text-decoration-line: underline; background-image: initial; background-position: 0px 0px; background-size: initial; background-repeat: initial; background-attachment: initial; background-origin: initial; background-clip: initial;">jhodgson@lincoln.ac.uk</a>
                  </p>
                  <dl style="text-align: center;">
                    <dd 14px="" font-size:="" helvetica="" open="" style="line-height: 1.42857; color: rgb(51, 51, 51);"><span class="fa fa-phone"></span>  <a class="phone" href="tel:01522835084" style="color: rgb(66, 139, 202); background-image: initial; background-position: 0px 0px; background-size: initial; background-repeat: initial; background-attachment: initial; background-origin: initial; background-clip: initial;">01522 83 5084</a>
                    </dd>
                  </dl>
                  <a class="btn btn-primary btn-sm" href="#"><i class="fa fa-plus"></i></a>
                </div>
              </div>
            </div>
            <div class="backside">
              <div class="card">
                <div class="card-body text-center mt-4">
                  <h4 class="card-title">Sunlimetech
                  </h4>
                  <p class="card-text">This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.
                  </p>
                  <ul class="list-inline">
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-facebook"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-twitter"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-skype"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-google"></i> </a></li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- ./Team member --></div>
    <div class="row"><!-- Team member -->
      <div class="col-xs-12 col-sm-6 col-md-4">
        <div class="image-flip" ontouchstart="this.classList.toggle('hover');">
          <div class="mainflip">
            <div class="frontside">
              <div class="card">
                <div class="card-body text-center">
                  <p><img alt="card image" class="img-fluid" src="https://www.lincoln.ac.uk/home/media/responsive2017/collegeofscience/medicalschool/Danny,McLaughlin,Square.jpg" />
                  </p>
                  <h4 apple="" class="card-title" color="" color:="" helvetica="" segoe="" style="font-family: -apple-system, BlinkMacSystemFont, " text-align:="" ui="">Jessica Hodgson
                  </h4>
                  <p class="card-text" style="text-align: center;"><span class="fa fa-envelope"></span>  <a class="email" href="mailto:jhodgson@lincoln.ac.uk" style="color: rgb(66, 139, 202); text-decoration-line: underline; background-image: initial; background-position: 0px 0px; background-size: initial; background-repeat: initial; background-attachment: initial; background-origin: initial; background-clip: initial;">jhodgson@lincoln.ac.uk</a>
                  </p>
                  <dl style="text-align: center;">
                    <dd 14px="" font-size:="" helvetica="" open="" style="line-height: 1.42857; color: rgb(51, 51, 51);"><span class="fa fa-phone"></span>  <a class="phone" href="tel:01522835084" style="color: rgb(66, 139, 202); background-image: initial; background-position: 0px 0px; background-size: initial; background-repeat: initial; background-attachment: initial; background-origin: initial; background-clip: initial;">01522 83 5084</a>
                    </dd>
                  </dl>
                  <a class="btn btn-primary btn-sm" href="#"><i class="fa fa-plus"></i></a>
                </div>
              </div>
            </div>
            <div class="backside">
              <div class="card">
                <div class="card-body text-center mt-4">
                  <h4 class="card-title">Sunlimetech
                  </h4>
                  <p class="card-text">This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.
                  </p>
                  <ul class="list-inline">
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-facebook"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-twitter"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-skype"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-google"></i> </a></li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- ./Team member --><!-- Team member -->
      <div class="col-xs-12 col-sm-6 col-md-4">
        <div class="image-flip" ontouchstart="this.classList.toggle('hover');">
          <div class="mainflip">
            <div class="frontside">
              <div class="card">
                <div class="card-body text-center">
                  <p><img alt="card image" class="img-fluid" src="https://www.lincoln.ac.uk/home/media/responsive2017/collegeofscience/medicalschool/Jill,Pinner,Profile,Image.jpg" />
                  </p>
                  <h4 apple="" class="card-title" color="" color:="" helvetica="" segoe="" style="font-family: -apple-system, BlinkMacSystemFont, " text-align:="" ui="">Jessica Hodgson
                  </h4>
                  <p class="card-text" style="text-align: center;"><span class="fa fa-envelope"></span>  <a class="email" href="mailto:jhodgson@lincoln.ac.uk" style="color: rgb(66, 139, 202); text-decoration-line: underline; background-image: initial; background-position: 0px 0px; background-size: initial; background-repeat: initial; background-attachment: initial; background-origin: initial; background-clip: initial;">jhodgson@lincoln.ac.uk</a>
                  </p>
                  <dl style="text-align: center;">
                    <dd 14px="" font-size:="" helvetica="" open="" style="line-height: 1.42857; color: rgb(51, 51, 51);"><span class="fa fa-phone"></span>  <a class="phone" href="tel:01522835084" style="color: rgb(66, 139, 202); background-image: initial; background-position: 0px 0px; background-size: initial; background-repeat: initial; background-attachment: initial; background-origin: initial; background-clip: initial;">01522 83 5084</a>
                    </dd>
                  </dl>
                  <a class="btn btn-primary btn-sm" href="#"><i class="fa fa-plus"></i></a>
                </div>
              </div>
            </div>
            <div class="backside">
              <div class="card">
                <div class="card-body text-center mt-4">
                  <h4 class="card-title">Sunlimetech
                  </h4>
                  <p class="card-text">This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.
                  </p>
                  <ul class="list-inline">
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-facebook"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-twitter"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-skype"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-google"></i> </a></li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- ./Team member --><!-- Team member -->
      <div class="col-xs-12 col-sm-6 col-md-4">
        <div class="image-flip" ontouchstart="this.classList.toggle('hover');">
          <div class="mainflip">
            <div class="frontside">
              <div class="card">
                <div class="card-body text-center">
                  <p><img alt="card image" class="img-fluid" src="https://www.lincoln.ac.uk/home/media/responsive2017/collegeofscience/medicalschool/Alistair,Warren,Profile,Image.jpg" />
                  </p>
                  <h4 apple="" class="card-title" color="" color:="" helvetica="" segoe="" style="font-family: -apple-system, BlinkMacSystemFont, " text-align:="" ui="">Jessica Hodgson
                  </h4>
                  <p class="card-text" style="text-align: center;"><span class="fa fa-envelope"></span>  <a class="email" href="mailto:jhodgson@lincoln.ac.uk" style="color: rgb(66, 139, 202); text-decoration-line: underline; background-image: initial; background-position: 0px 0px; background-size: initial; background-repeat: initial; background-attachment: initial; background-origin: initial; background-clip: initial;">jhodgson@lincoln.ac.uk</a>
                  </p>
                  <dl style="text-align: center;">
                    <dd 14px="" font-size:="" helvetica="" open="" style="line-height: 1.42857; color: rgb(51, 51, 51);"><span class="fa fa-phone"></span>  <a class="phone" href="tel:01522835084" style="color: rgb(66, 139, 202); background-image: initial; background-position: 0px 0px; background-size: initial; background-repeat: initial; background-attachment: initial; background-origin: initial; background-clip: initial;">01522 83 5084</a>
                    </dd>
                  </dl>
                  <a class="btn btn-primary btn-sm" href="#"><i class="fa fa-plus"></i></a>
                </div>
              </div>
            </div>
            <div class="backside">
              <div class="card">
                <div class="card-body text-center mt-4">
                  <h4 class="card-title">Sunlimetech
                  </h4>
                  <p class="card-text">This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.
                  </p>
                  <ul class="list-inline">
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-facebook"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-twitter"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-skype"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-google"></i> </a></li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- ./Team member --><!-- Team member -->
      <div class="col-xs-12 col-sm-6 col-md-4">
        <div class="image-flip" ontouchstart="this.classList.toggle('hover');">
          <div class="mainflip">
            <div class="frontside">
              <div class="card">
                <div class="card-body text-center">
                  <p><img alt="card image" class="img-fluid" src="https://www.lincoln.ac.uk/home/media/responsive2017/collegeofscience/medicalschool/Skantha,Spotlight.jpg" />
                  </p>
                  <h4 apple="" class="card-title" color="" color:="" helvetica="" segoe="" style="font-family: -apple-system, BlinkMacSystemFont, " text-align:="" ui="">Jessica Hodgson
                  </h4>
                  <p class="card-text" style="text-align: center;"><span class="fa fa-envelope"></span>  <a class="email" href="mailto:jhodgson@lincoln.ac.uk" style="color: rgb(66, 139, 202); text-decoration-line: underline; background-image: initial; background-position: 0px 0px; background-size: initial; background-repeat: initial; background-attachment: initial; background-origin: initial; background-clip: initial;">jhodgson@lincoln.ac.uk</a>
                  </p>
                  <dl style="text-align: center;">
                    <dd 14px="" font-size:="" helvetica="" open="" style="line-height: 1.42857; color: rgb(51, 51, 51);"><span class="fa fa-phone"></span>  <a class="phone" href="tel:01522835084" style="color: rgb(66, 139, 202); background-image: initial; background-position: 0px 0px; background-size: initial; background-repeat: initial; background-attachment: initial; background-origin: initial; background-clip: initial;">01522 83 5084</a>
                    </dd>
                  </dl>
                  <a class="btn btn-primary btn-sm" href="#"><i class="fa fa-plus"></i></a>
                </div>
              </div>
            </div>
            <div class="backside">
              <div class="card">
                <div class="card-body text-center mt-4">
                  <h4 class="card-title">Sunlimetech
                  </h4>
                  <p class="card-text">This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.
                  </p>
                  <ul class="list-inline">
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-facebook"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-twitter"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-skype"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-google"></i> </a></li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- ./Team member --><!-- Team member -->
      <div class="col-xs-12 col-sm-6 col-md-4">
        <div class="image-flip" ontouchstart="this.classList.toggle('hover');">
          <div class="mainflip">
            <div class="frontside">
              <div class="card">
                <div class="card-body text-center">
                  <p><img alt="card image" class="img-fluid" src="https://www.lincoln.ac.uk/home/media/responsive2017/collegeofscience/medicalschool/Gill,Garden,Image.jpg" />
                  </p>
                  <h4 apple="" class="card-title" color="" color:="" helvetica="" segoe="" style="font-family: -apple-system, BlinkMacSystemFont, " text-align:="" ui="">Jessica Hodgson
                  </h4>
                  <p class="card-text" style="text-align: center;"><span class="fa fa-envelope"></span>  <a class="email" href="mailto:jhodgson@lincoln.ac.uk" style="color: rgb(66, 139, 202); text-decoration-line: underline; background-image: initial; background-position: 0px 0px; background-size: initial; background-repeat: initial; background-attachment: initial; background-origin: initial; background-clip: initial;">jhodgson@lincoln.ac.uk</a>
                  </p>
                  <dl style="text-align: center;">
                    <dd 14px="" font-size:="" helvetica="" open="" style="line-height: 1.42857; color: rgb(51, 51, 51);"><span class="fa fa-phone"></span>  <a class="phone" href="tel:01522835084" style="color: rgb(66, 139, 202); background-image: initial; background-position: 0px 0px; background-size: initial; background-repeat: initial; background-attachment: initial; background-origin: initial; background-clip: initial;">01522 83 5084</a>
                    </dd>
                  </dl>
                  <a class="btn btn-primary btn-sm" href="#"><i class="fa fa-plus"></i></a>
                </div>
              </div>
            </div>
            <div class="backside">
              <div class="card">
                <div class="card-body text-center mt-4">
                  <h4 class="card-title">Sunlimetech
                  </h4>
                  <p class="card-text">This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.
                  </p>
                  <ul class="list-inline">
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-facebook"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-twitter"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-skype"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-google"></i> </a></li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- ./Team member --><!-- Team member -->
      <div class="col-xs-12 col-sm-6 col-md-4">
        <div class="image-flip" ontouchstart="this.classList.toggle('hover');">
          <div class="mainflip">
            <div class="frontside">
              <div class="card">
                <div class="card-body text-center">
                  <p><img alt="card image" class="img-fluid" src="https://www.lincoln.ac.uk/home/media/responsive2017/collegeofscience/medicalschool/Runa,Image.jpg" />
                  </p>
                  <h4 apple="" class="card-title" color="" color:="" helvetica="" segoe="" style="font-family: -apple-system, BlinkMacSystemFont, " text-align:="" ui="">Jessica Hodgson
                  </h4>
                  <p class="card-text" style="text-align: center;"><span class="fa fa-envelope"></span>  <a class="email" href="mailto:jhodgson@lincoln.ac.uk" style="color: rgb(66, 139, 202); text-decoration-line: underline; background-image: initial; background-position: 0px 0px; background-size: initial; background-repeat: initial; background-attachment: initial; background-origin: initial; background-clip: initial;">jhodgson@lincoln.ac.uk</a>
                  </p>
                  <dl style="text-align: center;">
                    <dd 14px="" font-size:="" helvetica="" open="" style="line-height: 1.42857; color: rgb(51, 51, 51);"><span class="fa fa-phone"></span>  <a class="phone" href="tel:01522835084" style="color: rgb(66, 139, 202); background-image: initial; background-position: 0px 0px; background-size: initial; background-repeat: initial; background-attachment: initial; background-origin: initial; background-clip: initial;">01522 83 5084</a>
                    </dd>
                  </dl>
                  <a class="btn btn-primary btn-sm" href="#"><i class="fa fa-plus"></i></a>
                </div>
              </div>
            </div>
            <div class="backside">
              <div class="card">
                <div class="card-body text-center mt-4">
                  <h4 class="card-title">Sunlimetech
                  </h4>
                  <p class="card-text">This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.
                  </p>
                  <ul class="list-inline">
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-facebook"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-twitter"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-skype"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-google"></i> </a></li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- ./Team member --></div>
    <div class="row"><!-- Team member -->
      <div class="col-xs-12 col-sm-6 col-md-4">
        <div class="image-flip" ontouchstart="this.classList.toggle('hover');">
          <div class="mainflip">
            <div class="frontside">
              <div class="card">
                <div class="card-body text-center">
                  <p><img alt="card image" class="img-fluid" src="https://www.lincoln.ac.uk/home/media/responsive2017/collegeofscience/medicalschool/Danny,McLaughlin,Square.jpg" />
                  </p>
                  <h4 apple="" class="card-title" color="" color:="" helvetica="" segoe="" style="font-family: -apple-system, BlinkMacSystemFont, " text-align:="" ui="">Jessica Hodgson
                  </h4>
                  <p class="card-text" style="text-align: center;"><span class="fa fa-envelope"></span>  <a class="email" href="mailto:jhodgson@lincoln.ac.uk" style="color: rgb(66, 139, 202); text-decoration-line: underline; background-image: initial; background-position: 0px 0px; background-size: initial; background-repeat: initial; background-attachment: initial; background-origin: initial; background-clip: initial;">jhodgson@lincoln.ac.uk</a>
                  </p>
                  <dl style="text-align: center;">
                    <dd 14px="" font-size:="" helvetica="" open="" style="line-height: 1.42857; color: rgb(51, 51, 51);"><span class="fa fa-phone"></span>  <a class="phone" href="tel:01522835084" style="color: rgb(66, 139, 202); background-image: initial; background-position: 0px 0px; background-size: initial; background-repeat: initial; background-attachment: initial; background-origin: initial; background-clip: initial;">01522 83 5084</a>
                    </dd>
                  </dl>
                  <a class="btn btn-primary btn-sm" href="#"><i class="fa fa-plus"></i></a>
                </div>
              </div>
            </div>
            <div class="backside">
              <div class="card">
                <div class="card-body text-center mt-4">
                  <h4 class="card-title">Sunlimetech
                  </h4>
                  <p class="card-text">This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.
                  </p>
                  <ul class="list-inline">
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-facebook"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-twitter"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-skype"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-google"></i> </a></li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- ./Team member --><!-- Team member -->
      <div class="col-xs-12 col-sm-6 col-md-4">
        <div class="image-flip" ontouchstart="this.classList.toggle('hover');">
          <div class="mainflip">
            <div class="frontside">
              <div class="card">
                <div class="card-body text-center">
                  <p><img alt="card image" class="img-fluid" src="https://www.lincoln.ac.uk/home/media/responsive2017/collegeofscience/medicalschool/Jill,Pinner,Profile,Image.jpg" />
                  </p>
                  <h4 apple="" class="card-title" color="" color:="" helvetica="" segoe="" style="font-family: -apple-system, BlinkMacSystemFont, " text-align:="" ui="">Jessica Hodgson
                  </h4>
                  <p class="card-text" style="text-align: center;"><span class="fa fa-envelope"></span>  <a class="email" href="mailto:jhodgson@lincoln.ac.uk" style="color: rgb(66, 139, 202); text-decoration-line: underline; background-image: initial; background-position: 0px 0px; background-size: initial; background-repeat: initial; background-attachment: initial; background-origin: initial; background-clip: initial;">jhodgson@lincoln.ac.uk</a>
                  </p>
                  <dl style="text-align: center;">
                    <dd 14px="" font-size:="" helvetica="" open="" style="line-height: 1.42857; color: rgb(51, 51, 51);"><span class="fa fa-phone"></span>  <a class="phone" href="tel:01522835084" style="color: rgb(66, 139, 202); background-image: initial; background-position: 0px 0px; background-size: initial; background-repeat: initial; background-attachment: initial; background-origin: initial; background-clip: initial;">01522 83 5084</a>
                    </dd>
                  </dl>
                  <a class="btn btn-primary btn-sm" href="#"><i class="fa fa-plus"></i></a>
                </div>
              </div>
            </div>
            <div class="backside">
              <div class="card">
                <div class="card-body text-center mt-4">
                  <h4 class="card-title">Sunlimetech
                  </h4>
                  <p class="card-text">This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.
                  </p>
                  <ul class="list-inline">
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-facebook"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-twitter"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-skype"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-google"></i> </a></li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- ./Team member --><!-- Team member -->
      <div class="col-xs-12 col-sm-6 col-md-4">
        <div class="image-flip" ontouchstart="this.classList.toggle('hover');">
          <div class="mainflip">
            <div class="frontside">
              <div class="card">
                <div class="card-body text-center">
                  <p><img alt="card image" class="img-fluid" src="https://www.lincoln.ac.uk/home/media/responsive2017/collegeofscience/medicalschool/Alistair,Warren,Profile,Image.jpg" />
                  </p>
                  <h4 apple="" class="card-title" color="" color:="" helvetica="" segoe="" style="font-family: -apple-system, BlinkMacSystemFont, " text-align:="" ui="">Jessica Hodgson
                  </h4>
                  <p class="card-text" style="text-align: center;"><span class="fa fa-envelope"></span>  <a class="email" href="mailto:jhodgson@lincoln.ac.uk" style="color: rgb(66, 139, 202); text-decoration-line: underline; background-image: initial; background-position: 0px 0px; background-size: initial; background-repeat: initial; background-attachment: initial; background-origin: initial; background-clip: initial;">jhodgson@lincoln.ac.uk</a>
                  </p>
                  <dl style="text-align: center;">
                    <dd 14px="" font-size:="" helvetica="" open="" style="line-height: 1.42857; color: rgb(51, 51, 51);"><span class="fa fa-phone"></span>  <a class="phone" href="tel:01522835084" style="color: rgb(66, 139, 202); background-image: initial; background-position: 0px 0px; background-size: initial; background-repeat: initial; background-attachment: initial; background-origin: initial; background-clip: initial;">01522 83 5084</a>
                    </dd>
                  </dl>
                  <a class="btn btn-primary btn-sm" href="#"><i class="fa fa-plus"></i></a>
                </div>
              </div>
            </div>
            <div class="backside">
              <div class="card">
                <div class="card-body text-center mt-4">
                  <h4 class="card-title">Sunlimetech
                  </h4>
                  <p class="card-text">This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.
                  </p>
                  <ul class="list-inline">
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-facebook"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-twitter"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-skype"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-google"></i> </a></li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- ./Team member --><!-- Team member -->
      <div class="col-xs-12 col-sm-6 col-md-4">
        <div class="image-flip" ontouchstart="this.classList.toggle('hover');">
          <div class="mainflip">
            <div class="frontside">
              <div class="card">
                <div class="card-body text-center">
                  <p><img alt="card image" class="img-fluid" src="https://www.lincoln.ac.uk/home/media/responsive2017/collegeofscience/medicalschool/Skantha,Spotlight.jpg" />
                  </p>
                  <h4 apple="" class="card-title" color="" color:="" helvetica="" segoe="" style="font-family: -apple-system, BlinkMacSystemFont, " text-align:="" ui="">Jessica Hodgson
                  </h4>
                  <p class="card-text" style="text-align: center;"><span class="fa fa-envelope"></span>  <a class="email" href="mailto:jhodgson@lincoln.ac.uk" style="color: rgb(66, 139, 202); text-decoration-line: underline; background-image: initial; background-position: 0px 0px; background-size: initial; background-repeat: initial; background-attachment: initial; background-origin: initial; background-clip: initial;">jhodgson@lincoln.ac.uk</a>
                  </p>
                  <dl style="text-align: center;">
                    <dd 14px="" font-size:="" helvetica="" open="" style="line-height: 1.42857; color: rgb(51, 51, 51);"><span class="fa fa-phone"></span>  <a class="phone" href="tel:01522835084" style="color: rgb(66, 139, 202); background-image: initial; background-position: 0px 0px; background-size: initial; background-repeat: initial; background-attachment: initial; background-origin: initial; background-clip: initial;">01522 83 5084</a>
                    </dd>
                  </dl>
                  <a class="btn btn-primary btn-sm" href="#"><i class="fa fa-plus"></i></a>
                </div>
              </div>
            </div>
            <div class="backside">
              <div class="card">
                <div class="card-body text-center mt-4">
                  <h4 class="card-title">Sunlimetech
                  </h4>
                  <p class="card-text">This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.
                  </p>
                  <ul class="list-inline">
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-facebook"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-twitter"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-skype"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-google"></i> </a></li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- ./Team member --><!-- Team member -->
      <div class="col-xs-12 col-sm-6 col-md-4">
        <div class="image-flip" ontouchstart="this.classList.toggle('hover');">
          <div class="mainflip">
            <div class="frontside">
              <div class="card">
                <div class="card-body text-center">
                  <p><img alt="card image" class="img-fluid" src="https://www.lincoln.ac.uk/home/media/responsive2017/collegeofscience/medicalschool/Gill,Garden,Image.jpg" />
                  </p>
                  <h4 apple="" class="card-title" color="" color:="" helvetica="" segoe="" style="font-family: -apple-system, BlinkMacSystemFont, " text-align:="" ui="">Jessica Hodgson
                  </h4>
                  <p class="card-text" style="text-align: center;"><span class="fa fa-envelope"></span>  <a class="email" href="mailto:jhodgson@lincoln.ac.uk" style="color: rgb(66, 139, 202); text-decoration-line: underline; background-image: initial; background-position: 0px 0px; background-size: initial; background-repeat: initial; background-attachment: initial; background-origin: initial; background-clip: initial;">jhodgson@lincoln.ac.uk</a>
                  </p>
                  <dl style="text-align: center;">
                    <dd 14px="" font-size:="" helvetica="" open="" style="line-height: 1.42857; color: rgb(51, 51, 51);"><span class="fa fa-phone"></span>  <a class="phone" href="tel:01522835084" style="color: rgb(66, 139, 202); background-image: initial; background-position: 0px 0px; background-size: initial; background-repeat: initial; background-attachment: initial; background-origin: initial; background-clip: initial;">01522 83 5084</a>
                    </dd>
                  </dl>
                  <a class="btn btn-primary btn-sm" href="#"><i class="fa fa-plus"></i></a>
                </div>
              </div>
            </div>
            <div class="backside">
              <div class="card">
                <div class="card-body text-center mt-4">
                  <h4 class="card-title">Sunlimetech
                  </h4>
                  <p class="card-text">This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.
                  </p>
                  <ul class="list-inline">
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-facebook"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-twitter"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-skype"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-google"></i> </a></li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- ./Team member --><!-- Team member -->
      <div class="col-xs-12 col-sm-6 col-md-4">
        <div class="image-flip" ontouchstart="this.classList.toggle('hover');">
          <div class="mainflip">
            <div class="frontside">
              <div class="card">
                <div class="card-body text-center">
                  <p><img alt="card image" class="img-fluid" src="https://www.lincoln.ac.uk/home/media/responsive2017/collegeofscience/medicalschool/Runa,Image.jpg" />
                  </p>
                  <h4 apple="" class="card-title" color="" color:="" helvetica="" segoe="" style="font-family: -apple-system, BlinkMacSystemFont, " text-align:="" ui="">Jessica Hodgson
                  </h4>
                  <p class="card-text" style="text-align: center;"><span class="fa fa-envelope"></span>  <a class="email" href="mailto:jhodgson@lincoln.ac.uk" style="color: rgb(66, 139, 202); text-decoration-line: underline; background-image: initial; background-position: 0px 0px; background-size: initial; background-repeat: initial; background-attachment: initial; background-origin: initial; background-clip: initial;">jhodgson@lincoln.ac.uk</a>
                  </p>
                  <dl style="text-align: center;">
                    <dd 14px="" font-size:="" helvetica="" open="" style="line-height: 1.42857; color: rgb(51, 51, 51);"><span class="fa fa-phone"></span>  <a class="phone" href="tel:01522835084" style="color: rgb(66, 139, 202); background-image: initial; background-position: 0px 0px; background-size: initial; background-repeat: initial; background-attachment: initial; background-origin: initial; background-clip: initial;">01522 83 5084</a>
                    </dd>
                  </dl>
                  <a class="btn btn-primary btn-sm" href="#"><i class="fa fa-plus"></i></a>
                </div>
              </div>
            </div>
            <div class="backside">
              <div class="card">
                <div class="card-body text-center mt-4">
                  <h4 class="card-title">Sunlimetech
                  </h4>
                  <p class="card-text">This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.This is basic card with image on top, title, description and button.
                  </p>
                  <ul class="list-inline">
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-facebook"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-twitter"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-skype"></i> </a></li>
                    <li class="list-inline-item"><a class="social-icon text-xs-center" href="#" target="_blank"><i class="fa fa-google"></i> </a></li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- ./Team member --></div>
  </div>
</section>
<!-- Team -->
<p class="card-text" style="text-align: center;"><span class="fa fa-envelope"></span> Email <a class="email" href="mailto:jhodgson@lincoln.ac.uk" style="color: rgb(66, 139, 202); background-image: initial; background-position: 0px 0px; background-size: initial; background-repeat: initial; background-attachment: initial; background-origin: initial; background-clip: initial;">jhodgson@lincoln.ac.uk</a>
</p>
<dl style="text-align: center;">
  <dd 14px="" font-size:="" helvetica="" open="" style="line-height: 1.42857; color: rgb(51, 51, 51); font-family: "><span class="fa fa-phone"></span> Telephone <a class="phone" href="tel:01522835084" style="color: rgb(66, 139, 202); background-image: initial; background-position: 0px 0px; background-size: initial; background-repeat: initial; background-attachment: initial; background-origin: initial; background-clip: initial;">01522 83 5084</a>
  </dd>
</dl>
<p><span class="fa fa-envelope"></span><span style="text-align: center;"> Email</span>
</p>
