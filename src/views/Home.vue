<template>
  <ion-page>
    <ion-content :fullscreen="true">
      <ion-grid>
        <ion-row class="ion-no-margin ion-no-padding">
          <ion-col size="12" class="ion-no-margin">
            <ion-card class="card-1 ion-no-margin">
              <ion-card-content>
                <ion-grid class="ion-no-padding">
                  <ion-row class="ion-no-padding ion-no-margin">
                    <ion-col size="10">
                      <h1>MK5,000,000</h1>
                      <p>Total balance</p>
                    </ion-col>
                    <ion-col size="2">
                      <img
                        src="../../public\assets\images\218390.png"
                        width="50"
                      />
                    </ion-col>
                  </ion-row>
                </ion-grid>
              </ion-card-content>
            </ion-card>
          </ion-col>
        </ion-row>

        <ion-row class="ion-no-margin ion-no-padding">
          <ion-col size="6" class="ion-no-margin">
            <ion-card class="card-2 ion-no-margin ion-no-padding">
              <ion-card-content>
                <ion-row>
                  <ion-col size="9" class="ion-no-padding">
                    <h1>MK5,000,00</h1>
                    <p>Income</p>
                  </ion-col>
                  <ion-col size="3" class="ion-no-padding">
                    <img
                      src="../../public\assets\images\218390.png"
                      width="50"
                    />
                  </ion-col>
                </ion-row>
              </ion-card-content>
            </ion-card>
          </ion-col>

          <ion-col size="6" class="ion-no-margin">
            <ion-card class="card-3 ion-no-margin ion-no-padding">
              <ion-card-content>
                <ion-row>
                  <ion-col size="9" class="ion-no-padding">
                    <h1>-MK5,000,00</h1>
                    <p>Expenses</p>
                  </ion-col>
                  <ion-col size="3" class="ion-no-padding">
                    <img
                      src="../../public\assets\images\218390.png"
                      width="50"
                    />
                  </ion-col>
                </ion-row>
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