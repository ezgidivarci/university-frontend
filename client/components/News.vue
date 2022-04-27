<template>
    <div>
        <section id="features" class="section-area">
        <div class="features-top">
            <h2 class="section-header">FEATURED SERVICE</h2>
            <p>Vintage Cars Blog is a hub of classic car knowledge, featuring reviews.</p>

        </div>
        
        <div class="features-body">
            <div class="container">
                <div class="col3">
                    <div class="item">
                        <div class="zoom">
                            <!--<img :src="require(`@/img/${card.image$|||`)"> -->
                        </div>
                        <div class="item-text">
                             <h1>{{cardsSection.header}}</h1>
                            <p> {{cardsSection.productDescription}}
                                Has there ever been a more iconic American car than the ’57 Chevy Bel Air? Of course there hasn’t, it’s not even close. Not even the Model T is as much a 
                                symbol of its age as the Bel Air. It represents American middle class postwar prosperity perfectly, and is a rare example of a car with styling that was exactly in line with contemporary design.</p>
                            <a href="#" class="btn-details">More Details</a>

                        </div>

                    </div>

                 </div>
            </div>
        </div>
    </section>
       

        <div><NewsCard v-for="card in cardsSection.cards"
        :key="card.id"
        :card="card" /> </div>

    </div>
    
</template>



<script>

export default {
   props: ['cardsSection']
}
</script>

<style scoped>

</style>