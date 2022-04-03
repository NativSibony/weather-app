<template>
  <div class="card">
    <p>Weather today in Amsterdam, Netherlands</p>
    <div class="feels-like">
      <h1>3°</h1>
    </div>
    <div class="chart">
      <div class="group">
        <div class="group-data">
          <i class="wi wi-thermometer"></i>
          <p>High &nbsp; / &nbsp; Low</p>
          <p>--/3°</p>
        </div>
        <div class="group-data">
          <i class="wi wi-strong-wind"></i>
          <p>Wind</p>
          <p>24 &nbsp; km/h</p>
        </div>
      </div>
      <div class="group">
        <div class="group-data">
          <i class="wi wi-humidity"></i>
          <p>Humidity</p>
          <p>61%</p>
        </div>
        <div class="group-data">
          <i class="wi wi-raindrop"></i>
          <p>Dew &nbsp; Point</p>
          <p>0°</p>
        </div>
      </div>
      <div class="group">
        <div class="group-data">
          <i class="wi wi-barometer"></i>
          <p>Pressure</p>
          <p>61%</p>
        </div>
        <div class="group-data">
          <i class="wi wi-day-sunny"></i>
          <p>UV &nbsp; Index</p>
          <p>0 &nbsp; of &nbsp; 10</p>
        </div>
      </div>
      <div class="group">
        <div class="group-data">
          <i class="wi wi-smog"></i>
          <p>Visibility</p>
          <p>Unlimited</p>
        </div>
        <div class="group-data">
          <i class="wi wi-moon-alt-waxing-crescent-3"></i>
          <p>Moon Phase</p>
          <p>Waxing Gibbous</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
h1 {
  font-size: 2.5rem;
}

h1,
h3,
p {
  letter-spacing: -1px;
}

p {
  font-size: 0.75rem;
  font-weight: 700;
}

.card {
  background: transparent;
  padding: 1.2rem;
}
.group {
  display: flex;
  column-gap: 20px;
}
.group-data {
  display: grid;
  grid-template-columns: 40px 150px 100px;
  align-items: center;
  padding: 11px 3px;
  border-bottom: 2px solid rgba(187, 187, 187, 0.2);
}
.group-data i {
  text-align: left;
}
.group-data p:nth-child(2) {
  text-align: left;
}
.group-data p:nth-child(3) {
  text-align: right;
}
</style>
