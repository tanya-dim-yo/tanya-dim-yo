<div class="container">
  <h1>CSS3 Social <span>bu</span>ttons vol.2</h1>
  
  <div class="effect lavinia">
    <h2>Lavinia</h2>
    <div class="buttons">
      <a href="#" class="fb" title="Join us on Facebook"><i class="fa fa-facebook" aria-hidden="true"></i></a>
      <a href="#" class="tw" title="Join us on Twitter"><i class="fa fa-twitter" aria-hidden="true"></i></a>
      <a href="#" class="g-plus" title="Join us on Google+"><i class="fa fa-google-plus" aria-hidden="true"></i></a>
      <a href="#" class="dribbble" title="Join us on Dribbble"><i class="fa fa-dribbble" aria-hidden="true"></i></a>
      <a href="#" class="vimeo" title="Join us on Vimeo"><i class="fa fa-vimeo" aria-hidden="true"></i></a>
    <a href="#" class="pinterest" title="Join us on Pinterest"><i class="fa fa-pinterest-p" aria-hidden="true"></i></a>
      <a href="#" class="insta" title="Join us on Instagram"><i class="fa fa-instagram" aria-hidden="true"></i></a>
      <a href="#" class="in" title="Join us on Linked In"><i class="fa fa-linkedin" aria-hidden="true"></i></a>
    </div>
  </div>
  
  <div class="effect varrius">
    <h2>Varrius</h2>
    <div class="buttons">
      <a href="#" class="fb" title="Join us on Facebook"><i class="fa fa-facebook" aria-hidden="true"></i></a>
      <a href="#" class="tw" title="Join us on Twitter"><i class="fa fa-twitter" aria-hidden="true"></i></a>
      <a href="#" class="g-plus" title="Join us on Google+"><i class="fa fa-google-plus" aria-hidden="true"></i></a>
      <a href="#" class="dribbble" title="Join us on Dribbble"><i class="fa fa-dribbble" aria-hidden="true"></i></a>
      <a href="#" class="vimeo" title="Join us on Vimeo"><i class="fa fa-vimeo" aria-hidden="true"></i></a>
      <a href="#" class="pinterest" title="Join us on Pinterest"><i class="fa fa-pinterest-p" aria-hidden="true"></i></a>
      <a href="#" class="insta" title="Join us on Instagram"><i class="fa fa-instagram" aria-hidden="true"></i></a>
      <a href="#" class="in" title="Join us on Linked In"><i class="fa fa-linkedin" aria-hidden="true"></i></a>
    </div>
  </div>
  
  <div class="effect thurio">
    <h2>Thurio</h2>
    <div class="buttons">
      <a href="#" class="fb" title="Join us on Facebook"><i class="fa fa-facebook" aria-hidden="true"></i></a>
      <a href="#" class="tw" title="Join us on Twitter"><i class="fa fa-twitter" aria-hidden="true"></i></a>
      <a href="#" class="g-plus" title="Join us on Google+"><i class="fa fa-google-plus" aria-hidden="true"></i></a>
      <a href="#" class="dribbble" title="Join us on Dribbble"><i class="fa fa-dribbble" aria-hidden="true"></i></a>
      <a href="#" class="vimeo" title="Join us on Vimeo"><i class="fa fa-vimeo" aria-hidden="true"></i></a>
    <a href="#" class="pinterest" title="Join us on Pinterest"><i class="fa fa-pinterest-p" aria-hidden="true"></i></a>
      <a href="#" class="insta" title="Join us on Instagram"><i class="fa fa-instagram" aria-hidden="true"></i></a>
      <a href="#" class="in" title="Join us on Linked In"><i class="fa fa-linkedin" aria-hidden="true"></i></a>
    </div>
  </div>
  
    <div class="effect amiens">
    <h2>Amiens</h2>
    <div class="buttons">
      <a href="#" class="fb" title="Join us on Facebook"><i class="fa fa-facebook" aria-hidden="true"></i></a>
      <a href="#" class="tw" title="Join us on Twitter"><i class="fa fa-twitter" aria-hidden="true"></i></a>
      <a href="#" class="g-plus" title="Join us on Google+"><i class="fa fa-google-plus" aria-hidden="true"></i></a>
      <a href="#" class="dribbble" title="Join us on Dribbble"><i class="fa fa-dribbble" aria-hidden="true"></i></a>
      <a href="#" class="vimeo" title="Join us on Vimeo"><i class="fa fa-vimeo" aria-hidden="true"></i></a>
    <a href="#" class="pinterest" title="Join us on Pinterest"><i class="fa fa-pinterest-p" aria-hidden="true"></i></a>
      <a href="#" class="insta" title="Join us on Instagram"><i class="fa fa-instagram" aria-hidden="true"></i></a>
      <a href="#" class="in" title="Join us on Linked In"><i class="fa fa-linkedin" aria-hidden="true"></i></a>
    </div>
  </div>
  
  <div class="effect solanio">
    <h2>Solanio</h2>
    <div class="buttons">
      <a href="#" class="fb" title="Join us on Facebook"><i class="fa fa-facebook" aria-hidden="true"></i></a>
      <a href="#" class="tw" title="Join us on Twitter"><i class="fa fa-twitter" aria-hidden="true"></i></a>
      <a href="#" class="g-plus" title="Join us on Google+"><i class="fa fa-google-plus" aria-hidden="true"></i></a>
      <a href="#" class="dribbble" title="Join us on Dribbble"><i class="fa fa-dribbble" aria-hidden="true"></i></a>
      <a href="#" class="vimeo" title="Join us on Vimeo"><i class="fa fa-vimeo" aria-hidden="true"></i></a>
    <a href="#" class="pinterest" title="Join us on Pinterest"><i class="fa fa-pinterest-p" aria-hidden="true"></i></a>
      <a href="#" class="insta" title="Join us on Instagram"><i class="fa fa-instagram" aria-hidden="true"></i></a>
      <a href="#" class="in" title="Join us on Linked In"><i class="fa fa-linkedin" aria-hidden="true"></i></a>
    </div>
  </div>
  
