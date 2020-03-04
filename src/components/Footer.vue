<template>
    <footer class="footer">
        <div class="container">
            <div class="row">
                <div class="col-sm-6 col-lg-3">
                    <div class="footer-logo">
                        <a class="footer-logo__link" href="/">
                            <img class="footer-logo__img" src="img/logo_white.png" alt="logo"/></a>
                    </div>

                    <ul class="footer-socials">
                        <li class="footer-socials__item"><a class="footer-socials__link" href="javascript://"><i class="fa fa-facebook" aria-hidden="true"></i></a></li>
                        <li class="footer-socials__item"><a class="footer-socials__link" href="javascript://"><i class="fa fa-twitter" aria-hidden="true"></i></a></li>
                        <li class="footer-socials__item"><a class="footer-socials__link" href="javascript://"><i class="fa fa-google-plus" aria-hidden="true"></i></a></li>
                        <li class="footer-socials__item"><a class="footer-socials__link" href="javascript://"><i class="fa fa-instagram" aria-hidden="true"></i></a></li>
                    </ul>
                </div>

                <div class="col-sm-6 col-lg-3">
                    <h4 class="footer__title">Contacts</h4>
                    <div class="footer-contacts">
                        <p class="footer-contacts__address">
                            3423 Piedmont Road NE
                            <br />Atlanta, Georgia 30305
                        </p>

                        <p class="footer-contacts__phone">
                            Phone: <a href="tel:+31859644725">+31 85 964 47 25</a>
                        </p>

                        <p class="footer-contacts__mail">
                            Email: <a href="mailto:support@bchplease.org">support@bchplease.org</a>
                        </p>
                    </div>
                </div>

                <div class="col-sm-6 col-lg-3">
                    <h4 class="footer__title">Menu & Links</h4>
                    <nav>
                        <ul class="footer-menu">
                            <li class="footer-menu__item footer-menu__item--active"><a class="footer-menu__link" href="/">Home</a></li>
                            <li class="footer-menu__item"><a class="footer-menu__link" href="javascript://">Blog</a></li>
                            <li class="footer-menu__item"><a class="footer-menu__link" href="javascript://">About</a></li>
                            <li class="footer-menu__item"><a class="footer-menu__link" href="javascript://">Contacts</a></li>
                            <li class="footer-menu__item"><a class="footer-menu__link" href="javascript://">Pages</a></li>
                            <li class="footer-menu__item"><a class="footer-menu__link" href="javascript://">Elements</a></li>
                            <li class="footer-menu__item"><a class="footer-menu__link" href="https://causes.cash" target="blank">Causes</a></li>
                        </ul>
                    </nav>
                    <!-- footer nav end-->
                </div>

                <div class="col-sm-6 col-lg-3">
                    <h4 class="footer__title">Donate</h4>
                    <p>Help Us Change the Lives of Children in World</p><a class="button footer__button button--filled" href="javascript://">Donate</a>
                </div>
            </div>

            <div class="row align-items-baseline">
                <div class="col-md-6">
                    <p class="footer-copyright">&copy; {{curYear}} Bitcoin Cash Please</p>
                </div>

                <div class="col-md-6">
                    <div class="footer-privacy">
                        <a class="footer-privacy__link" href="javascript://">
                            Privacy Policy</a>

                        <span class="footer-privacy__divider">|</span>

                        <a class="footer-privacy__link" href="javascript://">
                            Terms &amp; Conditions</a>
                    </div>
                </div>
            </div>
        </div>
    </footer>
</template>

<script>
/* Import modules. */
import moment from 'moment'

export default {
    props: {
        // msg: String
    },
    data: () => {
        return {

        }
    },
    computed: {
        curYear: function () {
            /* Return current year. */
            return moment().format('YYYY')
        },
    }
}
</script>

<style scoped>
/*  */
</style>
