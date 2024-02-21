<template>
  <div class="index-page">
    <h1>{{ count }}</h1>
    <h1>{{ num }}</h1>
    <NuxtLink to="/about">关于</NuxtLink>
    <NButton>666</NButton>
  </div>
</template>

<script>
import { NButton } from "naive-ui";
export default {
  setup() {
    const count = ref(0);
    const num = useState("num", () => 123);
    return { count, num };
  },
  components: { NButton },
};
</script>

<style></style>
