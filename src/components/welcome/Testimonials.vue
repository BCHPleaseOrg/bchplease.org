<template>
    <section class="section testimonials--style-2">
        <div class="testimonials--style-2__bg jarallax">
            <picture>
                <source srcset="@/assets/images/testimonials_2.jpg" media="(min-width: 992px)"/>
                <img class="jarallax-img" src="@/assets/images/testimonials_2.jpg" alt="img"/>
            </picture>
        </div>

        <div class="container">
            <div class="row">
                <div class="col-xl-4">
                    <div class="heading heading--primary">
                        <span class="heading__pre-title">Testimonials</span>

                        <h2 class="heading__title">
                            <span>What People Are</span><br/><span>Saying About Us</span>
                        </h2>
                    </div>

                    <div class="slider__nav testimonials-style-2__nav">
                        <div class="slider__arrows">
                            <div class="slider__prev">
                                <i class="fa fa-chevron-left" aria-hidden="true"></i>
                            </div>

                            <div class="slider__next">
                                <i class="fa fa-chevron-right" aria-hidden="true"></i>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="col-xl-8">
                    <div class="testimonials-slider testimonials-slider--style-2">

                        <div class="testimonials-slider__item" v-for="testimony of testimonials" :key="testimony.id">
                            <div class="testimonials-slider__icon">“</div>

                            <div class="testimonials-slider__text">
                                <p>
                                    {{testimony.body}}
                                </p>

                                <div class="testimonials-slider__author">
                                    <span class="testimonials-slider__name">{{testimony.author}}, </span>
                                    <span class="testimonials-slider__position">{{testimony.authorPos}}</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>
</template>

<script>
export default {
    props: {
        // msg: String
    },
    data: () => {
        return {
            testimonials: [],
        }
    },
    created: function () {

        this.testimonials.push({
            id: '1',
            body: `Slickhead grunion lake trout.
            Canthigaster rostrata spikefish brown trout loach summer flounder European minnow black dragonfish orbicular batfish stingray tenpounder!
            Flying characin herring, Moses sole sea snail grouper discus.
            European eel slender snipe eel.
            Gulper eel dealfish ocean sunfish; rohu yellow-and-black triplefin Atlantic saury swordfish southern sandfish Rudderfish long-finned pikerazorfish menhaden paradise fish, barramundi oceanic flyingfish.
            Fangtooth yellowtail banded killifish seamoth triplefin blenny desert pupfish crocodile shark catfish cutlassfish broadband dogfish whalefish.`,
            author: 'Jack Wolfskin',
            authorPos: 'Volunteer',
        })

        this.testimonials.push({
            id: '2',
            body: `Slickhead grunion lake trout. Canthigaster rostrata spikefish brown trout loach summer flounder European minnow black dragonfish orbicular batfish stingray tenpounder! Flying characin herring, Moses sole sea snail grouper discus. European eel slender snipe eel. Gulper eel dealfish ocean sunfish; rohu yellow-and-black triplefin Atlantic saury swordfish southern sandfish Rudderfish long-finned pikerazorfish menhaden paradise fish, barramundi oceanic flyingfish. Fangtooth yellowtail banded killifish seamoth triplefin blenny desert pupfish crocodile shark catfish cutlassfish broadband dogfish whalefish.`,
            author: 'Jack Wolfskin',
            authorPos: 'Volunteer',
        })

        this.testimonials.push({
            id: '3',
            body: `Slickhead grunion lake trout. Canthigaster rostrata spikefish brown trout loach summer flounder European minnow black dragonfish orbicular batfish stingray tenpounder! Flying characin herring, Moses sole sea snail grouper discus. European eel slender snipe eel. Gulper eel dealfish ocean sunfish; rohu yellow-and-black triplefin Atlantic saury swordfish southern sandfish Rudderfish long-finned pikerazorfish menhaden paradise fish, barramundi oceanic flyingfish. Fangtooth yellowtail banded killifish seamoth triplefin blenny desert pupfish crocodile shark catfish cutlassfish broadband dogfish whalefish.`,
            author: 'Jack Wolfskin',
            authorPos: 'Volunteer',
        })

    },
}
</script>

<style scoped>
/*  */
</style>
