<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<style lang="scss">
  * {
    margin: 0;
    padding: 0;
  }

  a {
    color: #000;
    text-decoration: none;
  }

  ul, li {
    list-style: none;
  }

  h1, h2, h3, h4 {
    font-weight: normal;
  }

  .page {
    width: 80%;
    margin: 0 auto;
    overflow: hidden;
  }
</style>
