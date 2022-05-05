<template>
    <div>
        <div class="mb-5"><Navbar /></div>

        <NuxtLink to="/arastirma-merkezleri" ><section id="merkez-slider" class="slider mb-5 cursor-pointer">
        <div id="cars-caption" class="caption">
            <h1>Araştırma Merkezleri</h1>
            <p>Uygulama ve Araştırma Merkezlerimiz spesifik konularda araştırmalar yapmak ve bilimsel etkinlikler gerçekleştirmektir:</p>

        </div>
        
        </section>
        </NuxtLink>

        <NuxtLink to="/arastirma-ve-projeler" ><section id="proje-slider" class="slider mb-5 cursor-pointer">
        <div id="cars-caption" class="caption">
            <h1>Bilimsel Araştırma Projeleri Birimi</h1>
            <p>Bilimsel araştırma projelerinin kabulü, değerlendirilmesi, desteklenmesi, izlenmesi amacıyla oluşturulan komisyon</p>

        </div>
     </section>
    </NuxtLink>

     <NuxtLink to="/bilgi-kaynaklari" ><section id="kaynak-slider" class="slider mb-5 cursor-pointer">
        <div id="cars-caption" class="caption">
            <h1>Bilgi Kaynakları</h1>
            <p>Uygulama ve Araştırma Merkezlerimiz spesifik konularda araştırmalar yapmak ve bilimsel etkinlikler gerçekleştirmektir:</p>

        </div>
     </section>
     </NuxtLink>
    </div>
</template>

<script>


export default {

}
</script>
<style scoped>

#merkez-slider {
  height: 250px;
  background: url("@/img/arastirma-merkezi.jpg") center center no-repeat;
  background-size: cover;
}
#proje-slider {
  height: 250px;
  background: url("@/img/proje.jpg") center center no-repeat;
  background-size: cover;
}
#kaynak-slider {
  height: 250px;
  background: url("@/img/kaynak-2.jpg") center center no-repeat;
  background-size: cover;
}

#cars-caption {
  height: 250px;
  background: rgba(0, 0, 0, 0.7);
}
h1 {
    padding-top: 50px;
    padding-bottom: 20px;
    color: white;
    text-align: center;
}
p {
    color: white;
    text-align: center;
}

</style>