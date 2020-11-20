<template>
  <div class="introContainer">
    <div class="textIntro">
      <!-- <p>Lorem <span id="spin"></span>!</p> -->
      <span style="font-size: 50px;">HELLO</span>
      <div class="textAnimation">
        <span>I AM</span>
        <span id="spin"></span>
        <!-- <div class="animate1"><h2>FAJAR</h2></div>
        <div class="animate2"><h2>F.E. ENGGINEER</h2></div> -->
      </div>
    </div>
    <div class="imageIntro">
      <Bgsvg />
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.introContainer {
  margin-top: 5%;
  display: flex;
  justify-content: space-evenly;
  /* background-color: turquoise; */
}
.imageIntro {
  width: 50%;
  height: 50%;
  /* background-color: teal; */
}
.textIntro {
  width: 50%;
  height: 50%;
  font-weight: 800;
  color: white;
}
.textAnimation {
  display: flex;
}
/* .animate1,
.animate2 {
  color: #6c63ff;
  position: absolute;
  margin-left: 100px;
}
.animate1 {
  animation: ani1 infinite;
  animation-delay: 3s;
}
.animate2 {
  animation: ani1 4s infinite;
}
/* .animate3 {
  animation: ani1 10s infinite;
} */
/* @keyframes ani1 { 
  0% {
    opacity: 0;
  }
  50% {
    opacity: 1;
  }
  100% {
    opacity: 0;
  }
} */

/* @keyframes ani2 {
  65% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
} */
#spin {
  color:#6c63ff;
}
span {
  font-size: 35px;
}
#spin:after {
  content:"";
  animation: spin 5s ease-in-out infinite;
  margin-left: 10px;
}
@keyframes spin {
  0% {
    content:" FAJAR";
  }
  100% {
    content: " A JUNIOR F.E. ENGINEER";
  }
  /* 0% { content:"ipsum"; }
  10% { content:"dolor"; }
  20% { content:"sit"; }
  30% { content:"amet"; }
  40% { content:"consectetur"; }
  50% { content: "adipisicing"; }
  60% { content: "elit"; }
  70% { content: "Hic"; }
  80% { content: "atque"; }
  100% { content: "fuga"; } */
}
</style>