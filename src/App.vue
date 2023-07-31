<template>
  <v-app >
    <dashboard/>
    <v-main>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script>
import dashboard from "@/components/Dashboard/Sidebar";

export default {
  components: {dashboard},

  name: 'App',

  data: () => ({
    //
  }),
};
</script>
<style lang="scss">
@font-face {
  font-family: IranSans;
  src: url("assets/font/iransans/IRANSansWeb_Light.eot");
  src: url("assets/font/iransans/IRANSansWeb_Light.eot?#iefix")
  format("embedded-opentype"),
  url("assets/font/iransans/IRANSansWeb_Light.woff2") format("woff2"),
  url("assets/font/iransans/IRANSansWeb_Light.woff") format("woff"),
  url("assets/font/iransans/IRANSansWeb_Light.ttf") format("truetype");
}

* {
  font-family: "IranSans", sans-serif;
}

.bg{
  background: rgb(234,253,254);
  background: linear-gradient(188deg, rgba(234,253,254,1) 40%, rgba(255,255,255,1) 56%, rgba(246,218,254,1) 84%);
}
</style>

