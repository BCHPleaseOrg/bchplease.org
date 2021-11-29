<template>
    <section class="section causes">
        <img class="causes__bg" src="@/assets/images/causes_img.png" alt="img"/>

        <div class="container">
            <div class="row align-items-end">
                <div class="col-xl-5">
                    <div class="heading heading--primary">
                        <span class="heading__pre-title">How We Support Communities</span>

                        <h2 class="heading__title">
                            <span>BCH Please</span> <span>Causes</span>
                        </h2>

                        <p>
                            Our community of volunteers work tirelessly to bring awareness and support to dozens of causes across the world.
                            We're proud to be making a difference in people's lives each and every day.
                        </p>
                    </div>
                </div>

                <div class="col-xl-6 offset-xl-1 d-none d-xl-block">
                    <div class="row offset-margin">
                        <div class="col-6">
                            <div class="counter-item counter-item--style-3">
                                <div class="counter-item__top">
                                    <h6 class="counter-item__title"># of People Impacted</h6>
                                </div>

                                <div class="counter-item__lower">
                                    ~<span class="js-counter">0.1</span>
                                    <span>k</span>
                                </div>
                            </div>
                        </div>

                        <div class="col-6">
                            <div class="counter-item counter-item--style-3">
                                <div class="counter-item__top">
                                    <h6 class="counter-item__title">Dollars Collected</h6>
                                </div>

                                <div class="counter-item__lower">
                                    ~<span class="js-counter">1</span>
                                    <span>k</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="row align-items-end margin-bottom">
                <div class="col-sm-6">
                    <a class="button button--primary" href="javascript://">View ALL Causes</a>
                </div>

                <div class="col-sm-6 d-flex justify-content-sm-end">
                    <div class="slider__nav causes-slider__nav">
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
            </div>
        </div>

        <div class="causes-holder offset-margin">
            <div class="causes-holder__wrapper">
                <div class="causes-slider offset-margin">

                    <!-- Causes -->
                    <div class="causes-slider__item" v-for="cause of causes" :key="cause.id">
                        <div class="causes-item causes-item--primary">
                            <div class="causes-item__body">
                                <div class="causes-item__top">
                                    <h6 class="causes-item__title">
                                        <a href="javascript://">{{cause.title}}</a>
                                    </h6>

                                    <p>
                                        {{cause.description}}
                                    </p>
                                </div>

                                <div class="causes-item__img">
                                    <div class="causes-item__badge" style="background-color: #49C2DF">
                                        {{cause.topic}}
                                    </div>

                                    <img class="img--bg" :src="cause.imgUrl" alt="img"/>
                                </div>

                                <div class="causes-item__lower">
                                    <div class="progress-bar">
                                        <div class="progress-bar__inner" :style="{ width: cause.pctComplete }">
                                            <div class="progress-bar__value">{{cause.pctComplete}}</div>
                                        </div>
                                    </div>

                                    <div class="causes-item__details-holder">
                                        <div class="causes-item__details-item">
                                            <span>Goal: </span>
                                            <span>{{cause.goal}}</span>
                                        </div>
                                        <div class="causes-item__details-item text-right">
                                            <span>Pledged: </span><span>{{cause.pledged}}</span>
                                        </div>
                                    </div>
                                </div>
                            </div>

                            <a class="button causes-item__button button--primary" href="javascript://">
                                + Donate Now</a>
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
            causes: []
        }
    },
    created: function () {

        this.causes.push({
            id: 'water-delivery-in-africa',
            title: 'Water Delivery in Africa',
            description: 'Sharksucker sea toad candiru rocket danio tilefish stingray deepwater stingray Sacramento splittail',
            topic: 'Water Delivery',
            imgUrl: 'https://i.imgur.com/Vd3CJlT.jpg',
            goal: '25 000$',
            pledged: '20 350$',
            pctComplete: '78%',
        })

        this.causes.push({
            id: 'health-in-other-countries',
            title: 'Health in other Countries',
            description: 'Sharksucker sea toad candiru rocket danio tilefish stingray deepwater stingray Sacramento splittail',
            topic: 'Medicine',
            imgUrl: 'https://i.imgur.com/IF7LQW8.jpg',
            goal: '14 000$',
            pledged: '6 098$',
            pctComplete: '23%',
        })

        this.causes.push({
            id: 'we-build-and-create',
            title: 'We Build and Create',
            description: 'Sharksucker sea toad candiru rocket danio tilefish stingray deepwater stingray Sacramento splittail',
            topic: 'Education',
            imgUrl: 'https://i.imgur.com/I0ahWDL.jpg',
            goal: '150 000$',
            pledged: '76 500$',
            pctComplete: '51%',
        })

        this.causes.push({
            id: 'healthy-food',
            title: 'Healthy Food',
            description: 'Sharksucker sea toad candiru rocket danio tilefish stingray deepwater stingray Sacramento splittail',
            topic: 'Food',
            imgUrl: 'https://i.imgur.com/TjJyF5w.jpg',
            goal: '50 000$',
            pledged: '25 000$',
            pctComplete: '50%',
        })

    },
}
</script>

<style scoped>
/*  */
</style>
