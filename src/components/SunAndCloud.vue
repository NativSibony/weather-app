<template>
  <div class="sun-and-cloud">
    <div class="sun"></div>
    <div class="cloud">
      <div class="cloud-right"></div>
      <div class="cloud-left"></div>
      <div class="cloud-mid"></div>
    </div>
  </div>
  <!-- <div class="only-sun">
    <div class="sun"></div>
  </div>
  <div class="only-cloud">
    <div class="cloud"></div>
  </div> -->
</template>

<style>
.sun-and-cloud {
  position: relative;
  /* left: -30%; */
  top: -20%;
  /* display: flex;
  justify-self: center;
  align-self: center; */
}

.sun {
  position: absolute;
  top: -50px;
  /* left: 300px; */

  width: 180px;
  height: 180px;
  border-radius: 50%;
  background: radial-gradient(circle at bottom, #ff8f1f 30%, #ffd34f, #fff48a);
}

.cloud {
  position: absolute;
  top: 0;
  left: -300px;

  margin: auto;
  display: flex;
  align-items: baseline;
}
.cloud-left,
.cloud-right {
  width: 100px;
  height: 100px;
  background: linear-gradient(90deg, #fefefe90 60%, transparent 40%);
  border-radius: 50% 0 0 50%;
  position: relative;
  left: 40px;
  backdrop-filter: blur(2px);
}
.cloud-right {
  border-radius: 0 50% 50% 0;
  left: 350px;
  background: linear-gradient(-90deg, #fefefe90 60%, transparent 40%);
}
.cloud-mid {
  backdrop-filter: blur(2px);

  width: 190px;
  height: 190px;
  background: #fefefe90;
  border-radius: 50% 50% 0% 0%;
}
</style>
