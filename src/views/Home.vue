<template>
  <ion-page>
    <ion-content :fullscreen="true">
      <ion-grid>
        <ion-row>
          <ion-col size="4">
            <p class="fade">Robert Sageme</p>
          </ion-col>
          <ion-col size="4"> </ion-col>
          <ion-col size="4">
            <p class="fade">05 May, 2021</p>
          </ion-col>
        </ion-row>
      </ion-grid>
      
      <ion-grid>
        <ion-row class="ion-no-margin ion-no-padding">
          <ion-col size="12" class="ion-no-margin">
            <ion-card class="card-1 ion-no-margin">
              <ion-card-content>
                <h1>5</h1>
                <p>Members in this group</p>
              </ion-card-content>
            </ion-card>
          </ion-col>
        </ion-row>

        <ion-row class="ion-no-margin ion-no-padding">
          <ion-col size="6" class="ion-no-margin">
            <ion-card class="card-2 ion-no-margin ion-no-padding">
              <ion-card-content class="ion-no-padding">
              <ion-row>
                <ion-col size="8">
                  
                </ion-col>
                <ion-col size="4">
                  
                </ion-col>
              </ion-row>
              </ion-card-content>
            </ion-card>
          </ion-col>
          
          <ion-col size="6" class="ion-no-margin">
            <ion-card class="card-3 ion-no-margin ion-no-padding">
              <ion-card-content>
                <h1>5</h1>
                <p>Members in this group</p>
              </ion-card-content>
            </ion-card>
          </ion-col>
        </ion-row>
      </ion-grid>
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import {
  IonContent,
  IonPage,
  IonGrid,
  IonRow,
  IonCol,
  IonCardContent,
  IonCard,
} from "@ionic/vue";
import { defineComponent } from "vue";
import {
  star,
  statsChartOutline,
  personAddOutline,
  printOutline,
  locationOutline,
  homeOutline,
  calendarClearOutline,
} from "ionicons/icons";

export default defineComponent({
  name: "Home",
  components: {
    IonContent,
    IonPage,
    IonGrid,
    IonRow,
    IonCol,
    IonCardContent,
    IonCard,
  },
  setup() {
    return {
      star,
      statsChartOutline,
      personAddOutline,
      printOutline,
      locationOutline,
      homeOutline,
      calendarClearOutline,
    };
  },
});
</script>

<style scoped>
</style>