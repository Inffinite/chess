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
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
        </div>
        <div class="boards-wr">
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
        </div>
        <div class="boards-wr">
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
        </div>
        <div class="boards-wr">
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
        </div>
        <div class="boards-wr">
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
        </div>
        <div class="boards-wr">
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
        </div>
        <div class="boards-wr">
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
        </div>
        <div class="boards-wr">
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
          <div class="a1"></div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
@import "../styles/chess.css";
</style>
