<script>
import Products from '../assets/data/dc-comics.js'
export default {
    name: 'Single Product',
    data() {
        return {
            products: Products
        }
    }
}
</script>

<template>
    <div class="grid align_items">
        <div v-for="product in products" class="col-2 card padding_card_10">
            <div class="card_elements">
                <img :src="product.thumb" alt="Card info">
                <p class="card_title">
                    {{ product.series }}
                </p>
            </div>
        </div>
    </div>
</template>

<style>

</style>