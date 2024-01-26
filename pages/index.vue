<template>
    <div class="page">
        <RandomCharacter/>
        <div class="char__content">
            <CharactersList/>
            <CharacterInfo/>
        </div>
    </div>
</template>

<script setup>
import RandomCharacter from '~/components/RandomCharacter/RandomCharacter.vue'
import CharactersList from '~/components/CharactersList/CharactersList.vue'
import CharacterInfo from '~/components/CharacterInfo/CharacterInfo.vue'
</script>
