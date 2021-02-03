<template>
    <base-layout page-title="All memories">
        <ion-list>
            <ion-item>memo 1</ion-item>
            <ion-item>memo 2</ion-item>
            <ion-item>memo 3</ion-item>
            <ion-item>memo 4</ion-item>
            <ion-item>memo 5</ion-item>
            <ion-item>memo 6</ion-item>
        </ion-list>
    </base-layout>
</template>

<script>
import {  
    IonList, 
    IonItem 
} from '@ionic/vue';

export default{
    components: { 
        IonList,
        IonItem
    }
}

</script>