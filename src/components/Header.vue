<template>
    <div class="header">
        <div class="header-brand">
            <h1>Chadura Tech</h1>
        </div>
        <div class="header-titles">
            <div class="header-title">
                <p>Home</p>
            </div>
            <div class="header-title">
                <p>About</p>
            </div>
            <div class="header-title">
                <p>Services</p>
            </div>
            <div class="header-title">
                <p>Contact Us</p>
            </div>
        </div>
    </div>
</template>

<script>

export default {
    name: "Header",
}

</script>

<style scoped>

    .header{
        display: grid;
        grid-template-columns: 1fr 1fr;
        padding: 1rem 10rem;
     

    }

    .header-titles{
        display: grid;
        grid-template-columns: 1fr 1fr 1fr 1fr;
        text-align: center;
        align-items: center;
    }

</style>
