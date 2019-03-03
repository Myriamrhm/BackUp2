<template>
    
</template>

<script defer>
// Les chansons 6
var ShouldIstay = new Audio('http:\/\/cdn-preview-e.deezer.com\/stream\/c-ecc0ed464ac3e078b0b224710f77900a-3.mp3')
var BoysDontCry = new Audio('http:\/\/cdn-preview-5.deezer.com\/stream\/c-581eb398681af7833532a28e5e6302d7-5.mp3')
var FluorescenAdolescent = new Audio('http:\/\/cdn-preview-8.deezer.com\/stream\/c-80138b5b93f7980e5f2ecf8bead39602-4.mp3')
var CommonPeople = new Audio('http:\/\/cdn-preview-b.deezer.com\/stream\/c-b4be0d2a5bd4c0f3cfcf0de9328591b8-5.mp3')
var LondonCalling = new Audio('http:\/\/cdn-preview-1.deezer.com\/stream\/c-12ac03a0075c7c567e63a5fc9f7e8c66-6.mp3')
var FoughtLaw = new Audio('http:\/\/cdn-preview-b.deezer.com\/stream\/c-ba3d08d4e8fec342dd459119a85b6ca7-3.mp3')
// 

CommonPeople.play()
CommonPeople.addEventListener('ended', function(){
       ShouldIstay.play()
   })
ShouldIstay.addEventListener('ended', function(){
       FluorescenAdolescent.play()
   })
FluorescenAdolescent.addEventListener('ended', function(){
       BoysDontCry.play()
   })

</script>

<style>

</style>
