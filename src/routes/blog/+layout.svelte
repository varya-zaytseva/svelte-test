<div class="container">
    <slot />
</div>

<style>
    .container {
        margin: 50px auto;
        max-width: 800px;
        padding: 0 20px;
    }

    .blogposts {
        display: grid;
        grid-template-columns: 1fr 1fr;
        grid-gap: 20px;
    }

    .post {
        border: 1px solid #ddd;
        padding: 10px;
        box-shadow: 0 0 10px #eee;
    }

    .link {
        color: rgb(10, 10, 139);
    }
</style>
