<template>
  <div class="default-layout">
    <!-- <n-layout>
      <n-layout-content>
        <slot />
      </n-layout-content>
      <n-layout-footer></n-layout-footer>
    </n-layout> -->
    <!-- 头部区域 -->
    <defaultLayoutHeader />
    <div>
      <slot />
    </div>
  </div>
</template>
<script>
import {
  NLayout,
  NLayoutContent,
  NLayoutFooter,
  NLayoutHeader,
} from "naive-ui";
export default {
  components: { NLayout, NLayoutContent, NLayoutFooter, NLayoutHeader },
};
</script>
