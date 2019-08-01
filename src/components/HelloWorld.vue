<template>
  <v-container fluid>
    <v-responsive>
      <v-layout align-center justify-space-around row>
        <v-flex xs6>
          <v-card class="item-large">
            <v-layout align-center justify-center row fill-height>
              <div class="place">ハフリンコ<span class="postfix"> 行</span></div>
            </v-layout>
            <v-layout column>
              <v-card class="timetable first">
                <v-layout align-center justify-space-between row>
                  <div class="timetable-title">先発</div>
                  <div class="timetable-time">12:34</div>
                  <div class="timetable-station">のりば<br>①</div>
                </v-layout>
              </v-card>
              <v-card class="timetable second" flat>
                <v-layout align-center justify-space-between row>
                  <div class="timetable-title">次発</div>
                  <div class="timetable-time">12:45</div>
                  <div class="timetable-station"></div>
                </v-layout>
              </v-card>
            </v-layout>
          </v-card>
        </v-flex>

        <v-flex xs6>
          <v-card class="item-large">
            <v-layout align-center justify-center row fill-height>
              <div class="place">嫌京<span class="postfix"> 行</span></div>
            </v-layout>
            <v-card class="timetable first">
              <v-layout align-center justify-space-between row>
                <div class="timetable-title">先発</div>
                <div class="timetable-time">12:50</div>
                <div class="timetable-station">のりば<br>②</div>
              </v-layout>
            </v-card>
            <v-card class="timetable second" flat>
              <v-layout align-center justify-space-between row>
                <div class="timetable-title">次発</div>
                <div class="timetable-time">13:15</div>
                <div class="timetable-station"></div>
              </v-layout>
            </v-card>
          </v-card>
        </v-flex>
      </v-layout>

      <v-layout align-center justify-space-around row>
        <v-flex xs6>
          <v-card class="item-small">
            <v-layout align-center justify-center row fill-height>
              <div class="place">さいたま <span class="postfix">行</span></div>
            </v-layout>
            <v-card class="timetable first">
              <v-layout align-center justify-space-between row>
                <div class="timetable-title">先発</div>
                <div class="timetable-time">12:46</div>
                <div class="timetable-station">のりば<br>③</div>
              </v-layout>
            </v-card>
          </v-card>
        </v-flex>

        <v-flex xs6>
          <v-card class="item-small">
            <v-layout align-center justify-center row fill-height>
              <div class="place">新宿 <span class="postfix">行</span></div>
            </v-layout>
            <v-card class="timetable first">
              <v-layout align-center justify-space-between row>
                <div class="timetable-title">先発</div>
                <div class="timetable-time">12:36</div>
                <div class="timetable-station">のりば<br>③</div>
              </v-layout>
            </v-card>
          </v-card>
        </v-flex>
      </v-layout>

      <v-layout align-center justify-space-around row>
        <v-flex xs6>
          <v-card class="item-small">
            <v-layout align-center justify-center row fill-height>
              <div class="place">大阪 <span class="postfix">行</span></div>
            </v-layout>
            <v-card class="timetable first">
              <v-layout align-center justify-space-between row>
                <div class="timetable-title">先発</div>
                <div class="timetable-time">13:11</div>
                <div class="timetable-station">のりば<br>①</div>
              </v-layout>
            </v-card>
          </v-card>
        </v-flex>

        <v-flex xs6>
          <v-card class="item-small">
            <v-layout align-center justify-center row fill-height>
              <div class="place">フィンランド <span class="postfix">行</span></div>
            </v-layout>
            <v-card class="timetable first">
              <v-layout align-center justify-space-between row>
                <div class="timetable-title">先発</div>
                <div class="timetable-time">14:11</div>
                <div class="timetable-station">のりば<br>①</div>
              </v-layout>
            </v-card>
          </v-card>
        </v-flex>
      </v-layout>
    </v-responsive>
  </v-container>
</template>

<script>
export default {
  data: () => ({
  }),
};
</script>

<style lang="scss">
.item-large {
  font-family: Arial, Helvetica, sans-serif;
  padding: 15px;
  margin: 5px;
  height: 40%;

  .place {
    font-size: 32pt;
    .postfix {
      font-size: 24pt;
    }
  }

  .timetable {
    padding: 5px;
    margin: 5px;
  }

  .first {
    text-align: center;
    padding: 0 60px;
    .timetable-title {
      font-size: 28pt;
    }
    .timetable-time {
      font-size: 72pt;
    }
    .timetable-station {
      width: 20%;
      font-size: 20pt;
    }
  }

  .second {
    text-align: center;
    padding: 0 70px;
    .timetable-title {
      font-size: 20pt;
    }
    .timetable-time {
      font-size: 30pt;
    }
    .timetable-station {
      width: 15%;
      font-size: 16pt;
    }
  }
}

.item-small {
  font-family: Arial, Helvetica, sans-serif;
  padding: 15px;
  margin: 5px;
  height: 40%;

  .place {
    font-size: 32pt;
    .postfix {
      font-size: 24pt;
    }
  }

  .timetable {
    padding: 5px;
    margin: 5px;
  }

  .first {
    text-align: center;
    padding: 0 60px;
    .timetable-title {
      font-size: 28pt;
    }
    .timetable-time {
      font-size: 60pt;
    }
    .timetable-station {
      width: 20%;
      font-size: 20pt;
    }
  }
}

</style>
