<template>
  <div class="index-page">
    <h1>{{ count }}</h1>
    <h1>{{ num }}</h1>
  </div>
</template>

<script>
export default {
  setup() {
    const count = ref(0);
    const num = useState("num", () => 123);
    return { count, num };
  },
};
</script>

<style></style>
