<template>
  <AppWindow>
    <div>Xin chào</div>
    <button class="btn btn-primary" @click="test">Thử nghiệm</button>
  </AppWindow>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import AppWindow from "./components/AppWindow.vue";

export default defineComponent({
  name: "App",
  components: {
    AppWindow,
  },
  methods: {
    test() {
      console.log("1234");
    },
  },
});
</script>

<style></style>
