<template>
    <footer class="footer">
        <div class="container">
            <div class="row">
                <div class="col-sm-6 col-lg-3">
                    <div class="footer-logo">
                        <a class="footer-logo__link" href="/">
                            <img class="footer-logo__img" src="@/assets/images/logo_white.png" alt="logo"/></a>
                    </div>

                    <ul class="footer-socials">
                        <li class="footer-socials__item">
                            <a class="footer-socials__link" href="javascript://">
                                <i class="fa fa-reddit" aria-hidden="true"></i></a>
                        </li>

                        <li class="footer-socials__item">
                            <a class="footer-socials__link" href="javascript://">
                                <i class="fa fa-twitter" aria-hidden="true"></i></a>
                        </li>

                        <li class="footer-socials__item">
                            <a class="footer-socials__link" href="javascript://">
                                <i class="fa fa-gitlab" aria-hidden="true"></i></a>
                        </li>

                        <li class="footer-socials__item">
                            <a class="footer-socials__link" href="https://join.slack.com/t/bchplease/shared_invite/zt-e7jj03j5-vJbe47kNrPBjTgTXwLNRkA" target="_blank">
                                <i class="fa fa-slack" aria-hidden="true"></i></a>
                        </li>
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
                            Phone: <a href="javascript://">+1 678 981-8818</a>
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
                </div>

                <div class="col-sm-6 col-lg-3">
                    <h4 class="footer__title">Join Us</h4>

                    <p>
                        Help Us Give the <strong class="text-white">Freedom to Wealth???</strong> to Millions All Over World
                    </p>

                    <a class="button footer__button button--filled" href="https://join.slack.com/t/bchplease/shared_invite/zt-e7jj03j5-vJbe47kNrPBjTgTXwLNRkA" target="_blank">Join Our Slack</a>
                </div>
            </div>

            <div class="row align-items-baseline">
                <div class="col-md-6">
                    <p class="footer-copyright">
                        &copy; {{curYear}} Bitcoin Please.
                        All rights reserved.
                    </p>

                    <small>
                        <a href="https://explorer.bitcoin.com/bch/address/bitcoincash:qqvl7fwcthhhntsew056t8007pw55k258vmlm053fy" target="_blank" style="text-decoration:none">
                            Send <strong class="text-success">BCH</strong> <i class="fa fa-heart text-danger" aria-hidden="true"></i> ??? bitcoincash:qqvl7fwcthhhntsew056t8007pw55k258vmlm053fy</a>
                    </small>

                    <br />

                    <small>
                        <a href="https://www.smartscan.cash/address/0x891813423D812A4618fA7892404C2C2Aa6F727fC" target="_blank" style="text-decoration:none">
                            Send <strong style="color:#74dd54">SBCH</strong> <i class="fa fa-heart text-danger" aria-hidden="true"></i> ??? 0x891813423D812A4618fA7892404C2C2Aa6F727fC</a>
                    </small>

                    <br />

                    <small>
                        <a href="https://explorer.bitcoin.com/bch/address/simpleledger:qqxtz0fw3gs5ndmwjm2we92k20zu3z99uuuxr25a2s" target="_blank" style="text-decoration:none">
                            Send <strong class="text-info">SLP</strong> <i class="fa fa-heart text-danger" aria-hidden="true"></i> ??? simpleledger:qqxtz0fw3gs5ndmwjm2we92k20zu3z99uuuxr25a2s</a>
                    </small>
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
