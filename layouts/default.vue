import { NLayout } from 'naive-ui';
<template>
  <div class="default-layout">
    <n-layout>
      <n-layout-header><defaultLayoutHeader /></n-layout-header>
      <n-layout-content>
        <slot />
      </n-layout-content>
      <n-layout-footer></n-layout-footer>
    </n-layout>
  </div>
</template>
