<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Item List</ion-title>
        <ion-searchbar></ion-searchbar>
      </ion-toolbar>
    </ion-header>
<!--    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Tab 1</ion-title>
        </ion-toolbar>
      </ion-header>
      <ExploreContainer name="Tab 1 page" />
    </ion-content>-->
    <ion-content :fullscreen="true">
      <ion-list>
        <ion-item>Amsterdam</ion-item>
        <ion-item>Bogota</ion-item>
        <ion-item>Buenos Aires</ion-item>
        <ion-item>Cairo</ion-item>
        <ion-item>Dhaka</ion-item>
        <ion-item>Edinburgh</ion-item>
        <ion-item>Geneva</ion-item>
        <ion-item>Genoa</ion-item>
        <ion-item>Glasgow</ion-item>
        <ion-item>Hanoi</ion-item>
        <ion-item>Hong Kong</ion-item>
        <ion-item>Islamabad</ion-item>
        <ion-item>Istanbul</ion-item>
        <ion-item>Jakarta</ion-item>
        <ion-item>Kiel</ion-item>
        <ion-item>Kyoto</ion-item>
        <ion-item>Le Havre</ion-item>
        <ion-item>Lebanon</ion-item>
        <ion-item>Lhasa</ion-item>
        <ion-item>Lima</ion-item>
        <ion-item>London</ion-item>
        <ion-item>Los Angeles</ion-item>
        <ion-item>Madrid</ion-item>
        <ion-item>Manila</ion-item>
        <ion-item>New York</ion-item>
        <ion-item>Olympia</ion-item>
        <ion-item>Oslo</ion-item>
        <ion-item>Panama City</ion-item>
        <ion-item>Peking</ion-item>
        <ion-item>Philadelphia</ion-item>
        <ion-item>San Francisco</ion-item>
        <ion-item>Seoul</ion-item>
        <ion-item>Taipeh</ion-item>
        <ion-item>Tel Aviv</ion-item>
        <ion-item>Tokio</ion-item>
        <ion-item>Uelzen</ion-item>
        <ion-item>Washington</ion-item>
      </ion-list>
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent, IonSearchbar, IonList, IonItem } from '@ionic/vue';
// import ExploreContainer from '@/components/ExploreContainer.vue';

export default  defineComponent({
  name: 'Tab1Page',
  components: { IonHeader, IonToolbar, IonTitle, IonContent, IonPage, IonSearchbar, IonList, IonItem  },

});
</script>
