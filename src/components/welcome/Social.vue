<template>
    <section class="section instagram no-padding-bottom">
        <div class="container">
            <div class="row align-items-end margin-bottom">
                <div class="col-md-7 col-lg-8">
                    <div class="heading heading--primary">
                        <span class="heading__pre-title">Social Media</span>

                        <h2 class="heading__title no-margin-bottom">
                            <span>#BCHPlease</span>
                        </h2>
                    </div>
                </div>

                <div class="col-md-5 col-lg-4 text-md-right">
                    <div class="slider__nav instagram-slider__nav">
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

        <div class="instagram-slider">

            <a class="instagram-slider__item" href="javascript://" v-for="photo of photos" :key="photo.id">
                <img class="img--bg" :src="photo.url" alt="img"/>

                <span class="instagram-slider__icon">
                    <i class="fa fa-instagram" aria-hidden="true"></i>
                </span>

                <span class="instagram-slider__icon-hover">
                    <i class="fa fa-instagram" aria-hidden="true"></i>
                </span>
            </a>

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
            photos: []
        }
    },
    created: function () {

        this.photos.push({
            id: '1',
            url: 'https://i.imgur.com/1JNuG3O.jpg',
        })

        this.photos.push({
            id: '2',
            url: 'https://i.imgur.com/grsuiAW.jpg',
        })

        this.photos.push({
            id: '3',
            url: 'https://i.imgur.com/FSOlINl.jpg',
        })

        this.photos.push({
            id: '4',
            url: 'https://i.imgur.com/LUWFJIO.jpg',
        })

        this.photos.push({
            id: '5',
            url: 'https://i.imgur.com/W06sPnJ.jpg',
        })

        this.photos.push({
            id: '6',
            url: 'https://i.imgur.com/09niMvb.jpg',
        })

        this.photos.push({
            id: '7',
            url: 'https://i.imgur.com/zhInK3x.jpg',
        })

        this.photos.push({
            id: '8',
            url: 'https://i.imgur.com/IlSH2Ji.jpg',
        })

    }
}
</script>

<style scoped>
/*  */
</style>
