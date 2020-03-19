<template>
    <div class="page-wrapper">
        <Sidebar />
        <Header />

        <main class="main">
            <Promo />
            <AboutUs />
            <Services />
            <Causes />
            <Projects />
            <Events />
            <Message />
            <Testimonials />
            <Articles />
            <Sponsors />
            <Gallery />
            <Subscribe />
        </main>

        <Footer />
    </div>
</template>

<script>
/* Import components. */
import Footer from '@/components/Footer.vue'
import Header from '@/components/Header.vue'
import Sidebar from '@/components/Sidebar.vue'

import AboutUs from '@/components/welcome/AboutUs.vue'
import Articles from '@/components/welcome/Articles.vue'
import Causes from '@/components/welcome/Causes.vue'
import Events from '@/components/welcome/Events.vue'
import Gallery from '@/components/welcome/Gallery.vue'
import Message from '@/components/welcome/Message.vue'
import Projects from '@/components/welcome/Projects.vue'
import Promo from '@/components/welcome/Promo.vue'
import Services from '@/components/welcome/Services.vue'
import Sponsors from '@/components/welcome/Sponsors.vue'
import Subscribe from '@/components/welcome/Subscribe.vue'
import Testimonials from '@/components/welcome/Testimonials.vue'

export default {
    components: {
        Footer,
        Header,
        Sidebar,

        AboutUs,
        Articles,
        Causes,
        Events,
        Gallery,
        Message,
        Projects,
        Promo,
        Services,
        Sponsors,
        Subscribe,
        Testimonials,
    }
}
</script>
