<template>
    <section class="section projects no-padding-top no-padding-bottom">
        <div class="container">
            <div class="row align-items-end margin-bottom">
                <div class="col-lg-9">
                    <div class="heading heading--primary">
                        <span class="heading__pre-title">What We're Building</span>

                        <h2 class="heading__title"><span>BCH Please</span> <span>Projects</span></h2>

                        <p class="no-margin-bottom">
                            Our community is hard at work building products and services that will help benefit our global society.
                        </p>
                    </div>
                </div>
            </div>
        </div>

        <div class="row no-gutters projects-masonry">

            <!-- Project #1 -->
            <div class="col-lg-6 col-xl-4 projects-masonry__item projects-masonry__item--height-1 projects-masonry__item--vertical">
                <div class="projects-masonry__img">
                    <img class="img--bg" :src="projects[0].imgUrl" alt="img"/>
                </div>

                <div class="projects-masonry__text" style="background-color: #2EC774;">
                    <div class="projects-masonry__inner">
                        <span class="projects-masonry__badge" style="background: #49C2DF;">
                            {{projects[0].topic}}
                        </span>

                        <h3 class="projects-masonry__title">
                            <a href="javascript://">{{projects[0].title}}</a>
                        </h3>

                        <p>
                            {{projects[0].description}}
                        </p>

                        <div class="projects-masonry__details-holder">
                            <div class="projects-masonry__details-item">
                                <span>Goal: </span>
                                <span>{{projects[0].goal}}</span>
                            </div>

                            <div class="projects-masonry__details-item">
                                <span>Date: </span>
                                <span>{{projects[0].date}}</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Project #2 -->
            <div class="col-lg-6 col-xl-8 projects-masonry__item projects-masonry__item--height-2 projects-masonry__item--horizontal">
                <div class="projects-masonry__img">
                    <img class="img--bg" :src="projects[1].imgUrl" alt="img"/>
                </div>

                <div class="projects-masonry__text" style="background-color: #9BC35E;">
                    <div class="projects-masonry__inner">
                        <span class="projects-masonry__badge" style="background: #F36F8F;">
                            {{projects[1].topic}}
                        </span>

                        <h3 class="projects-masonry__title">
                            <a href="javascript://">{{projects[1].title}}</a>
                        </h3>

                        <p>
                            {{projects[1].description}}
                        </p>

                        <div class="projects-masonry__details-holder">
                            <div class="projects-masonry__details-item">
                                <span>Goal: </span>
                                <span>{{projects[1].goal}}</span>
                            </div>

                            <div class="projects-masonry__details-item">
                                <span>Date: </span>
                                <span>{{projects[1].date}}</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Project #3 -->
            <div class="col-lg-6 col-xl-8 projects-masonry__item projects-masonry__item--height-1 projects-masonry__item--primary">
                <div class="projects-masonry__img">
                    <img class="img--bg" :src="projects[2].imgUrl" alt="img"/>

                    <div class="projects-masonry__inner">
                        <span class="projects-masonry__badge" style="background: #F8AC3A;">
                            {{projects[2].topic}}
                        </span>

                        <h3 class="projects-masonry__title">
                            <a href="javascript://">{{projects[2].title}}</a>
                        </h3>

                        <p>
                            {{projects[2].description}}
                        </p>

                        <div class="projects-masonry__details-holder">
                            <div class="projects-masonry__details-item">
                                <span>Goal: </span>
                                <span>{{projects[2].goal}}</span>
                            </div>

                            <div class="projects-masonry__details-item">
                                <span>Date: </span>
                                <span>{{projects[2].date}}</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Project #4 -->
            <div class="col-lg-6 col-xl-4 projects-masonry__item projects-masonry__item--height-2 projects-masonry__item--primary">
                <div class="projects-masonry__img">
                    <img class="img--bg" :src="projects[3].imgUrl" alt="img"/>

                    <div class="projects-masonry__inner">
                        <span class="projects-masonry__badge" style="background: #2EC774;">
                            {{projects[3].topic}}
                        </span>

                        <h3 class="projects-masonry__title">
                            <a href="javascript://">{{projects[3].title}}</a>
                        </h3>

                        <p>
                            {{projects[3].description}}
                        </p>

                        <div class="projects-masonry__details-holder">
                            <div class="projects-masonry__details-item">
                                <span>Goal: </span>
                                <span>{{projects[3].goal}}</span>
                            </div>

                            <div class="projects-masonry__details-item">
                                <span>Date: </span>
                                <span>{{projects[3].date}}</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Project #5 -->
            <div class="col-lg-6 col-xl-8 projects-masonry__item projects-masonry__item--height-2 projects-masonry__item--horizontal">
                <div class="projects-masonry__img">
                    <img class="img--bg" :src="projects[4].imgUrl" alt="img"/>
                </div>

                <div class="projects-masonry__text" style="background-color: #E78F51;">
                    <div class="projects-masonry__inner">
                        <span class="projects-masonry__badge" style="background: #2EC774;">
                            {{projects[4].topic}}
                        </span>

                        <h3 class="projects-masonry__title">
                            <a href="javascript://">{{projects[4].title}}</a>
                        </h3>

                        <p>
                            {{projects[4].description}}
                        </p>

                        <div class="projects-masonry__details-holder">
                            <div class="projects-masonry__details-item">
                                <span>Goal: </span>
                                <span>{{projects[4].goal}}</span>
                            </div>

                            <div class="projects-masonry__details-item">
                                <span>Date: </span>
                                <span>{{projects[4].date}}</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Project #6 -->
            <div class="col-lg-6 col-xl-4 projects-masonry__item projects-masonry__item--height-2 projects-masonry__item--primary">
                <div class="projects-masonry__img">
                    <img class="img--bg" :src="projects[5].imgUrl" alt="img"/>

                    <div class="projects-masonry__inner">
                        <span class="projects-masonry__badge" style="background: #F36F8F;">
                            {{projects[5].topic}}
                        </span>

                        <h3 class="projects-masonry__title">
                            <a href="javascript://">{{projects[5].title}}</a>
                        </h3>

                        <p>
                            {{projects[5].description}}
                        </p>

                        <div class="projects-masonry__details-holder">
                            <div class="projects-masonry__details-item">
                                <span>Goal: </span>
                                <span>{{projects[5].goal}}</span>
                            </div>

                            <div class="projects-masonry__details-item">
                                <span>Date: </span>
                                <span>{{projects[5].date}}</span>
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
            projects: []
        }
    },
    created: function () {

        this.projects.push({
            id: '1',
            title: 'More than One Life Changed',
            description: 'Rockweed gunnel; candlefish mail-cheeked fish, yellowtail snapper cuskfish elasmobranch seamoth triggerfish gar',
            topic: 'Water Delivery',
            imgUrl: 'https://i.imgur.com/JP6x25z.jpg',
            goal: '25 000$',
            date: `23 Jan'19`,
        })

        this.projects.push({
            id: '2',
            title: 'Helpo for Help',
            description: 'Gray eel-catfish longnose whiptail catfish smalleye squaretail queen danio unicorn fish shortnose greeneye fusilier fish silver carp',
            topic: 'Food',
            imgUrl: 'https://i.imgur.com/3FG02Y8.jpg',
            goal: '25 000$',
            date: `23 Jan'19`,
        })

        this.projects.push({
            id: '3',
            title: 'Help for Children of the East',
            description: 'Murray cod clownfish American sole rockfish dojo loach gulper, trout-perch footballfish, pelican eel. Spinefoot coelacanth eagle ray',
            topic: 'Education',
            imgUrl: 'https://i.imgur.com/mhge8LF.jpg',
            goal: '25 000$',
            date: `23 Jan'19`,
        })

        this.projects.push({
            id: '4',
            title: 'Help for Children of the East',
            description: 'Murray cod clownfish American sole rockfish dojo loach gulper, trout-perch footballfish, pelican eel. Spinefoot coelacanth eagle ray',
            topic: 'Education',
            imgUrl: 'https://i.imgur.com/sCs9EmU.jpg',
            goal: '25 000$',
            date: `23 Jan'19`,
        })

        this.projects.push({
            id: '5',
            title: 'Help for Children of the East',
            description: 'Murray cod clownfish American sole rockfish dojo loach gulper, trout-perch footballfish, pelican eel. Spinefoot coelacanth eagle ray',
            topic: 'Education',
            imgUrl: 'https://i.imgur.com/06Gj4se.jpg',
            goal: '25 000$',
            date: `23 Jan'19`,
        })

        this.projects.push({
            id: '6',
            title: 'Helpo for Help',
            description: 'Gray eel-catfish longnose whiptail catfish smalleye squaretail queen danio unicorn fish shortnose greeneye fusilier fish silver carp',
            topic: 'Medicine',
            imgUrl: 'https://i.imgur.com/2QSv9LD.jpg',
            goal: '25 000$',
            date: `23 Jan'19`,
        })

    },
}
</script>

<style scoped>
/*  */
</style>
