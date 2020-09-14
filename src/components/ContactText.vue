<template>
    <div id="contact-page">
        <h1>{{ msg }}</h1>
        <p>For reservations, nutrition questions, or requesting where the bodies are, please call 669-987-1047</p>
    </div>
</template>

<script>
export default {
    name: "ContactText",
    props: {
        msg: String
    }    
}
</script>

<style scoped>

</style>