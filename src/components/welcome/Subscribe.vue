<template>
    <section class="subscribe">
        <div class="container">
            <div class="row align-items-end">
                <div class="col-lg-4">
                    <h2 class="subscribe__title">Subscribe.</h2>
                </div>

                <div class="col-lg-8">
                    <form class="subscribe-form" action="javascript://">
                        <input class="subscribe-form__input" type="email" name="email" placeholder="Please enter your email address" required="required"/>
                        <input class="subscribe-form__submit" type="submit" value="Submit"/>
                    </form>
                </div>
            </div>
        </div>
    </section>
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
