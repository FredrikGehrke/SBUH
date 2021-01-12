<template>
    <div>
        <div class="main-footer" id="kontakt">
            <footer class="page-footer font-small footer-bg pt-4">
                <div class="container-fluid text-center text-md-left container">
                    <div class="row">
                        <div class="col-md-5 mt-md-0 mt-3">
                            <h5 class="SBUH theme-color">Sollentuna Bygguthyrning</h5>
                            <p class="text-white">Har flera telefonnummer, ring, dra iväg ett mail eller skriv till mig på messenger!</p>
                        </div>
                        <hr class="clearfix w-100 d-md-none pb-3">
                        <div class="col-md-3 mb-md-0 mb-3">
                            <h5 class="heading theme-color">Telefonnummer</h5>
                            <ul class="list-unstyled">
                                <li>
                                    <a href="tel:0702200491">070-2200491</a>
                                </li>
                                <li>
                                    <a href="tel:0735745403">073-5745403</a>
                                </li>
                                <li>
                                    <a href="tel:0762577951">0762-577951</a>
                                </li>
                            </ul>
                        </div>
                        <div class="col-md-3 mb-md-0 mb-3">
                            <h5 class="heading theme-color">Email</h5>
                            <ul class="list-unstyled">
                                <li>
                                    <a href="mailto:leif@sbuh.se">leif@sbuh.se</a>
                                </li>
                                <li>
                                    <!-- <a href="#!">Link 2</a> -->
                                </li>
                                <li>
                                    <!-- <a href="#!">Link 3</a> -->
                                </li>
                            </ul>
                        </div>
                        <div class="col-md-1 mb-md-0 mb-3 d-none d-lg-block">
                            <button id="topBtn"><i v-on:click="scrollToTop()" class="fas fa-arrow-up totop fa-2x d-none d-lg-block"></i></button>
                        </div>
                    </div>
                </div>
                <div class="page-footer font-small black footer-color">
                    <div class="footer-copyright text-center py-3 footer-style">
                    Copyright {{ new Date().getFullYear() }} &copy;  Sollentuna Bygguthyrning
                    </div>
                </div>
            </footer>
        </div>

    </div>
</template>

<script>
export default {
    methods: {
        scrollToTop() {
            window.scrollTo(0, 0);
        },
    }
}
</script>

<style scoped>

    #topBtn {
        background: none;
        color: inherit;
        border: none;
        padding: 0;
        font: inherit;
        cursor: pointer;
        outline: inherit;

        background-color: var(--theme-color);
        padding: 6px;
        border-radius: 5px;
        cursor: pointer;
    }#topBtn:hover {
        background-color: white;
        color: var(--theme-color)
    }

    a {
        text-decoration: none;
        color: white;
    }

    .heading {
        font-weight: 800;
    }

    .SBUH {
        font-family: 'Roboto Slab', serif;
        font-weight: 700;
        font-size: 24px;
    }

    .footer-bg {
        background: linear-gradient(to bottom, rgb(22, 22, 22), rgb(19, 19, 19));
    }

    .footer-style {
        font-size: 16px;
    }

    .footer-color {
        background: linear-gradient(to bottom, rgb(26, 26, 26), rgb(19, 19, 19));
    }

</style>