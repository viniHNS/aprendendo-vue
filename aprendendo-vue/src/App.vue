<template>
  <food-item />
  <food-item />
  <food-item />
</template>

<script></script>

<style>
  #app {
    display: flex;
    justify-content: center;
    align-items: center;
}

  #app > div {
    border: solid black 1px;
    display: inline-block;
    justify-content: center;
    margin: 10px;
    padding: 10px;
    background-color: lightgreen;
  }

  #app > div:hover {
  cursor: pointer;
}
</style>