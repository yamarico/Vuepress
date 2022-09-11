<template>
    <div>
        <button v-on:click="count++">クリックするとカウントが増えるよ</button>
        <p>カウンター：{{ count }}</p>
    </div>
</template>

<script>
export default {
    name: 'Counter',
    data: function () {
        return {
            count: 0
        }
    },
}
</script>