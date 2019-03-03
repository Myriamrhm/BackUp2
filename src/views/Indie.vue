<template>
    <div>
    <div id="picIndie">
      <br>
      <br>
      <br>
      <br>
      <br>
      <br>
    <h1>Qui est l'interprete de cette chanson ?</h1>
    <TuneIndie></TuneIndie>
    <Countdown></Countdown>
    <BritC></BritC>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    </div>
    </div>
</template>


<script>
import TuneIndie from '@/components/TuneIndie.vue'
import Countdown from '@/components/countdown.vue'
import BritC from '@/components/BritComponent.vue'


export default {
  components: {
    TuneIndie,
    Countdown, 
    BritC
  }
}
</script>

<style lang="scss" scoped>
#picIndie{
  background: url("../assets/escape.jpg");
    background-size: cover;
    height: 800px;
    margin-top: -82px;
    margin-right: -8px;
    margin-left: -8px;
}
h1{
color: white;
}
</style>
