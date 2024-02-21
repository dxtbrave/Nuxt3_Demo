<template>
  <div class="header-box">
    <div class="header-nav-box">
      <div class="global-default-width header-content">
        <!-- Logo图标 -->
        <div class="logo-img">
          <a href="/">
            <img src="~@/assets/images/talkweb_logo_1.80267e1.png" />
          </a>
        </div>
        <!-- 顶部菜单选项 -->
        <ul class="header-min-ul position-ul">
          <li v-for="(item, index) in headerNavList" :key="index">
            <div class="li-box">
              <div class="first-title-box">
                <a target="_self" class="first-title">{{ item.title }}</a>
              </div>
            </div>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>
<script>
import "./index.less";
export default {
  setup() {
    const headerNavList = ref([{ title: "产品", id: 1 }]);
    return { headerNavList };
  },
};
</script>
