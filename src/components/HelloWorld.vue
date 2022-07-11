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
          <div class="a1 light-sqaure">C</div> 
          <div class="a1 dark-square">K</div>
          <div class="a1 light-sqaure">B</div>
          <div class="a1 dark-square">QN</div>
          <div class="a1 light-sqaure">KN</div>
          <div class="a1 dark-square">B</div>
          <div class="a1 light-sqaure">K</div>
          <div class="a1 dark-square">C</div>
        </div>
        <div class="boards-wr">
          <div class="a1 dark-square">P</div>
          <div class="a1 light-sqaure">P</div>
          <div class="a1 dark-square">P</div>
          <div class="a1 light-sqaure">P</div>
          <div class="a1 dark-square">P</div>
          <div class="a1 light-sqaure">P</div>
          <div class="a1 dark-square">P</div>
          <div class="a1 light-sqaure">P</div>
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
          <div class="a1 light-sqaure">P</div> 
          <div class="a1 dark-square">P</div>
          <div class="a1 light-sqaure">P</div>
          <div class="a1 dark-square">P</div>
          <div class="a1 light-sqaure">P</div>
          <div class="a1 dark-square">P</div>
          <div class="a1 light-sqaure">P</div>
          <div class="a1 dark-square">P</div>
        </div>
        <div class="boards-wr">
          <div class="a1 dark-square">C</div>
          <div class="a1 light-sqaure">K</div>
          <div class="a1 dark-square">B</div>
          <div class="a1 light-sqaure">QN</div>
          <div class="a1 dark-square">KN</div>
          <div class="a1 light-sqaure">B</div>
          <div class="a1 dark-square">K</div>
          <div class="a1 light-sqaure">C</div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
@import "../styles/chess.css";
</style>
