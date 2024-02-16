<template>
  <div id="app" class="app">
    <n-config-provider :theme="'darkTheme'" abstract>
      <NuxtLayout>
        <NuxtPage />
      </NuxtLayout>
    </n-config-provider>
  </div>
</template>
<script lang="ts">
export default defineComponent({
  setup() {
    useSeoMeta({
      title: "非常非常NB的个人网站",
      description: "一个用于学习Nuxt3的个人网站项目",
    });
  },
});
</script>
