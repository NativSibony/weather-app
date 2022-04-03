<template>
  <div class="current-day">
    <CurrentDayHeader />
    <CurrentDayInfo />
  </div>
</template>

<script>
import CurrentDayHeader from "./CurrentDayHeader.vue";
import CurrentDayInfo from "./CurrentDayInfo.vue";
export default { components: { CurrentDayHeader, CurrentDayInfo } };
</script>

<style>
.current-day {
  display: flex;
  flex-direction: column;
  gap: 1rem;
}
</style>
