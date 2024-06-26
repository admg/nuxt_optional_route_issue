<template>
    <div>
        <NuxtLink to="/a">Link to A</NuxtLink> <br />
        <NuxtLink to="/a/id">Link to A + param</NuxtLink>
    </div>

    <div>
        <NuxtLink to="/b">Link to B</NuxtLink> <br />
        <NuxtLink to="/b/id">Link to B + param</NuxtLink>
    </div>

    <div>
        <NuxtPage />
    </div>
</template>

<style lang="css">
.router-link-active {
    background-color: yellow;
}
</style>