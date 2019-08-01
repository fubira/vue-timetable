<template>
  <v-container fluid>
    <v-layout column>
      <v-card class="item">
        <v-flex xsl2>
          <div class="resultContainer">
            <v-layout align-center justify-space-around row fill-height>
              <div style="width: 10%" class="display-1">先発</div>
              <div class="display-3">12:34</div>
              <div style="width: 40%" class="display-2">ハフリンコ <span class="display-1">行</span></div>
              <div class="display-1">1番</div>
            </v-layout>
          </div>
        </v-flex>
      </v-card>

      <v-card class="item">
        <v-flex xsl2>
          <div class="resultContainer">
            <v-layout align-center justify-space-around row fill-height>
              <div style="width: 10%" class="display-1">次発</div>
              <div class="display-3">12:55</div>
              <div style="width: 40%" class="display-2">名古屋 <span class="display-1">行</span></div>
              <div class="display-1">2番</div>
            </v-layout>
          </div>
        </v-flex>
      </v-card>

      <v-card class="item">
        <v-flex xsl2>
          <div class="resultContainer">
            <v-layout align-center justify-space-around row fill-height>
              <div style="width: 10%" class="display-1"></div>
              <div class="display-3">13:10</div>
              <div style="width: 40%" class="display-2">東京 <span class="display-1">行</span></div>
              <div class="display-1">3番</div>
            </v-layout>
          </div>
        </v-flex>
      </v-card>

      <v-card class="item">
        <v-flex xsl2>
          <div class="resultContainer">
            <v-layout align-center justify-space-around row fill-height>
              <div style="width: 10%" class="display-1"></div>
              <div class="display-3">13:22</div>
              <div style="width: 40%" class="display-2">大阪 <span class="display-1">行</span></div>
              <div class="display-1">2番</div>
            </v-layout>
          </div>
        </v-flex>
      </v-card>

    </v-layout>
  </v-container>
</template>

<script>
export default {
  data: () => ({
  }),
};
</script>

<style lang="scss">

.item {
  padding: 20px;
  margin: 5px;
}
</style>
