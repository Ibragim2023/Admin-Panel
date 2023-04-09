<script setup lang="ts"></script>

<template>
  <div class="bg-[#ff6c03] text-white p-3">
    <div class="headContent mx-auto flex justify-between items-center">
      <div class=" w-2/5 flex justify-between items-center">
        <div>
          <h1 class="text-3xl">Jig-Fishing</h1>
        </div>
        <div class="bg-[#1f1f1f] p-2 rounded-md w-96 flex justify-between items-center">
          <input placeholder="Поиск по Jig-Fishing" class="text-white bg-[#1f1f1f] w-full mx-3" type="text" />
          <span class="mdi mdi-magnify text-white"></span>
        </div>
      </div>
      <div class="w-10 h-10 rounded-full overflow-hidden bg-[#1f1f1f]">
      </div>
    </div>
  </div>
</template>
<style scoped>
.headContent {
  width: 1500px;
}
</style>
