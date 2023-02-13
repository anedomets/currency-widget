<template>
  <div :class="'main'">
<!--    <CurrencyCard v-if="this.show"/>-->
<!--    <Currency v-if="!this.show"/>-->
<!--    <button v-on:click="isShow">{{this.changeButtonText()}}</button>-->
    <router-view />
  </div>
</template>

<script src="./app.ts"></script>
<style src="./app.css"></style>
