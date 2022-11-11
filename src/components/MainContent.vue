<script>
import Products from '../assets/data/dc-comics.js'
export default {
    name: 'MainContent'
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
            <div class="grid">
                <div class="col-2 card">
                    <div class="card_elements">
                        <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX"
                            alt="Card info">
                        <p class="card_title">
                            ACTION COMICS
                        </p>
                    </div>
                </div>
            </div>
            <div class="load_more text_center d_flex justify_center">
                <a class="load_more_button" href="#">LOAD MORE</a>
            </div>
        </div>
    </div>
</template>

<style>

</style>