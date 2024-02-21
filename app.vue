<template>
  <div id="app" class="app">
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>
<script lang="ts">
import "@/assets/style/common.less";
export default defineComponent({
  setup() {
    useSeoMeta({
      title: "拓维信息官网",
      description:
        "拓维·梧桐云原生平台 提供一站式云原生解决方案,满足多云集群管理、云原生应用管理、应用持续交付、研发自动化、数字资产管理、国产化/信创迁移等多个核心业务场景,助力企业全面实现数字化转型。",
    });
  },
});
</script>
