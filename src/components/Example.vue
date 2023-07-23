<template>
  <ion-header>
    <ion-toolbar>
      <ion-title>Header Toolbar</ion-title>
    </ion-toolbar>
  </ion-header>
  <ion-content color="light">
    <ion-list :inset="true">
      <ion-item>
        <ion-label>Pokémon Yellow</ion-label>
      </ion-item>
      <ion-item>
        <ion-label>Mega Man X</ion-label>
      </ion-item>
      <ion-item>
        <ion-label>The Legend of Zelda</ion-label>
      </ion-item>
      <ion-item>
        <ion-label>Pac-Man</ion-label>
      </ion-item>
      <ion-item>
        <ion-label>Super Mario World</ion-label>
      </ion-item>
    </ion-list>
  </ion-content>
  <ion-footer>
  <ion-toolbar>
    <ion-title>Footer</ion-title>
  </ion-toolbar>
</ion-footer>
</template>

<script lang="ts">
import { IonContent, IonItem, IonLabel, IonList } from '@ionic/vue';
import { defineComponent } from 'vue';

export default defineComponent({
  components: { IonContent, IonItem, IonLabel, IonList },
});
</script>
