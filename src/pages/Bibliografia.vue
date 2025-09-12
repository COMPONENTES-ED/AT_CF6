<template>
  <div class="curso-main-container referencias">
    <BannerInterno
      icono="fas fa-book"
      titulo="Referencias bibliográficas"
    ></BannerInterno>
    <div class="container tarjeta tarjeta--blanca p-4 p-md-5 mb-5">
      <div v-for="ref in orderedData" :key="ref.link" class="referencias__item">
        <span v-html="ref.referencia"></span
        ><a v-if="ref.link" class="ms-1" :href="ref.link" target="_blank"
          ><span v-html="ref.link"></span
          ><i class="ms-1 fas fa-external-link-alt"></i
        ></a>
        <hr class="my-3" />
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'Referencias',
  data: () => ({
    referencias: [
      {
        referencia:
          'Campus, A. [@AgroTechCampus]. (s/f). <em>IoT en la Agricultura.</em> Youtube. Recuperado el 18 de junio de 2025, de',
        link: 'https://www.youtube.com/watch?v=BU77lTxF5KY',
      },
      {
        referencia:
          '<em>Censo Nacional Agropecuario 2014.</em> (n.d.). Gov.co. Recuperado el 18 de junio de 2025, de',
        link:
          'https://www.dane.gov.co/index.php/estadisticas-por-tema/agropecuario/censo-nacional-agropecuario-2014',
      },
      {
        referencia:
          'Edu.co. (n.d.). [Documento PDF]. Recuperado el 18 de junio de 2025, de',
        link:
          'https://repositorio.ucaldas.edu.co/entities/publication/933cb604-6417-4792-82d8-a157c78af90a',
      },
      {
        referencia:
          'Español, C. en [@cnnee]. (n.d.). <em>¿Cómo se puede alcanzar una agricultura sostenible?.</em> [Video]. Youtube. Recuperado el 18 de junio de 2025, de',
        link: 'https://www.youtube.com/watch?v=c26KwI1Vc6o',
      },
      {
        referencia:
          'Food and Agriculture Organization of the United Nations. (2015). <em>World Programme for the Census of Agriculture 2020.</em> [Documento PDF]. FAO.',
        link: 'https://www.fao.org/3/i4913e/i4913e.pdf',
      },
      {
        referencia:
          'Food and Agriculture Organization of the United Nations. (2019). <em>AquaCrop</em> [Simulador]. FAO.',
        link: 'http://www.fao.org/aquacrop/es/',
      },
      {
        referencia:
          'Gamco. (2021). <em>Los 5 desafíos del Big Data.</em> Gamco.',
        link: 'https://gamco.es/los-5-desafios-del-big-data/',
      },
      {
        referencia:
          'García-Arteaga, J. J., Zambrano-Zambrano, J. J., Alcivar-Cevallos, R., & Zambrano-Romero, W. D. (2020). Predicción del rendimiento de cultivos agrícolas usando aprendizaje automático. <em>Revista Arbitrada Interdisciplinaria Koinonía</em>, 5(2), 144.',
        link: 'https://doi.org/10.35381/r.k.v5i2.1013',
      },
      {
        referencia:
          'Hernández-Leal, E. J., Duque-Méndez, N. D., & Moreno-Cadavid, J. (2017). <em>Big Data: una exploración de investigaciones, tecnologías y casos de aplicación. TecnoLógicas</em>, 20(39), 17-24.',
        link: 'https://doi.org/10.22430/22565337.701',
      },
      {
        referencia:
          '<em>Home.</em> (2019, septiembre 13). [Simulador Web]. APSIM; APSIM Initiative.',
        link: 'https://www.apsim.info/',
      },
      {
        referencia: 'IBM. (2021). <em>What is Machine Learning?.</em> IBM.',
        link: 'https://www.ibm.com/topics/machine-learning',
      },
      {
        referencia:
          'Mark, R. (2019). Ethics of using AI and big data in agriculture: The case of a large agriculture multinational. <em>ORBIT Journal</em>, 2(2), 1-27.',
        link: 'https://doi.org/10.29297/orbit.v2i2.109',
      },
      {
        referencia:
          'Nexus Integra. (2020). <em>Big Data vs. Inteligencia Artificial.</em> Nexus Integra.',
        link: 'https://nexusintegra.io/es/big-data-vs-inteligencia-artificial/',
      },
      {
        referencia:
          'Quinto, N. M. D., Villodas, A. J. C., Montero, C. P. C., Cueva, D. L. E., & Vera, S. A. N. (2021). <em>La inteligencia artificial y la toma de decisiones gerenciales.</em> Revista de Investigación Valor Agregado, 8(1), 52-69.',
        link: '',
      },
      {
        referencia:
          'Researchgate.net. (n.d.). [Documento PDF]. Recuperado el 18 de junio de 2025, de ',
        link:
          'https://www.researchgate.net/publication/373610354_Analisis_de_Datos_Agropecuarios',
      },
    ],
  }),
  computed: {
    orderedData() {
      return [...this.referencias].sort((a, b) => {
        const afl = this.quitarAcentos(a.referencia.split(' ')[0].toLowerCase())
        const bfl = this.quitarAcentos(b.referencia.split(' ')[0].toLowerCase())
        if (afl < bfl) return -1
        if (afl > bfl) return 1
        return 0
      })
    },
  },
  methods: {
    quitarAcentos(str) {
      return str.normalize('NFD').replace(/[\u0300-\u036f]/g, '')
    },
  },
}
</script>

<style lang="sass">
.referencias
  &__item
    &:last-child
      hr
        display: none
    a
      color: $blue
      text-decoration: underline
      overflow-wrap: break-word
</style>
