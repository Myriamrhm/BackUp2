<template>
<div>
    <div id="contenu1">
        <section>
        <p>Brit Rock</p>
        <router-link to="/brit"><img class="img" src="../assets/CatBrit.jpg" alt=""></router-link>
        </section>
        <section>
        <p>New Indie/Rock</p>
        <router-link to="/indie"><img class="img" src="../assets/Categorie2.jpg" alt=""></router-link>
        </section>
        <section>
        <p>Dance</p>
        <router-link to="/funk"><img class="img" src="../assets/Funk.jpg" alt=""></router-link>
        </section>
        <section>
        <p>Hits</p>
        <router-link to="/eightiesHits"><img class="img" src="../assets/HitsCat.jpg"></router-link>
        </section>
        <section>
        <p>Chill</p>
        <router-link to="/partie"><img class="img" src="../assets/ChillCat.jpg" alt=""></router-link>
        </section>
        <section>
        <p>Band Eighties</p>
        <router-link to="/eighties"><img class="img" src="../assets/Eighties.jpg"></router-link>
        </section>
        <section>
        <p>Eighties Rock</p>
        <router-link to="/eightiesRock"><img class="img" src="../assets/RockEighties.jpg"></router-link>
        </section>
        <section>
        <p>Teen 2010 Rock</p>
        <div class="bloc"></div>
        </section>
        <section>
        <p>Teen 2010 RNB</p>
        <div class="bloc"></div>
        </section>
    </div>
    <br>
    <hr>
    <div id="contenu2">
        <section>
        <p>Tendance French</p>
        <img class="img" src="../assets/Tendance.jpg">
        </section>
        <section>
        <p>2000-2010 French</p>
        <img class="img" src="../assets/2010.jpg">
        </section>
        <section>
        <p>Eighties French</p>
        <div class="bloc"></div>
        </section>
        <section>
        <p>Sixties French</p>
        <div class="bloc"></div>
        </section>
    </div>
</div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
#contenu1, #contenu2{
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
    margin-left: 100px;
    margin-right: 100px;
}
p{
    // margin-top: 120px;
    font-size: 140%;
    font-family: 'Open Sans', sans-serif;
    font-weight: 700;
    background-color: rgba(0, 0, 0, 0.342);
    border-radius: 3px;
    margin-top: 25%;
}
.img{
    width: 220px;
    height: 220px;
    box-shadow: 10px 12px rgba(0, 0, 0, 0.404);
}
.img:hover{
    transform: scale(1.01);
    outline-style: solid;
    outline-color: rgb(187, 187, 187);
    outline-offset: 15px;
}
.bloc{
    width: 220px;
    height: 220px;
    background-color: darkcyan;
}
hr{
    height: 2px;
    width: 88%;
    background-color: white;
}

</style>
