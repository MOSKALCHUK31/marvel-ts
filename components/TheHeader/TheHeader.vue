<template>
    <header class="app__header">
        <h1 class="app__title">
            <NuxtLink to="/">
                <span>Marvel</span>
                information portal
            </NuxtLink>
        </h1>
        <nav class="app__menu">
            <ul>
                <li>
                    <NuxtLink to="/">Characters</NuxtLink>
                </li>
                /
                <li>
                    <NuxtLink to="/comics">Comics</NuxtLink>
                </li>
            </ul>
        </nav>
    </header>
</template>
