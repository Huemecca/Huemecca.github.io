<template>
  <ion-content id="home">

    <ion-grid>

      <ion-row>
        <ion-col>
          <ion-text>
            <h3 class="huemecca-emphasize-text">
              Under Construction
            </h3>
          </ion-text>
        </ion-col>
      </ion-row>

      <ion-row>
        <ion-col>
          <ion-text>
            <h1 class="huemecca-text huemecca-primary-text">
              HUEMECCA
            </h1>
          </ion-text>
        </ion-col>
      </ion-row>

      <ion-row>
        <ion-col>
          <ion-text>
            <h1 class="huemecca-text huemecca-primary-text">
              The Melanin Beauty HQ
            </h1>
          </ion-text>
        </ion-col>
      </ion-row>

      <ion-row>
        <ion-col>
          <ion-text>
            <h2 class="huemecca-text huemecca-secondary-text">
              We simplify the way you find, try and buy melanin beauty online
            </h2>
          </ion-text>
        </ion-col>
      </ion-row>

      <ion-row>
        <ion-col>
          <svg id="demo"  viewBox="0 0 200 100">
            <line class="dashed" x1="0" y1="50" x2="200" y2="50" />
          </svg>
        </ion-col>
      </ion-row>

      <ion-row size="md">
        <ion-col>
          <ion-text>
            <p class="huemecca-text">
              We are super excited to have you here.
              Huemecca is solving a huge problem that exists in the melanin beauty space.
              To learn the "who, what, and how" of Huemecca, check out our pitch deck.
              We would love to have you apart of the journey!
            </p>
          </ion-text>
        </ion-col>
      </ion-row>

      <ion-row>
        <ion-col>
          <ion-button shape="round">
            <a href="https://app.slidebean.com/p/1qg36t2ms7/Daria-Wright-Startup-Pitch-Deck">
              Click Here
            </a>
          </ion-button>
        </ion-col>
      </ion-row>

    </ion-grid>

  </ion-content>
</template>

<script>

import {
  IonContent,
  IonButton,
  IonText,
  IonGrid,
  IonRow,
  IonCol
 } from '@ionic/vue';

export default {
  name: 'Home',
  components: {
    IonContent,
    IonButton,
    IonText,
    IonGrid,
    IonRow,
    IonCol
   },
  props: {
    msg: String
  },
  async mounted(){
    // TweenMax.to(".mask01", 2, {x:100,ease:Power0.easeNone, repeat:-1, repeatDelay:1, yoyo:true});
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

ion-content{
    --background: url("../assets/img/Website Landing Page.png");
}

ion-grid{
    height: 100%;
}
ion-row{
    display: flex;
    align-items: center;
    justify-content: center;
}

ion-button{
  --background:white;
  --color:black;
}

.huemecca-text{
  color: #03989e;
  font-family:TTRegular !important;
}

.huemecca-primary-text{
  font-size: 75px;
}

.huemecca-secondary-text{
  font-size: 24px;
}

.huemecca-emphasize-text{
  font-family:TTBold !important;
  color: #03989e;
  font-size: 24px;
}

h3 {
  margin: 40px 0 0;
}

a {
  color: black;
}


.dashed{
  stroke: #03989e;
}


#demo{
  width:400px;
}

</style>
