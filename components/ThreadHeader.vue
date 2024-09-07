<template>
  <div id="main-line">
    <div>
    [<a href="google.com"><u>d</u></a>&nbsp; | &nbsp;<a href="google.com"><u>au</u></a>&nbsp; / &nbsp;<a href="google.com"><u>b</u></a>&nbsp; / &nbsp;<a href="google.com"><u>bro</u></a> 
    &nbsp;/&nbsp; <a href="google.com"><u>cu</u></a> &nbsp;/&nbsp; <a href="google.com"><u>dev</u></a> &nbsp;/&nbsp; <a href="google.com"><u>hr</u></a> &nbsp;/&nbsp; <a href="google.com"><u>l</u></a>&nbsp;/&nbsp; <a href="google.com"><u>m</u></a> &nbsp;/&nbsp; <a href="google.com"><u>mu</u></a> &nbsp;/&nbsp; <a href="google.com"><u>o</u></a> &nbsp;/&nbsp; <a href="google.com"><u>s</u></a>
    &nbsp;/&nbsp; <a href="google.com"><u>tran</u></a> &nbsp;/&nbsp; <a href="google.com"><u>tu</u></a> &nbsp;/&nbsp; <a href="google.com"><u>tv</u></a> &nbsp;/&nbsp; <a href="google.com"><u>vg</u></a> &nbsp;/&nbsp; <a href="google.com"><u>x</u></a> &nbsp;|&nbsp; <a href="google.com"><u>a</u></a> &nbsp;/&nbsp; <a href="google.com"><u>aa</u></a> &nbsp;/&nbsp; <a href="google.com"><u>c</u></a>
    &nbsp;/&nbsp; <a href="google.com"><u>fi</u></a> &nbsp;/&nbsp; <a href="google.com"><u>jp</u></a> &nbsp;/&nbsp; <a href="google.com"><u>rm</u></a> &nbsp;/&nbsp; <a href="google.com"><u>tan</u></a> &nbsp;/&nbsp; <a href="google.com"><u>to</u></a> &nbsp;/&nbsp; <a href="google.com"><u>ts</u></a> &nbsp;/&nbsp; <a href="google.com"><u>vn</u></a>]
    </div>

    <div class="options-container">
      <select>
        <option value="value1">Burichan</option>
        <option value="value1">Footaba</option>
        <option value="value1" selected>Gurochan</option>
        <option value="value1">Tommorow</option>
      </select> &nbsp;
        <a href="https://htmlacademy.ru">
          <img src="../public/archive.svg" height="25">
        </a>&nbsp;
        <a href="https://htmlacademy.ru">
          <img src="../public/grid.svg" height="25">
        </a>&nbsp;
        <a href="https://htmlacademy.ru">
          <img src="../public/house.svg" height="25">
        </a>&nbsp;
    </div>
  </div>
  <div class="red-strip"></div>
</template>

<script lang="ts" setup>
  
</script>

<style scoped>
.red-strip {
  height: 1px;
  background-color: #cc9580;
}

#main-line {
  display: flex;
  justify-content: space-between;
}
.options-container {
  display: flex;
  align-items: center;
}
</style>