<template>
    <div id="homepage">
      <Nav />
    </div>  
</template>

<script>
export default {}
</script>

<style>
.page-enter-active, .page-leave-active{
  transition: all 0.5s;
}

.page-enter, .page-leave-active{
  opacity: 0;
  transform: scale(0);
}

div#homepage{
  background-image: url('~assets/fond.png');
  background-repeat: no-repeat;
  height: 100vh;
}
</style>
