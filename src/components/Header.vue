<template>
  <header>
    <nav>
        <a href="#">
            <img src="../img/dc-logo.png" alt="">
        </a>
        <ul>
            <li>
                <a href="#">characters</a>
            </li>
            <li>
                <a href="#">comics</a>
            </li>
            <li>
                <a href="#">movies</a>
            </li>
            <li>
                <a href="#">tv</a>
            </li>
            <li>
                <a href="#">games</a>
            </li>
            <li>
                <a href="#">collectibles</a>
            </li>
            <li>
                <a href="#">videos</a>
            </li>
            <li>
                <a href="#">fans</a>
            </li>
            <li>
                <a href="#">news</a>
            </li>
            <li>
                <a href="#">shop</a>
            </li>
        </ul>
    </nav>
    
  </header>
</template>
    


<script>
export default {

}
</script>

<style lang="scss" scoped>



nav{
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: space-around;
}

ul{
     list-style: none;
     display: flex;
     flex-direction: row;
     align-items: center;

    li a{
     margin:0 10px;
     text-decoration: none;
     text-transform: uppercase;
     color: black;
    }
}



</style>