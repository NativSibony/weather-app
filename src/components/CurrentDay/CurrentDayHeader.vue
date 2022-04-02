<template>
  <div class="card">
    <div class="card-header">
      <h3>Amsterdam, Netherlands Weather</h3>
      <p class="pale">as of 8:49 am CEST</p>
      <h1 style="color: #ffcc4a">7°</h1>
    </div>
    <div class="line-break"></div>
    <div class="card-body">
      <h3 style="padding-top: 10px">Partly Cloudly</h3>
      <p class="pale">1% chance of rain through 9am</p>
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
}

.card {
  background: white;
  padding: 1.2rem;
}
.pale {
  color: #bbb;
}
.line-break {
  height: 0.05rem;
  width: 100%;
  background: rgba(187, 187, 187, 0.35);
}
</style>
