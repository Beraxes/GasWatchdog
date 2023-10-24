<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Alertas</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
      </ion-header> 
      
      <div class="cajas">
  


  <ion-card color="danger">
    <ion-card-header>
      <ion-card-title>Alerta</ion-card-title>
      <ion-card-subtitle>Fuga</ion-card-subtitle>
    </ion-card-header>


    <ion-card-content> 2023-01-14 05:57:33 </ion-card-content>
  </ion-card>
</div>  
    </ion-content>
  </ion-page>
</template>

<script>
  import { IonCard, IonCardContent, IonCardHeader, IonCardSubtitle, IonCardTitle } from '@ionic/vue';
  import { defineComponent } from 'vue';

  export default defineComponent({
    components: { IonCard, IonCardContent, IonCardHeader, IonCardSubtitle, IonCardTitle },
  });
</script>

<style scoped>
  /* iOS places the subtitle above the title */
  .cajas{
  display: flex;
  flex-wrap: wrap;
  }
</style>
<script setup>
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';
import ExploreContainer from '@/components/ExploreContainer.vue';
</script>
