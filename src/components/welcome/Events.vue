<template>
    <section class="section events">
        <img class="events__bg" src="@/assets/images/events_bg.png" alt="img"/>

        <div class="container">
            <div class="row margin-bottom">
                <div class="col-12">
                    <div class="heading heading--primary heading--center">
                        <span class="heading__pre-title">Calendar of Events</span>

                        <h2 class="heading__title">
                            <span>What's Happening Now</span>
                            <br /><span>In Your Area</span>
                        </h2>

                        <p class="no-margin-bottom">
                            Our community is very active, both in real-life and online.
                            There is ALWAYS something going on for your participation.
                        </p>
                    </div>
                </div>
            </div>

            <div class="row">
                <div class="col-md-6 col-lg-4" v-for="event of events" :key="event.id">
                    <div class="event-item">
                        <div class="event-item__img">
                            <img class="img--bg" :src="event.imgUrl" alt="img" />
                        </div>

                        <div class="event-item__content">
                            <h6 class="event-item__title">
                                <a href="javascript://">{{event.title}}</a>
                            </h6>

                            <p>
                                <b>{{event.location}},</b> {{event.city}}, {{event.state}} {{event.postal}}, {{event.country}}
                            </p>

                            <p>
                                <b>{{event.startDate}} - {{event.endDate}},</b> {{event.year}}
                            </p>

                            <p>
                                <b>{{event.startTime}} - {{event.endTime}},</b> {{event.frequency}}
                            </p>
                        </div>
                    </div>
                </div>
            </div>

            <div class="row">
                <div class="col-12 text-center">
                    <a class="button button--primary" href="javascript://">
                        View all events</a>
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
            events: []
        }
    },
    created: function () {

        this.events.push({
            id: '1',
            title: 'Help for Language. Voluanteer',
            location: 'Dark Spurt',
            city: 'San Francisco',
            state: 'CA',
            postal: '94528',
            country: 'USA',
            imgUrl: 'https://i.imgur.com/JXQiB1l.jpg',

            startDate: 'September 30',
            endDate: 'October 31',
            year: '2019',

            startTime: '10:00 AM',
            endTime: '18:00 PM',
            frequency: 'Everyday',
        })

        this.events.push({
            id: '2',
            title: 'The Culture of Africa. Rebirth',
            location: 'Dark Spurt',
            city: 'San Francisco',
            state: 'CA',
            postal: '94528',
            country: 'USA',
            imgUrl: 'https://i.imgur.com/8XXigpo.jpg',

            startDate: 'September 30',
            endDate: 'October 31',
            year: '2019',

            startTime: '10:00 AM',
            endTime: '18:00 PM',
            frequency: 'Everyday',
        })

        this.events.push({
            id: '3',
            title: 'Help for Language. Voluanteer',
            location: 'Dark Spurt',
            city: 'San Francisco',
            state: 'CA',
            postal: '94528',
            country: 'USA',
            imgUrl: 'https://i.imgur.com/4HSTbN1.jpg',

            startDate: 'September 30',
            endDate: 'October 31',
            year: '2019',

            startTime: '10:00 AM',
            endTime: '18:00 PM',
            frequency: 'Everyday',
        })

    },
}
</script>

<style scoped>
/*  */
</style>
