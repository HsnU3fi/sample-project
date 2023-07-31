<template>
  <div>
    <v-app-bar
        app
        scroll-target="#scrolling-techniques-7"
        color="#EAFDFE"
        absolute
        elevate-on-scroll>
      <v-toolbar-title>
        <img src="../../assets/logo/Company Name (1).png" width="250" />
      </v-toolbar-title>

      <v-spacer></v-spacer>

      <v-btn
          depressed
          class="space"
          color="#fff"
          width="147"
          height="43"
          rounded
      >
        <h4 dir="rtl" style="margin-right: 10px">۱ پیام دارید</h4>
        <img src="../../assets/icon/icon (13).png" sizes="80" alt="پیام"/>
      </v-btn>
      <v-btn
          depressed
          color="#fff"
          rounded
          height="43"
          width="159"
      >
        <h4>سارا محمدیان</h4>

        <img src="../../assets/avatar.png" sizes="80" alt="آواتار"/>
        <v-btn

            style="margin-right: -15px"
            height="18"
            width="18"
            fab
            class="bg_btn"
        >
          <v-icon color="#fff" size="25">
            mdi-menu-down
          </v-icon>
        </v-btn>
      </v-btn>

    </v-app-bar>
  </div>
</template>

<script>

export default {

}
</script>

<style lang="scss">
.space {
  margin: 20px;
}
.bg_btn{
  background: rgb(43,174,232);
  background: linear-gradient(200deg, rgba(43,174,232,1) 60%, rgba(75,237,234,1) 100%);
}
</style>
