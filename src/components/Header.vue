<template >
    <header>
        <div class="container">
           <headerSection/>
            <div class="header_bottom">
                <div class="header_bottom_top">
                    <div class="header_bottom_top_left">
                        <div class="header_bottom_top_left_card">
                            <img src="../assets/images/moon 1.svg" alt="">
                            <img src="../assets/images/arrow 1.svg" alt="">
                            <img src="../assets/images/sun 1.svg" alt="">
                        </div>
                        <p>В любое время дня и ночи</p>
                    </div>
                    <div class="header_bottom_top_right">

                    </div>
                </div>
                <div class="header_bottom_n1">
                    <div class="header_bottom_left">

                    </div>
                    <div class="header_bottom_right">

                    </div>
                </div>
            </div>
        </div>
    </header>
</template>
<script>
import headerSection from './header/header-section.vue'

export default {
    name:'App',
    components:{
        headerSection,
    }
}
</script>
<style lang="">
    
</style>