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
import AboutUs from '@/components/AboutUs.vue'
import Articles from '@/components/Articles.vue'
import Causes from '@/components/Causes.vue'
import Events from '@/components/Events.vue'
import Footer from '@/components/Footer.vue'
import Gallery from '@/components/Gallery.vue'
import Header from '@/components/Header.vue'
import Message from '@/components/Message.vue'
import Projects from '@/components/Projects.vue'
import Promo from '@/components/Promo.vue'
import Services from '@/components/Services.vue'
import Sidebar from '@/components/Sidebar.vue'
import Sponsors from '@/components/Sponsors.vue'
import Subscribe from '@/components/Subscribe.vue'
import Testimonials from '@/components/Testimonials.vue'

export default {
    components: {
        AboutUs,
        Articles,
        Causes,
        Events,
        Footer,
        Gallery,
        Header,
        Message,
        Projects,
        Promo,
        Services,
        Sidebar,
        Sponsors,
        Subscribe,
        Testimonials,
    }
}
</script>
