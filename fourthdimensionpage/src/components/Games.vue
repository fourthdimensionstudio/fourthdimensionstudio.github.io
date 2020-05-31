<template>
    <div id="games" class="container">
        <h1>Games</h1>
        <a href="https://fourthdimension.itch.io/defensees"><img class="img-thumbnail" src="../assets/protectroguelike.png" alt="Defensees"></a>
        <a href="/pizzaclicker"><img class="img-thumbnail" src="../assets/pizzaclicker.png" alt="Pizza Clicker"></a>
        <a href="/spacejourney"><img class="img-thumbnail" src="../assets/spacejourney.png" alt="Space Journey"></a>
    </div>
</template>

<style scoped>
#games {
    padding: 5rem;
}

.img-thumbnail {
    border-radius: 10%;
    box-shadow: 0;
    opacity: 1;
    transition: all .2s;
    margin: 1rem .25rem;
}

.img-thumbnail:hover {
    box-shadow: 0 0px 4px 0 rgba(0,0,0,0.18),0 0px 12px 0 rgba(0,0,0,0.15);
    opacity: .5;
}
</style>