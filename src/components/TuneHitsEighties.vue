<template>
    
</template>

<script defer>
//Les chansons DEVINE TITRE??? 16
var Africa = new Audio('http://cdn-preview-4.deezer.com//stream//c-4b888aec204edec33c4619ad4a5410b9-4.mp3')
var NeverGonnaGiveYouUp = new Audio('http:\/\/cdn-preview-6.deezer.com\/stream\/c-69c754e51ce012c96cbb4eb39841fec7-6.mp3')
var FunkyTown = new Audio('http:\/\/cdn-preview-b.deezer.com\/stream\/c-b27a69b6c30d1ea11cd21c96f3c8833f-3.mp3')
var TaintedLove = new Audio('http:\/\/cdn-preview-e.deezer.com\/stream\/c-ecca2746ba3e5bfbccc1d6433d51abba-4.mp3')
var Maniac = new Audio('http:\/\/cdn-preview-1.deezer.com\/stream\/c-1bfdbd32d5aa1ee679b05e1f9ccc4a0b-5.mp3')
var NeedYouTonight = new Audio('http:\/\/cdn-preview-b.deezer.com\/stream\/c-bad3798e0702a52649373233b5b600d5-5.mp3')
var WhatsUp = new Audio('http:\/\/cdn-preview-2.deezer.com\/stream\/c-2d13de786b154b10be49cb7827af47ac-7.mp3')
var Bohemian = new Audio('http:\/\/cdn-preview-1.deezer.com\/stream\/c-17597947a0fdd6e8ea971f146755cd34-11.mp3')
var DontStopMeNow = new Audio('http:\/\/cdn-preview-5.deezer.com\/stream\/c-5a9b2da5acb610170196eb5872c7d2ab-15.mp3')
var YourSong = new Audio('http:\/\/cdn-preview-a.deezer.com\/stream\/c-ae8f9b10e8924ad25b2ceed76c3e48e8-5.mp3')
var NewOrder = new Audio('http:\/\/cdn-preview-7.deezer.com\/stream\/c-77ccd542c217cc66acdc0cd550cf4612-4.mp3')
var OneStepBeyond = new Audio('http:\/\/cdn-preview-7.deezer.com\/stream\/c-7e9af4777ca1b9f90e540c5f70b7565d-5.mp3')
var Silence = new Audio('http:\/\/cdn-preview-f.deezer.com\/stream\/c-f9ca315f3bf66995386dffe05b7b0cb8-2.mp3')
var Respect = new Audio('http:\/\/cdn-preview-0.deezer.com\/stream\/c-09922a19e087310a13616e955fb80552-4.mp3')
var JailhouseRock = new Audio('http:\/\/cdn-preview-8.deezer.com\/stream\/c-8e0eab947e665fddbb092d5964b28df9-1.mp3')
var BlueSuedeShoes = new Audio('http://cdn-preview-6.deezer.com//stream//c-6e37d64ba415d308f59221ff5590f9af-2.mp3')

//

NewOrder.play()
NewOrder.addEventListener('ended', function(){
       Silence.play()
   })
Silence.addEventListener('ended', function(){
        FunkyTown.play()
   })
FunkyTown.addEventListener('ended', function(){
        Maniac.play()
   })
Maniac.addEventListener('ended', function(){
        YourSong.play()
   })
YourSong.addEventListener('ended', function(){
        Bohemian.play()
   })
Bohemian.addEventListener('ended', function(){
        Africa.play()
   })
Africa.addEventListener('ended', function(){
        TaintedLove.play()
   })
TaintedLove.addEventListener('ended', function(){
        OneStepBeyond.play()
   })
OneStepBeyond.addEventListener('ended', function(){
        DontStopMeNow.play()
   })
DontStopMeNow.addEventListener('ended', function(){
        WhatsUp.play()
   })
WhatsUp.addEventListener('ended', function(){
        NeedYouTonight.play()
   })
NeedYouTonight.addEventListener('ended', function(){
        NeverGonnaGiveYouUp.play()
   })
NeverGonnaGiveYouUp.addEventListener('ended', function(){
        Respect.play()
   })
Respect.addEventListener('ended', function(){
        JailhouseRock.play()
   })
JailhouseRock.addEventListener('ended', function(){
       BlueSuedeShoes.play()
   })

</script>

<style>

</style>
