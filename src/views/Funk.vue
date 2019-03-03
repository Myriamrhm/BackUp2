<template>
    <div class="funk">
        <br>
        <br>
        <br>
        <br>
        <br>
        <br>
        <h1>Qui est l'interprete de cette chanson ?</h1>
        <Countdown></Countdown>
        <BritC></BritC>
        <Dance></Dance>

    </div>
</template>

<script>
import BritC from '@/components/BritComponent.vue'
import Countdown from '@/components/countdown.vue'
import Dance from '@/components/TuneDance.vue'

export default {
  components: {
    BritC,
    Countdown,
    Dance
  }
}
</script>

<style lang="scss" scoped>
.funk{
    background: url("../assets/FondFunk2.jpg");
    background-size: cover;
    height: 800px;
    margin-top: -82px;
    margin-right: -8px;
    margin-left: -8px;
}
h1{
    font-family: 'Open Sans', sans-serif;
    font-weight: 900;
    font-size: 180%;
}
</style>
