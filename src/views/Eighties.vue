<template>
    <div class="eighties">
        <br>
        <br>
        <br>
        <br>
        <br>
        <h1>Qui est l'interprete de cette chanson ?</h1>
        <Countdown></Countdown>
        <BritC></BritC>
        <TuneEighties></TuneEighties>

    </div>
</template>

<script>
import TuneEighties from '@/components/TuneEightiesBand.vue'
import BritC from '@/components/BritComponent.vue'
import Countdown from '@/components/countdown.vue'

export default {
  components: {
    BritC,
    Countdown,
    TuneEighties
  }
}
</script>

<style lang="scss" scoped>
.eighties{
    background: url("../assets/Glastonbury.jpg");
    background-size: cover;
    height: 1000px;
    width: auto;
    margin-top: -82px;
    margin-right: -8px;
    margin-left: -8px;
}
h1{
    font-family: 'Open Sans', sans-serif;
    font-weight: 900;
    font-size: 160%;
}

</style>
