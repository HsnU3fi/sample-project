<template>
  <div>
    <appbar/>

    <v-navigation-drawer
        right
        class="bg_sidebar"
        mini-variant-width="70"
        v-model="drawer"
        width="300"
        app
    >

      <v-list-item-content style="padding-top: 45px">
        <v-list-item>
          <v-list-item-title style="margin-right: -5px" class="title_sidebar" dir="rtl">داشبورد</v-list-item-title>
          <v-list-item-avatar>
            <img src="../../assets/icon/Icon.png" sizes="80" alt="داشبورد"/>
          </v-list-item-avatar>
        </v-list-item>
      </v-list-item-content>

      <v-list-item-group active-class="hover_tile" dark>
        <v-list nav>


          <v-list-item
              dir="rtl"
              link
              to="/"
              style="height: 41px"
          >
            <img src="../../assets/icon/Icon1.png" sizes="80" alt="برنامه"/>
            <v-list-item-content>
              <span class="title_sidebar">برنامه</span>
            </v-list-item-content>
            <v-list-item-action>
              <v-icon color="black">mdi-chevron-down</v-icon>
            </v-list-item-action>
          </v-list-item>

          <v-list-item
              dir="rtl"
              dark
              link
              to="/"
              style="height: 41px"
          >
            <img src="../../assets/icon/Icon2.png" sizes="80" alt="داشبورد"/>
            <v-list-item-content>
              <span class="title_sidebar">بسته های منتخب</span>
            </v-list-item-content>
            <v-list-item-action>
              <v-icon color="black">mdi-chevron-down</v-icon>
            </v-list-item-action>
          </v-list-item>

          <v-list-item
              dir="rtl"
              dark
              link
              to="/"
              style="height: 41px"
          >
            <img src="../../assets/icon/Icon3.png" sizes="80" alt="هشدارها"/>
            <v-list-item-content>
              <span class="title_sidebar">هشدارها</span>
            </v-list-item-content>
            <v-list-item-action>
              <v-icon color="black">mdi-chevron-down</v-icon>
            </v-list-item-action>
          </v-list-item>


          <v-list-item
              dir="rtl"
              dark
              link
              to="/"
              style="height: 41px"
          >
            <img src="../../assets/icon/Icon4.png" sizes="80" alt="تست نرم افزار"/>
            <v-list-item-content>
              <span class="title_sidebar">تست نرم افزار</span>
            </v-list-item-content>
            <v-list-item-action>
              <v-icon color="black">mdi-chevron-down</v-icon>
            </v-list-item-action>
          </v-list-item>

          <v-list-item
              dir="rtl"
              dark
              link
              to="/"
              style="height: 41px"
          >
            <img src="../../assets/icon/Icon5.png" sizes="80" alt="تست نرم افزار"/>
            <v-list-item-content>
              <span class="title_sidebar">اتصالات کاربری</span>
            </v-list-item-content>

          </v-list-item>


          <v-list-item
              dir="rtl"
              dark
              link
              to="/"
              style="height: 41px"
          >
            <img src="../../assets/icon/Icon4.png" sizes="80" alt="برنامه ریزی"/>
            <v-list-item-content>
              <span class="title_sidebar">برنامه ریزی</span>
            </v-list-item-content>
            <v-list-item-action>
              <v-icon color="black">mdi-chevron-down</v-icon>
            </v-list-item-action>
          </v-list-item>

          <v-list-item
              dir="rtl"
              dark
              link
              to="/"
              style="height: 41px"
          >
            <img src="../../assets/icon/Icon6.png" sizes="80" alt="برنامه ریزی هوشمند"/>
            <v-list-item-content>
              <span class="title_sidebar">برنامه ریزی هوشمند</span>
            </v-list-item-content>
            <v-list-item-action>
              <v-icon color="black">mdi-chevron-down</v-icon>
            </v-list-item-action>
          </v-list-item>


          <v-list-item
              dir="rtl"
              dark
              link
              to="/"
              style="height: 41px"
          >
            <img src="../../assets/icon/Icon7.png" sizes="80" alt="مشاهده پروفایل"/>
            <v-list-item-content>
              <span class="title_sidebar">مشاهده پروفایل</span>
            </v-list-item-content>

          </v-list-item>


          <v-list-item
              dir="rtl"
              dark
              link
              to="/"
              style="height: 41px"
          >
            <img src="../../assets/icon/Icon8.png" sizes="80" alt="پشتیبانی"/>
            <v-list-item-content>
              <span class="title_sidebar">پشتیبانی</span>
            </v-list-item-content>

          </v-list-item>

          <v-list-item
              dir="rtl"
              dark
              link
              to="/"
              style="height: 41px"
          >
            <img src="../../assets/icon/Icon9.png" sizes="80" alt="راهنما"/>
            <v-list-item-content>
              <span class="title_sidebar">راهنما</span>
            </v-list-item-content>

          </v-list-item>


          <v-list-item
              dir="rtl"
              dark
              link
                to="/"
              style="height: 41px"
          >
            <img src="../../assets/icon/Icon10.png" sizes="80" alt="درباره ما"/>
            <v-list-item-content>
              <span class="title_sidebar">درباره ما</span>
            </v-list-item-content>

          </v-list-item>
          <v-divider  />

          <v-list-item
              dir="rtl"
              dark
              link
              to="/"
              style="height: 41px"
          >
            <img src="../../assets/icon/Icon12.png" sizes="80" alt="خروج"/>
            <v-list-item-content>
              <span class="title_sidebar">خروج</span>
            </v-list-item-content>

          </v-list-item>

        </v-list>
      </v-list-item-group>
    </v-navigation-drawer>

  </div>
</template>

<script>
//======================================================================================================================
import appbar from "@/components/Dashboard/AppBar";

export default {
  components: {
    appbar,
  },

  //======================================================================================================================

};
</script>
<style lang="scss">
.hover_tile:hover {
  border-radius: 4px;
  background-color: #33D1FF;
}

.title_sidebar {
  font-weight: bold;
  font-size: 15px;
  color: black;
  margin-right: 15px
}

.bg_sidebar{
  background: rgb(246,255,255);
  background: linear-gradient(183deg, rgba(246,255,255,1) 79%, rgba(241,241,254,1) 95%);}


.v-navigation-drawer--mini-variant,
.v-navigation-drawer {
  overflow: visible !important;
}
  </style>
