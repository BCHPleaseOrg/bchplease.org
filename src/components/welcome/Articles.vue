<template>
    <section class="section blog">
        <img class="blog__bg" src="@/assets/images/blog_bg.png" alt="img"/>

        <div class="container">
            <div class="row margin-bottom">
                <div class="col-12">
                    <div class="heading heading--primary heading--center">
                        <span class="heading__pre-title">Featured Publications</span>

                        <h2 class="heading__title no-margin-bottom">
                            <span>Read Our Articles</span>
                            <br /><span>Speaking Directly To You</span>
                        </h2>
                    </div>
                </div>
            </div>

            <div class="row offset-margin">
                <div class="col-md-6 col-lg-5 col-xl-4">
                    <div class="blog-item blog-item--style-1">
                        <div class="blog-item__img">
                            <img class="img--bg" :src="articles[0].imgUrl" alt="img"/>
                            <span class="blog-item__badge" style="background-color: #49C2DF;">
                                {{articles[0].topic}}
                            </span>
                        </div>

                        <div class="blog-item__content">
                            <h6 class="blog-item__title"><a href="javascript://">
                                {{articles[0].title}}</a>
                            </h6>

                            <p>
                                {{articles[0].summary}}
                            </p>

                            <div class="blog-item__details">
                                <span class="blog-item__date">{{articles[0].date}}</span>

                                <span>
                                    <svg class="icon">
                                        <use xlink:href="#comment"></use>
                                    </svg>
                                    {{articles[0].count}}
                                </span>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="col-md-6 col-lg-7 col-xl-8">
                    <div class="blog-item blog-item--style-2">
                        <img class="img--bg" :src="articles[1].imgUrl" alt="img"/>

                        <div class="blog-item__content">
                            <span class="blog-item__badge" style="background-color: #2EC774;">
                                {{articles[1].topic}}
                            </span>

                            <h6 class="blog-item__title">
                                <a href="javascript://">
                                    {{articles[1].title}}</a>
                            </h6>

                            <p>
                                {{articles[1].summary}}
                            </p>
                        </div>

                        <div class="blog-item__details">
                            <span class="blog-item__date">{{articles[1].date}}</span>

                            <span>
                                <svg class="icon">
                                    <use xlink:href="#comment"></use>
                                </svg>
                                {{articles[1].count}}
                            </span>
                        </div>
                    </div>
                </div>

                <div class="col-md-6 col-lg-7 col-xl-8">
                    <div class="blog-item blog-item--style-2">
                        <img class="img--bg" :src="articles[2].imgUrl" alt="img"/>

                        <div class="blog-item__content">
                            <span class="blog-item__badge" style="background-color: #F8AC3A;">
                                Food
                            </span>

                            <h6 class="blog-item__title">
                                <a href="javascript://">
                                    {{articles[2].title}}</a>
                            </h6>

                            <p>
                                {{articles[2].summary}}
                            </p>
                        </div>

                        <div class="blog-item__details">
                            <span class="blog-item__date">{{articles[2].date}}</span>

                            <span>
                                <svg class="icon">
                                    <use xlink:href="#comment"></use>
                                </svg>
                                {{articles[2].count}}
                            </span>
                        </div>
                    </div>
                </div>

                <div class="col-md-6 col-lg-5 col-xl-4">
                    <div class="blog-item blog-item--style-1">
                        <div class="blog-item__img">
                            <img class="img--bg" :src="articles[3].imgUrl" alt="img"/>

                            <span class="blog-item__badge" style="background-color: #F36F8F;">
                                Medicine
                            </span>
                        </div>

                        <div class="blog-item__content">
                            <h6 class="blog-item__title">
                                <a href="javascript://">
                                    {{articles[3].title}}</a>
                            </h6>

                            <p>
                                {{articles[3].summary}}
                            </p>

                            <div class="blog-item__details">
                                <span class="blog-item__date">{{articles[3].date}}</span>

                                <span>
                                    <svg class="icon">
                                        <use xlink:href="#comment"></use>
                                    </svg>
                                    {{articles[3].count}}
                                </span>
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
            articles: [],
        }
    },
    created: function () {

        this.articles.push({
            topic: 'Water Delivery',
            title: `Save the Children's Role in Fight Against Malnutrition Hailed`,
            summary: `Sharksucker sea toad candiru rocket danio tilefish stingray deepwater stingray Sacramento splittail canthigaster`,
            imgUrl: 'https://i.imgur.com/X98MRCw.jpg',
            date: `23 Jan' 19`,
            count: 501,
        })

        this.articles.push({
            topic: 'Education',
            title: `Back to the future: Quality education through respect, commitment and accountability`,
            summary: `Sharksucker sea toad candiru rocket danio tilefish stingray deepwater stingray Sacramento splittail canthigaster`,
            imgUrl: 'https://i.imgur.com/8srOqpS.png',
            date: `23 Jan' 19`,
            count: 284,
        })

        this.articles.push({
            topic: '',
            title: `Condolences to Families Effected By Flash Floods in Setswetla, Alexandra Township, Johannesburg`,
            summary: `Sharksucker sea toad candiru rocket danio tilefish stingray deepwater stingray Sacramento splittail canthigaster`,
            imgUrl: `https://i.imgur.com/p9NmKPj.png`,
            date: `23 Jan' 19`,
            count: 921,
        })

        this.articles.push({
            topic: '',
            title: `Save the Children's Role in Fight Against Malnutrition Hailed`,
            summary: `Sharksucker sea toad candiru rocket danio tilefish stingray deepwater stingray Sacramento splittail canthigaster`,
            imgUrl: 'https://i.imgur.com/fkN0WOH.png',
            date: `23 Jan' 19`,
            count: 295,
        })

    }
}
</script>

<style scoped>
/*  */
</style>
