<template>
    <div class="aside-dropdown">
        <div class="aside-dropdown__inner">
            <span class="aside-dropdown__close">
                <svg class="icon">
                    <use xlink:href="#close"></use>
                </svg>
            </span>

            <div class="aside-dropdown__item d-lg-none d-block">
                <ul class="aside-menu">
                    <li class="aside-menu__item aside-menu__item--active">
                        <a class="aside-menu__link" href="javascript://">
                            <span>Home</span></a>
                    </li>

                    <li class="aside-menu__item aside-menu__item--has-child">
                        <a class="aside-menu__link" href="javascript://">
                            <span>Pages</span></a>

                        <ul class="aside-menu__sub-list">
                            <li><a href="javascript://"><span>About</span></a></li>
                            <li><a href="javascript://"><span>Documentation</span></a></li>
                            <li><a href="javascript://"><span>Donors & Partners</span></a></li>
                            <li><a href="javascript://"><span>Become a Volunteer</span></a></li>
                            <li><a href="javascript://"><span>Events</span></a></li>
                            <li><a href="javascript://"><span>Stories</span></a></li>
                            <li><a href="javascript://"><span>Blog</span></a></li>
                            <li><a href="javascript://"><span>Photo Gallery</span></a></li>
                        </ul>
                    </li>

                    <li class="aside-menu__item">
                        <a class="aside-menu__link" href="javascript://">
                            <span>Contacts</span></a>
                    </li>
                </ul>
            </div>

            <div class="aside-dropdown__item">
                <ul class="aside-menu">
                    <li class="aside-menu__item"><a class="aside-menu__link" href="javascript://">Our Causes</a></li>
                    <li class="aside-menu__item"><a class="aside-menu__link" href="javascript://">Our Projects</a></li>
                    <li class="aside-menu__item"><a class="aside-menu__link" href="https://docs.bchplease.org" target="_blank">Documentation</a></li>
                </ul>

                <div class="aside-inner">
                    <span class="aside-inner__title">Email</span>
                    <a class="aside-inner__link" href="mailto:support@bchplease.org">support@bchplease.org</a>
                </div>

                <div class="aside-inner">
                    <span class="aside-inner__title">Phone numbers</span>
                    <a class="aside-inner__link" href="tel:+180012345678">+1 678 981-8818</a>
                </div>

                <ul class="aside-socials">
                    <li class="aside-socials__item"><a class="aside-socials__link" href="javascript://"><i class="fa fa-reddit" aria-hidden="true"></i></a></li>
                    <li class="aside-socials__item"><a class="aside-socials__link" href="javascript://"><i class="fa fa-twitter" aria-hidden="true"></i></a></li>
                    <li class="aside-socials__item"><a class="aside-socials__link" href="javascript://"><i class="fa fa-github" aria-hidden="true"></i></a></li>
                </ul>
            </div>

            <div class="aside-dropdown__item">
                <a class="button button--squared" href="https://causes.cash" target="_blank">
                    <span>Donate</span></a>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    props: {
        // msg: String
    }
}
</script>

<style scoped>
/*  */
</style>
