<template>
    <div id="assets" class="container">
        <h1>Assets</h1>
        <a href="/DungeonGenerator"><img class="img-thumbnail" src="../assets/cdg-resized.png" alt="Customizable Dungeon Generator"></a>
    </div>
</template>

<style scoped>
#assets {
    padding: 2.5rem;
}

.img-thumbnail {
    border-radius: 5%;
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