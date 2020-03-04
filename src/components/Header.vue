<template>
    <header class="header header--front">
        <div class="container-fluid">
            <div class="row no-gutters justify-content-between">
                <div class="col-auto d-flex align-items-center">
                    <div class="dropdown-trigger d-none d-sm-block">
                        <div class="dropdown-trigger__item"></div>
                    </div>

                    <div class="header-logo">
                        <a class="header-logo__link" href="index.html">
                            <img class="header-logo__img logo--light" src="img/logo_white.png" alt="logo"/>
                            <img class="header-logo__img logo--dark" src="img/logo_dark.png" alt="logo"/></a>
                        </div>
                </div>

                <div class="col-auto">
                    <!-- main menu start-->
                    <nav>
                        <ul class="main-menu">
                            <li class="main-menu__item main-menu__item--active">
                                <a class="main-menu__link" href="javascript://">
                                    <span>Home</span></a>
                            </li>

                            <li class="main-menu__item main-menu__item--has-child">
                                <a class="main-menu__link" href="javascript://">
                                    <span>Pages</span></a>

                                <ul class="main-menu__sub-list sub-list--style-2">
                                    <li><a href="javascript://"><span>About</span></a></li>
                                    <li><a href="javascript://"><span>Donors & Partners</span></a></li>
                                    <li><a href="javascript://"><span>Become a Volunteer</span></a></li>
                                    <li><a href="javascript://"><span>Team Member</span></a></li>
                                    <li><a href="javascript://"><span>Events</span></a></li>
                                    <li><a href="javascript://"><span>Stories</span></a></li>
                                    <li><a href="javascript://"><span>Blog</span></a></li>
                                    <li><a href="javascript://"><span>Gallery</span></a></li>
                                    <li><a href="javascript://"><span>Pricing Plans</span></a></li>
                                    <li><a href="javascript://"><span>FAQ</span></a></li>
                                </ul>
                            </li>

                            <li class="main-menu__item">
                                <a class="main-menu__link" href="javascript://">
                                    <span>Contacts</span></a>
                            </li>
                        </ul>
                    </nav>
                </div>

                <div class="col-auto d-flex align-items-center">
                    <ul class="lang-select">
                        <li class="lang-select__item lang-select__item--active">
                            <span>En</span>

                            <ul class="lang-select__sub-list">
                                <li><a href="javascript://">French</a></li>
                                <li><a href="javascript://">Spanish</a></li>
                                <li><a href="javascript://">Deutsch</a></li>
                                <li><a href="javascript://">Russian</a></li>
                            </ul>
                        </li>
                    </ul>

                    <div class="dropdown-trigger d-block d-sm-none">
                        <div class="dropdown-trigger__item"></div>
                    </div>

                    <a class="button button--squared" href="javascript://">
                        <span>Donate</span></a>
                </div>
            </div>
        </div>
    </header>
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
