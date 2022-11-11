<script>
import ProductsList from "./ProductsList.vue";
export default {
    name: 'MainContent',
    components: {
        ProductsList
    }
}
</script>

<template>
    <div class="jumbo">

    </div>
    <div class="main_content">
        <div class="container">
            <div class="series_indicator text_center">
                <h2 class="series_text">
                    CURRENT SERIES
                </h2>
            </div>
            <ProductsList></ProductsList>
            <div class="load_more text_center d_flex justify_center">
                <a class="load_more_button" href="#">LOAD MORE</a>
            </div>
        </div>
    </div>
</template>

<style>

</style>