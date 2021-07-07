<template>
  <footer>
      <div class="barra-blu">
        <ul>
            <li>
                <a href="#"><img src="../img/buy-comics-digital-comics.png" alt="">digital comics</a>
            </li>
            <li>
                <a href="#"><img src="../img/buy-comics-merchandise.png" alt="">dc merchandise</a>
            </li>
            <li>
                <a href="#"><img src="../img/buy-comics-subscriptions.png" alt="">subscription</a>
            </li>
            <li>
                <a href="#"><img src="../img/buy-comics-shop-locator.png" alt="">comic shop locator</a>
            </li>
            <li>
                <a href="#"><img src="../img/buy-dc-power-visa.svg" alt="">dc power visa</a>
            </li>
        </ul>
      </div>
      <div class="foot-alto">
          <div>
            <ul>
            <h3>dc comics</h3>
            <li>characters</li>
            <li>comics</li>
            <li>movies</li>
            <li>TV</li>
            <li>games</li>
            <li>videos</li>
            <li>news</li>
            <h3>shop</h3>
            <li>shop DC</li>
            <li>shop DC collectibles</li>
            </ul>
            <ul>
                <h3>dc</h3>
                <li>terms of use</li>
                <li>privacy policy(new)</li>
                <li>ad choices</li>
                <li>advertising</li>
                <li>jobs</li>
                <li>subscriptions</li>
                <li>talent workshops</li>
                <li>CPSC certificates</li>
                <li>ratings</li>
                <li>shop help</li>
                <li>contact us</li>
            </ul>
            <ul>
                <h3>sites</h3>
                <li>DC</li>
                <li>MAD magazine</li>
                <li>DC kids</li>
                <li>DC universe</li>
                <li>DC power visas</li>
            </ul>
          </div>
      
          <img src="../img/dc-logo-bg.png" alt="">
      </div>
      <div class="foot-basso">
        <a href="#" class="btn">sign-up now!</a>
        <div class="link-foot-basso">
            <a href="#">follow us</a>
            <a href="#">
                <img src="../img/footer-facebook.png" alt="">
            </a>
            <a href="#">
                <img src="../img/footer-twitter.png" alt="">
            </a>
            <a href="#">
                <img src="../img/footer-youtube.png" alt="">
            </a>
            <a href="#">
                <img src="../img/footer-pinterest.png" alt="">
            </a>
            <a href="#">
                <img src="../img/footer-periscope.png" alt="">
            </a>
           
        </div>
      </div>
  </footer>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
.barra-blu{
    height: 100px;
    background-color: rgb(31, 74, 218);
    display: flex;
    justify-content: center;
    align-items: center;
    
    
    ul{
      display: flex;
      flex-direction: row;
      list-style: none;
    }
      
    li a{
        margin: 0 20px;
        color: white;
        text-transform: uppercase;
        text-decoration: none;
        font-size: 15px;
        display: flex;
        align-items: center;
    }
        li a img{
            margin: 0 10px;
            width: 40px;
            height: 40px;
        }
        
}
      
      
  

.foot-alto{
    display: flex;
    background-image: url(../img/footer-bg.jpg);
    justify-content: space-around;
    
    div{
        display: flex;

    }

    h3{
        margin: 20px 0;
        text-transform: uppercase;
        color: white;
    }
    li{
        list-style: none;
        text-transform: capitalize;
        margin: 10px 0;
        color: lightgrey;
    }
    img{
       width: 40%;
       
    }
}

.foot-basso{
    background-color: black;
    height: 100px;
    position: fixed;
    bottom: 0;
    width: 100%;
    display: flex;
    justify-content: space-around;
    align-items: center;
    text-transform: uppercase;
   a{
        margin: 0 10px;
        text-decoration: none;
    } 
    
}

.link-foot-basso{
    display: flex;
    align-items: center;
    :first-child {
    color: rgb(0, 68, 255);
    font-size: 20px;
}
    a{
        margin: 0 10px;
        text-decoration: none;
    }
}

.btn{
    padding: 10px;
    border: 1px solid blue;
    color: white;
}


</style>