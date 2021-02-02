<template>
    <ion-page>
        <ion-header>
            <ion-toolbar>
                <ion-title>All memories</ion-title>
            </ion-toolbar>
        </ion-header>
        <ion-content>
            <ion-list>
                <ion-item>item1</ion-item>
                <ion-item>item2</ion-item>
                <ion-item>item3</ion-item>
                <ion-item>item4</ion-item>
                <ion-item>item5</ion-item>
                <ion-item>item6</ion-item>
            </ion-list>
        </ion-content>
    </ion-page>

</template>

<script>
import { IonPage, IonHeader, IonTitle, IonToolbar, IonContent, IonList, IonItem } from '@ionic/vue';

export default{
    components: {
        IonPage,
        IonHeader,
        IonTitle,
        IonToolbar,
        IonContent,
        IonList,
        IonItem,
    }
}
</script>