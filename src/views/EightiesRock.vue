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
        <TuneEightiesRock></TuneEightiesRock>

    </div>
</template>

<script>

import TuneEightiesRock from '@/components/TuneEightiesRock.vue'
import BritC from '@/components/BritComponent.vue'
import Countdown from '@/components/countdown.vue'

export default {
  components: {
    BritC,
    Countdown,
    TuneEightiesRock
  }
}
</script>

<style lang="scss" scoped>
.eighties{
    background: url("../assets/Concert.jpg");
    background-size: cover;
    height: 1200px;
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