</div>

---
//variables
$basic-dark-color: #212121;
$basic-light-color: #fff;
$border-radius: 50%;
$font-size: 25px;

/* common styles !!! YOU DON'T NEED THEM */
.container {
  margin: 60px auto 0px auto;
  text-align: center;
  
  h1 {
    font: {
      family: 'Roboto', sans-serif;
      weight: 900;
      size: 30px;
    }
    text-transform: uppercase;
    color: $basic-dark-color;
    letter-spacing: 3px;
    
    span {
      display: inline-block;
      
      &:before,
      &:after {
        content: "";
        display: block;
        width: 34px;
        height: 2px;
        background-color: $basic-dark-color;
        margin: 0px 0px 0px 2px;
      }
    }
  }
}

.effect {
  width: 100%;
  padding: 50px 0px 70px 0px;
  background-color: $basic-dark-color;
  
  h2 {
    color: $basic-light-color;
    font: {
      family: 'Playfair Display', serif;
      weight: 400;
      size: 25px;
    }
    letter-spacing: 3px;
  }
  
  &:nth-child(2) {
    margin-top: 50px;
  }
  
  &:nth-child(2n+1) {
    background-color: $basic-light-color;
    
    h2 {
      color: $basic-dark-color;
    }
  }
  
  &:nth-child(2n) {
    
     a {
      color: $basic-light-color;
      border-color: $basic-light-color;
    }
  }
  
  .buttons {
    margin-top: 50px;
    display: flex;
    justify-content: center;
  }
}

/* styles for a common effect !!!YOU NEED THEM */
.effect {
  /*display: flex; !!!uncomment this line !!!*/
  
  a {
    text-decoration: none !important;
    width: 60px;
    height: 60px;
    display: flex;
    align-items: center;
    justify-content: center;
    border-radius: $border-radius;
    margin-right: 20px;
    font-size: $font-size;
    overflow: hidden;
    position: relative;
    color: $basic-dark-color; //or change to your own color
    border: 2px solid $basic-dark-color; //or change to your own color
    
    i {
      position: relative;
      z-index: 3;
    }
    
    &:last-child {
      margin-right: 0px;
    }
    
    &:before {
      content: "";
      display: inline-block;
      height: 100%;
      vertical-align: middle;
    }
    
    i {
      display: inline-block;
      vertical-align: middle;
    }
  }
}

/* lavinia effect */
.effect.lavinia {
  
  a {
    
    transition: border-top-color 0.2s linear 0s, border-right-color 0.2s linear 0.1s, border-bottom-color 0.2s linear 0.2s, border-left-color 0.2s linear 0.3s;
    overflow: visible;
    
    &:hover {
      border-color: rgba($basic-light-color, 0);
    }
      
    &:after {
      content: "";
      display: block;
      width: 100%;
      height: 100%;
      top: -2px;
      left: -2px;
      border: 2px dashed $basic-light-color;
      position: absolute;
      border-radius: $border-radius;
    }
  }
}

/* varrius effect */
.effect.varrius {
  
  a {
    transition: all 0.2s linear 0s;
    
    &:after {
      content: "";
      display: block;
      width: 90%;
      height: 90%;
      top: -110%;
      left: 0;
      right: 0;
      margin: auto;
      position: absolute;
      background-color: $basic-dark-color;
      border-radius: $border-radius;
    }
    
    &:hover {
      color: $basic-light-color;
      
      &:after {
        top: 5%;
        transition: all 0.2s linear 0s;
      }
    }
  }
}

/* thurio effect */

.effect.thurio {
  
  a {
    transition: border-radius 0.2s linear 0s;
    transform: rotate(45deg);
    
    i {
      transition: transform 0.01s linear 0s;
      transform: rotate(-45deg);
    }
    
    &:hover {
      border-radius: 0px;
    }
  }
}

/* amiens effect */
.effect.amiens {
  
  a {
    transition: all 0.2s linear 0.2s;
    
    i {
      transition: all 0.2s linear 0s;
    }
    
    &:hover {
      transition: all 0.2s linear 0s;
      border-color: rgba($basic-dark-color,0);
      
      i {
        transform: scale(1.15);
        text-shadow: 4px 0px 3px rgba($basic-dark-color,0.3);
        transition: all 0.2s linear 0.2s;
      }
    }
  }
}

/* solanio effect */
.effect.solanio {
  
  a {
    border: none;
    overflow: visible;
    
    &:after {
      content: "";
      display: block;
      position: absolute;
      top: -2px;
      left: -2px;
      width: 100%;
      height: 100%;
      border: 2px solid $basic-light-color;
      border-radius: $border-radius;
      transition: all 0.2s linear 0s;
    }
    
    &:hover {

      &:after {
        height: 0px;
        top: 100%;
      }
    }
  }
}
---

[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=tanya-dim-yo&show_icons=true)](https://github.com/anuraghazra/github-readme-stats)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=tanya-dim-yo&size_weight=0.5&count_weight=0.5)

[![trophy](https://github-profile-trophy.vercel.app/?username=tanya-dim-yo&theme=flat&margin-w=15&no-frame=true&title=Commits,Repositories,Experience)](https://github.com/ryo-ma/github-profile-trophy)
