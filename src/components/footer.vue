<template>
    <div>
        <div class="main-footer">
            <!-- Footer -->
            <footer class="page-footer font-small footer-bg pt-4">

            <!-- Footer Links -->
            <div class="container-fluid text-center text-md-left container">

                <!-- Grid row -->
                <div class="row">

                <!-- Grid column -->
                <div class="col-md-6 mt-md-0 mt-3">

                    <!-- Content -->
                    <h5 class="SBUH">Sollentuna Bygguthyrning</h5>
                    <p>Har flera telefonnummer, ring, dra iväg ett mail eller skriv till mig på messenger!</p>

                </div>
                <!-- Grid column -->

                <hr class="clearfix w-100 d-md-none pb-3">

                <!-- Grid column -->
                <div class="col-md-3 mb-md-0 mb-3">

                    <!-- Links -->

                    <h5 class="heading theme-color">Telefonnummer</h5>

                    <ul class="list-unstyled">
                        <li>
                            <a href="#!">070-2200491</a>
                        </li>
                        <li>
                            <a href="#!">073-5745403</a>
                        </li>
                        <li>
                            <a href="#!">0762-577951</a>
                        </li>
                    </ul>

                </div>
                <!-- Grid column -->

                <!-- Grid column -->
                <div class="col-md-3 mb-md-0 mb-3">

                    <!-- Links -->
                    <h5 class="heading theme-color">Email</h5>

                    <ul class="list-unstyled">
                        <li>
                            <a href="mailto:leif@sbuh.se">leif@sbuh.se</a>
                        </li>
                        <li>
                            <a href="#!">Link 2</a>
                        </li>
                        <li>
                            <a href="#!">Link 3</a>
                        </li>
                    </ul>

                </div>
                <!-- Grid column -->

                </div>
                <!-- Grid row -->

            </div>
            <!-- Footer Links -->

            <!-- Copyright -->
            <div class="page-footer font-small black footer-color">
                <div class="footer-copyright text-center py-3 footer-style">
                Copyright {{ new Date().getFullYear() }} &copy;  Sollentuna Bygguthyrning
                </div>
            </div>
            <!-- Copyright -->

            </footer>
        </div>

    </div>
</template>

<style scoped>

    .heading {
        font-weight: 800;
    }

    .SBUH {
        font-family: 'Roboto Slab', serif;
        font-weight: 700;
        font-size: 24px;
    }

    .footer-bg {
        background: linear-gradient(to bottom, rgba(21, 26, 36, 0.966), rgb(21, 28, 43));
    }

    .footer-style {
        font-size: 16px;
    }

    .footer-color {
        background: linear-gradient(to bottom, rgba(16, 19, 26, 0.966), rgb(20, 25, 36));
    }

</style>