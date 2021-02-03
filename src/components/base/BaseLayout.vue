<template>
    <ion-page>
        <ion-header>
            <ion-toolbar>
                <ion-title>{{ pageTitle }}s</ion-title>
            </ion-toolbar>
        </ion-header>
        <ion-content>
            <slot />
        </ion-content>
    </ion-page>

</template>

<script>
import { 
    IonPage, 
    IonHeader, 
    IonTitle, 
    IonToolbar, 
    IonContent
} from '@ionic/vue';

export default {
    props: ['pageTitle'],
    components: {
        IonPage,
        IonHeader,
        IonTitle,
        IonToolbar,
        IonContent
    }
}
</script>