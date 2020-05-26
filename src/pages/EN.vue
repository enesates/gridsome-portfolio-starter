<template>
  <Layout>
    <div class="hero container-inner mx-auto flex flex-col justify-between pt-16 pr-16 pb-4 pl-16">
      <div class="text-4xl w-full text-center">
        <div class="leading-tight">ENES ATEŞ</div>
      </div>
      <div class="sm:mt-0">
        <g-image src="../../static/programmer.png" alt="programmer" class="mx-auto py-4" />
      </div>
    </div> <!-- end hero -->

    <div class="container-inner mx-auto">
      <p class="text-lg sm:text-xl">
        Merhaba, ben Enes. İzmir'de yaşayan bir bilgisayar mühendisiyim.
        Şimdiye kadar hep backend developer olarak çalışmış olsam da son dönemde frontend teknolojilerini de öğrenmeye çalışıyorum.
        Bu vesileyle <a href="https://vuejs.org/">Vue.js</a> ile tanıştım ve blogumu açtım.
        Şu anda Salesforce Commerce Cloud platformu ile e-ticaret sitesi projeleri yaptığım bir işteyim. Aynı zamanda makine öğrenmesi alanında doktora çalışması yapıyorum.
        Özgür yazılım felsefesini destekliyor elimden geldiğince bu fikri yaymaya çalışıyorum.
      </p>
      <p class="text-lg sm:text-xl pt-6">
        Kendime ayırdığım vakitlerde mümkün olduğunca kitap okuyup spor yapmaya senelerdir oynayamadığım bilgisayar oyunlarını oynayıp bitirmeye çalışıyorum.
        Birkaç sene önce Lindy Hop dansıyla tanıştım ve düzenli olarak dans ediyorum. Ayrıca bir diğer hobime de zaman ayırmaya başlayabildim ve tiyatro eğitimi alıyorum, amatör olarak tiyatroyla ilgileniyorum.
      </p>

      <div class="flex justify-between items-center py-8">
        <div class="w-1/2 sm:w-1/2 px-4 py-4 sm:py-0">
          <g-image src="../../static/books.png" alt="books" />
        </div>
        <div class="w-1/2 sm:w-1/2 px-4 py-4 sm:py-0">
          <g-image src="../../static/dance.png" alt="dance" />
        </div>
        <div class="w-1/2 sm:w-1/2 px-4 py-4 sm:py-0">
          <g-image src="../../static/shakespeare.png" alt="shakespeare" />
        </div>
        <div class="w-1/2 sm:w-1/2 px-4 py-4 sm:py-0">
          <g-image src="../../static/videogames.png" alt="videogames" />
        </div>
        <div class="w-1/2 sm:w-1/2 px-4 py-4 sm:py-0">
          <g-image src="../../static/bicycle.png" alt="bicycle" />
        </div>
      </div>
    </div>

    <div class="overflow-x-hidden">
      <div class="projects container-inner mx-auto text-xl border-t border-gray-500 border-b py-16 mb-16 relative">
        <h2 class="font-bold mb-6" id="projects">Here are some projects I've worked on:</h2>

        <div class="absolute right-0" style="top: 50px; transform: translate(100%) rotate(180deg)">
          <svg width="170px" height="170px"><use xlink:href="#dots-triangle" /></svg>
        </div>

        <ul class="text-lg sm:text-xl space-y-6">
          <li class="checkmark">
            <div>Salesforce Certified B2C Commerce Developer</div>
            <div class="text-lg text-gray-600">I have been working as a backend developer in the e-commerce projects in <a href="https://wittycommerce.com/">WittyCommerce</a> (Epart of makina Group) company since 2016.</div>
          </li>
          <li class="checkmark">
            <div>Area-priority-based Sensor Deployment Optimisation with Priority Estimation Using K-Means (IET Communications, 11(7):1082–1090, 2017)</div>
            <div class="text-lg text-gray-600">It's a paper which I worked on during my MSc studies. You can find it <a href="https://digital-library.theiet.org/content/journals/10.1049/iet-com.2016.1264">here</a>.</div>
          </li>
        </ul>
      </div> <!-- end projects -->
    </div>

    <div class="overflow-x-hidden border-gray-200 border-b">
      <div class="get-to-know-me container-inner mx-auto text-xl pb-16 relative">
        <div class="absolute left-0" style="top: 50px; transform: translateX(-100%)">
          <svg width="170px" height="170px"><use xlink:href="#dots-triangle" /></svg>
        </div>

        <div class="flex flex-col sm:flex-row justify-between items-center mb-16">
          <div><g-image src="../../static/avatar.png" alt="avatar" class="w-32 h-32 rounded-full mb-8 lg:mb-0" /></div>
          <div class="flex-1 text-lg sm:text-xl ml-6">
            If you want to contact me, please find me on <a href="https://twitter.com/enesatesimov">Twitter</a> or <a href="https://www.linkedin.com/in/enesates/">LinkedIn</a>.
            I also have <a href="https://github.com/enesates">Github</a> and <a href="https://www.goodreads.com/enesates">Goodreads</a> accounts.
            My publications are available in <a href=" https://scholar.google.com/citations?user=LlwteK0AAAAJ&hl=en">Google Scholar</a>.
          </div>
        </div>
      </div> <!-- end get-to-know me -->
    </div>

  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'About'
  }
}
</script>

