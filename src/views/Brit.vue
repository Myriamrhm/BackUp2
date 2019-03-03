<template>
    <div class="picture">
        <br>
        <br>
        <br>
        <br>
        <br>
        <br>
        <br>
        <h1>Qui est l'interprete de cette chanson ?</h1>
        <Countdown></Countdown>
        <BritC></BritC>
        <TuneBrit></TuneBrit>

    </div>
</template>

<script>
import TuneBrit from '@/components/TuneBrit.vue'
import BritC from '@/components/BritComponent.vue'
import Countdown from '@/components/countdown.vue'

export default {
  components: {
    BritC,
    Countdown,
    TuneBrit
  }
}

</script>

<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css?family=Open+Sans:400,600,700,800');
.picture{
    background: url("../assets/FondBrit.jpg");
    background-size: cover;
    height: 842px;
    width: auto;
    margin-top: -105px;
    margin-right: -8px;
    margin-left: -8px;
}
h1{
    font-family: 'Open Sans', sans-serif;
    font-weight: 900;
    font-size: 160%;
    background-color: rgba(0, 0, 0, 0.308);
}
</style>
