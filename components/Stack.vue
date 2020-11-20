<template>
  <div class="stackContainer">
    <h2 style="color: #4f47e2">TECH STACK</h2>
    <h5 style="color: white">some of the tech that usually use</h5>
    <div class="content">
      <div class="satu"></div>
      <div class="dua"></div>
      <div class="tiga"></div>
      <div class="empat"></div>
      <div class="lima"></div>
      <div class="enam"></div>
      <div class="tujuh"></div>
      <div class="delapan"></div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.stackContainer{
  margin-top: 5%;
  text-align: center;
}
.content {
  margin-top: 2%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 7rem;
}
.satu {
  height: 4rem;
  width: 4rem;
  background-image: url(~@/assets/vsc.svg);
  background-repeat: no-repeat;
  background-size: contain;
}
.satu:hover {
  transition: 0.2s ease-in-out;
  height: 5rem;
  width: 5rem;
}
.dua {
  height: 4rem;
  width: 4rem;
  background-image: url(~@/assets/html5-1.svg);
  background-repeat: no-repeat;
  background-size: contain;
}
.dua:hover {
  transition: 0.2s ease-in-out;
  height: 5rem;
  width: 5rem;
}
.tiga {
  height: 4rem;
  width: 4rem;
  background-image: url(~@/assets/css3-1.svg);
  background-repeat: no-repeat;
  background-size: contain;
}
.tiga:hover {
  transition: 0.2s ease-in-out;
  height: 5rem;
  width: 5rem;
}
.empat {
  height: 4rem;
  width: 4rem;
  background-image: url(~@/assets/nuxt.svg);
  background-repeat: no-repeat;
  background-size: contain;
}
.empat:hover {
  transition: 0.2s ease-in-out;
  height: 5rem;
  width: 5rem;
}
.lima {
  height: 4rem;
  width: 4rem;
  background-image: url(~@/assets/figma.svg);
  background-repeat: no-repeat;
  background-size: contain;
}
.lima:hover {
  transition: 0.2s ease-in-out;
  height: 5rem;
  width: 5rem;
}
.enam {
  height: 4rem;
  width: 4rem;
  background-image: url(~@/assets/git.svg);
  background-repeat: no-repeat;
  background-size: contain;
}
.enam:hover {
  transition: 0.2s ease-in-out;
  height: 5rem;
  width: 5rem;
}
.tujuh {
  height: 4rem;
  width: 4rem;
  background-image: url(~@/assets/logo-stackoverflow.svg);
  background-repeat: no-repeat;
  background-size: contain;
}
.tujuh:hover {
  transition: 0.2s ease-in-out;
  height: 5rem;
  width: 5rem;
}
.delapan {
  height: 3.5rem;
  width: 9rem;
  background-image: url(~@/assets/nodejs.svg);
  background-repeat: no-repeat;
  background-size: contain;
}
.delapan:hover {
  transition: 0.2s ease-in-out;
  height: 4rem;
  width: 10rem;
}
</style>