<script setup>
const player = ref("X");
const board = ref([
  ["", "", ""],
  ["", "", ""],
  ["", "", ""],
]);
const CalculateWinner = (board) => {
  console.log("🚀 ~ file: index.vue:9 ~ CalculateWinner ~ board", board);
};
CalculateWinner(board.value);
</script>
<template>
  <div class="bg-red-500">hello</div>
</template>
