<script setup>

import Microsoft from "../components/Microsoft.vue";
import {ref, watch} from "vue";

let nosplash = ref(localStorage.getItem("nosplash") | "false")

// 可以直接侦听一个 ref
watch(nosplash, async (newSplash, oldSplash) => {
  localStorage.setItem("nosplash", String(newSplash))
})

</script>

<template>
  <div style="display: flex; flex-direction: column; justify-content: center; align-items: center; position: absolute; width: 100vw; height: 100vh; top: 0; left: 0;">
    <img style="width: 100px" src="../assets/copilot.svg" alt="Copilot Logo">
    <p class="splash_primary">BingGPT</p>
    <p class="splash_secondary">Powered By Copilot with Bing Chat</p>
    <p class="splash_check"><input type="checkbox" v-model="nosplash">don't show this again</p>
    <a style='display: block; margin-top: 10px; font-size: 25px; text-align: center;' href='https://www.bing.com/fd/auth/signin?action=interactive&provider=windows_live_id&return_url=https:%2F%2fwww.bing.com%2F'><Microsoft></Microsoft></a>
  </div>
</template>

<style scoped>

.splash_primary {
  padding-top: 30px;
  font-family: SansSerif,sans-serif;
  font-size: 30px;
}

.splash_secondary {
  font-family: SansSerif,sans-serif;
}

.splash_check {
  font-family: SansSerif,sans-serif;
}

@media (prefers-color-scheme: dark) {
  .splash_primary {
    color: #FFFFFF;
  }

  .splash_secondary {
    color: #FFFFFF;
  }

  .splash_check {
    color: #FFFFFF;
  }
}

</style>