<template>

<div>
    <div class="photo">
        <br>
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
        <Tune></Tune>
    </div>
</div>
    
</template>

<script>
import Tune from '@/components/TuneChill.vue'
import BritC from '@/components/BritComponent.vue'
import Countdown from '@/components/countdown.vue'

export default {
  components: {
    Tune,
    BritC,
    Countdown
  }
}

</script>

<style lang="scss" scoped>
.photo{
    background: url("../assets/chillMusic.jpg");
    margin-top: -82px;
    margin-right: -8px;
    margin-left: -8px;
    background-size: cover;
    width: auto;
    height: 852px;
}
.bloc2{
    height: 500px;
}
h1{
    font-family: 'Open Sans', sans-serif;
    font-weight: 900;
    font-size: 160%;
}

</style>
