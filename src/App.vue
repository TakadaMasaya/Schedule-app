<template>
  <div>
    <myheader />
    <router-view />
    <myfooter />
  </div>
</template>

<script>

import myheader from './components/myheader';
import myfooter from './components/myfooter';

export default {
  components: {
    myheader,
    myfooter
  }
}
</script>

<style>
  * {
    margin: 0;
    padding: 0;
  }

  button {
    background-color: transparent;
    border: none;
    cursor: pointer;
    outline: none;
    padding: 0;
    appearance: none;
  }

  .top-container {
    padding-top: 100px;
    width: 90%;
    margin: 0 5%;
    z-index: 1;
  }

  h1 {
    color: rgba(200, 70, 70, 0.9);
    font-size: 40px;
    letter-spacing: 10px;
    margin: 0 30px 20px;
  }
</style>