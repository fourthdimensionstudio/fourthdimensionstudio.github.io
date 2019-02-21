<template>
    <div id="contact" class="container">
        <h1>More</h1>
         <a href="http://twitter.com/frthdimension" target="_BLANK"> 
            <button class="btn btn-light"><font-awesome-icon :icon="['fab', 'twitter']"></font-awesome-icon> TWITTER</button>
        </a>
        <a href="mailto:contact@fourthdimesion.studio">
            <button class="btn btn-light"><font-awesome-icon icon="envelope"></font-awesome-icon> EMAIL</button>
        </a>
        <a href="https://fourthdimension.itch.io" target="_BLANK">
            <button class="btn btn-light"><font-awesome-icon icon="gamepad"></font-awesome-icon> itch.io</button>
        </a>
        <a href="/devlog">
            <button class="btn btn-light"><font-awesome-icon icon="book"></font-awesome-icon> DEVLOG</button>
        </a>
    </div>
</template>

<style scoped>
#contact {
    padding: 2.5rem;
}

button {
    margin: 1rem .5rem;
}
</style>