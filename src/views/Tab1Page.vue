<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Estado Del Sensor</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
      </ion-header> 
      
      <div class="estadoActual">
        
        <ion-chip color="success">Activo</ion-chip>
      </div>
      <div class="botonesEstado">

        <ion-button color="success">Activar</ion-button>
        <ion-button color="danger">Desactivar</ion-button>
      </div>
    </ion-content>


  </ion-page>
  
</template>


<script>
  import { IonItem, IonLabel, IonList, IonListHeader } from '@ionic/vue';
  import { defineComponent } from 'vue';

  export default defineComponent({
    components: { IonItem, IonLabel, IonList, IonListHeader, IonButton, IonChip },
  });
</script>
<script setup>
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent, IonButton, IonChip} from '@ionic/vue';

</script>
<style scoped>
.botonesEstado{
  text-align: center;
}
.estadoActual{
  margin-top: 20;
  text-align: center;
  margin-bottom: 20%;
}
ion-chip{
  margin-top: 20%;
  font-size: x-large;
}

</style>