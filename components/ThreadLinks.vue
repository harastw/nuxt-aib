<template>
  <div id="links-box">
    <div class="need-button-space">
      [Радио 410] [ii.booru-Архив РПГ] [acomics-cf-ost] [𝕏]
    </div>
    <div id="pic">
      <img src="../public/sci.jpg">
    </div>
    <div class="red-text"><b>Ычан — Аниме и манга</b></div>
  </div>
  <div class="gray-strip"></div>
  <div class="white-strip"></div>
</template>

<script lang="ts" setup>
</script>

<style>
.gray-strip {
  height: 1px;
  background-color: #9a9a9a;
}
.white-strip {
  height: 1px;
  background-color: #eeeeee;
}

#links-box {
}

.need-button-space {
  margin-bottom: 10px;
}

.red-text {
  color: #af0a15;
  text-align: center;
  font: 2.3em "Fira Sans", sans-serif;
}

#pic {
  text-align: center; /* Центрируем содержимое */
}

#pic img {
  display: inline-block; /* Устанавливаем inline-block для корректного центрирования */
}
</style>