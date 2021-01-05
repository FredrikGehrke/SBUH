<template>
    <footer class="page-footer font-small black footer-color">
        <div class="footer-copyright text-center py-3 footer-style">
        Copyright {{ new Date().getFullYear() }} &copy;  Sollentuna Bygguthyrning
        </div>
    </footer>
</template>

<style scoped>

    .footer-style {
        font-size: 16px;
    }

    .footer-color {
        background: linear-gradient(to bottom, rgba(21, 26, 36, 0.966), rgb(28, 35, 49));
    }

</style>