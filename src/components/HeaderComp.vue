<template>
  <header>
      <img class="logo" src="../assets/img/dc-logo.png" alt="">
          <ul>
            <li class="active">
              <a href="">CHARACTHERS</a>
              </li>
            <li>
              <a href="">COMICS</a>
            </li>
            <li>
              <a href="">MOVIES</a>
            </li>
            <li>
              <a href="">TV</a>
            </li>
            <li> 
              <a href=""> GAMES</a>
            </li>
            <li>
              <a href="">VIDEO </a>
            </li>
            <li>
              <a href="">FANS</a>
            </li>
            <li>
              <a href="">NEWS</a>
            </li>
            <li>
              <a href="">SHOP</a>
            </li>
          </ul>
  </header>
</template>
<script>
export default {
  name: 'HeaderComp',
}
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

header{
  width: 70%;
  margin: auto;
  display: flex ;
  justify-content: space-between;
  align-items: center;
}

ul{
  display: flex;
  align-items: center;
  justify-content: center;

  .active{
    border-bottom: 4px solid #0282f9;
  }

  li{
    list-style: none;
    margin-right: 13px;
    padding: 40px 0px;
    font-size: 12px;
  }

  a{
    color: black;
    text-decoration: none;
  }

}

</style>
