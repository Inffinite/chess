<script setup>
import { ref } from "vue";

defineProps({
  msg: String,
});

const count = ref(0);
</script>

<template>
  <div class="chess">
    <div class="board">
      <div>
        <div class="boards-wr">
          <div class="a1 light-sqaure"></div>
          <div class="a1 dark-square"></div>
          <div class="a1 light-sqaure"></div>
          <div class="a1 dark-square"></div>
          <div class="a1 light-sqaure"></div>
          <div class="a1 dark-square"></div>
          <div class="a1 light-sqaure"></div>
          <div class="a1 dark-square"></div>
        </div>
        <div class="boards-wr">
          <div class="a1 dark-square"></div>
          <div class="a1 light-sqaure"></div>
          <div class="a1 dark-square"></div>
          <div class="a1 light-sqaure"></div>
          <div class="a1 dark-square"></div>
          <div class="a1 light-sqaure"></div>
          <div class="a1 dark-square"></div>
          <div class="a1 light-sqaure"></div>
        </div>
        <div class="boards-wr">
          <div class="a1 light-sqaure"></div>
          <div class="a1 dark-square"></div>
          <div class="a1 light-sqaure"></div>
          <div class="a1 dark-square"></div>
          <div class="a1 light-sqaure"></div>
          <div class="a1 dark-square"></div>
          <div class="a1 light-sqaure"></div>
          <div class="a1 dark-square"></div>
        </div>
        <div class="boards-wr">
          <div class="a1 dark-square"></div>
          <div class="a1 light-sqaure"></div>
          <div class="a1 dark-square"></div>
          <div class="a1 light-sqaure"></div>
          <div class="a1 dark-square"></div>
          <div class="a1 light-sqaure"></div>
          <div class="a1 dark-square"></div>
          <div class="a1 light-sqaure"></div>
        </div>
        <div class="boards-wr">
          <div class="a1 light-sqaure"></div>
          <div class="a1 dark-square"></div>
          <div class="a1 light-sqaure"></div>
          <div class="a1 dark-square"></div>
          <div class="a1 light-sqaure"></div>
          <div class="a1 dark-square"></div>
          <div class="a1 light-sqaure"></div>
          <div class="a1 dark-square"></div>
        </div>
        <div class="boards-wr">
          <div class="a1 dark-square"></div>
          <div class="a1 light-sqaure"></div>
          <div class="a1 dark-square"></div>
          <div class="a1 light-sqaure"></div>
          <div class="a1 dark-square"></div>
          <div class="a1 light-sqaure"></div>
          <div class="a1 dark-square"></div>
          <div class="a1 light-sqaure"></div>
        </div>
        <div class="boards-wr">
          <div class="a1 light-sqaure"></div>
          <div class="a1 dark-square"></div>
          <div class="a1 light-sqaure"></div>
          <div class="a1 dark-square"></div>
          <div class="a1 light-sqaure"></div>
          <div class="a1 dark-square"></div>
          <div class="a1 light-sqaure"></div>
          <div class="a1 dark-square"></div>
        </div>
        <div class="boards-wr">
          <div class="a1 dark-square"></div>
          <div class="a1 light-sqaure"></div>
          <div class="a1 dark-square"></div>
          <div class="a1 light-sqaure"></div>
          <div class="a1 dark-square"></div>
          <div class="a1 light-sqaure"></div>
          <div class="a1 dark-square"></div>
          <div class="a1 light-sqaure"></div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
@import "../styles/chess.css";
</style>
