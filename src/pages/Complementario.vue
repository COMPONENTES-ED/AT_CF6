<template>
  <div class="curso-main-container complementario">
    <BannerInterno
      icono="far fa-folder-open"
      titulo="Material complementario"
    ></BannerInterno>
    <div class="container tarjeta tarjeta--blanca p-4 p-md-5 mb-5">
      <div class="table-responsive">
        <table>
          <thead>
            <tr>
              <th colspan="3" scope="col">Tema</th>
              <th colspan="5" scope="col">Referencia APA del material</th>
              <th colspan="2" scope="col">Tipo</th>
              <th colspan="2" scope="col">Enlace</th>
            </tr>
          </thead>
          <tbody>
            <tr
              v-for="(item, index) in computedData"
              :key="'complementario-' + index"
            >
              <td
                class="text-start"
                colspan="3"
                scope="row"
                v-html="item.tema"
              ></td>
              <td
                class="text-start"
                colspan="5"
                scope="row"
                v-html="item.referencia"
              ></td>
              <td colspan="2" v-html="item.tipo"></td>
              <td colspan="2">
                <div class="complementario__enlaces">
                  <a
                    v-for="(link, linkIndex) of item.link"
                    :key="linkIndex"
                    class="complementario__btn"
                    :href="link"
                    target="_blank"
                    ><i class="fas fa-external-link-alt"></i
                  ></a>
                </div>
              </td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'MaterialComplementario',
  computed: {
    complementarioData() {
      return [
        {
          tema: 'Caracterización de sistemas productivos',
          referencia:
            'Food and Agriculture Organization of the United Nations. (2015). <em>World Programme for the Census of Agriculture 2020.</em> [Documento PDF]. FAO.',
          tipo: 'Documento',
          link: 'https://www.fao.org/3/i4913e/i4913e.pdf',
        },
        {
          tema: 'Caracterización de sistemas productivos',
          referencia:
            '<em>Censo Nacional Agropecuario 2014.</em> (n.d.). Gov.co.',
          tipo: 'Documentos',
          link:
            'https://www.dane.gov.co/index.php/estadisticas-por-tema/agropecuario/censo-nacional-agropecuario-2014',
        },
        {
          tema: 'Monitoreo de variables en sistemas productivos',
          referencia:
            'Edu.co. (n.d.). Monitoreo y control de variables ambientales mediante una red inalámbrica para agricultura de precisión en invernaderos. [Documento PDF].',
          tipo: 'Documento',
          link:
            'https://repositorio.ucaldas.edu.co/entities/publication/933cb604-6417-4792-82d8-a157c78af90a',
        },
        {
          tema: 'Sensores IoT en agricultura',
          referencia:
            'Campus, A. [@AgroTechCampus]. (s/f). <em>IoT en la Agricultura.</em> [Video]. Youtube.',
          tipo: 'Video',
          link: 'https://www.youtube.com/watch?v=BU77lTxF5KY',
        },
        {
          tema: 'Análisis de datos agrícolas',
          referencia:
            'Researchgate.net. (n.d.). Análisis de Datos Agropecuarios. [Documento PDF].',
          tipo: 'Documento',
          link:
            'https://www.researchgate.net/publication/373610354_Analisis_de_Datos_Agropecuarios',
        },
        {
          tema: 'Simuladores de Cultivos',
          referencia:
            'Food and Agriculture Organization of the United Nations. (2019). <em>AquaCrop.</em> [Simulador]. FAO.',
          tipo: 'Simulador',
          link: 'http://www.fao.org/aquacrop/es/ ',
        },
        {
          tema: 'Ética en la gestión de datos agrícolas',
          referencia:
            'Mark, R. (2019). Ethics of using AI and big data in agriculture: The case of a large agriculture multinational. <em>ORBIT Journal</em>, 2(2), 1–27.',
          tipo: 'Documento',
          link:
            'https://www.sciencedirect.com/science/article/pii/S2515856220300110 ',
        },
        {
          tema: 'Sostenibilidad en agricultura',
          referencia:
            'Español, C. en [@cnnee]. (n.d.). <em>¿Cómo se puede alcanzar una agricultura sostenible?.</em> [Video]. Youtube. ',
          tipo: 'Video',
          link: 'https://www.youtube.com/watch?v=c26KwI1Vc6o',
        },
        {
          tema: 'Simulador de gestión agrícola',
          referencia:
            '<em>Home.</em> (2019, septiembre 13). [Simulador Web]. APSIM; APSIM Initiative.',
          tipo: 'Simulador',
          link: 'https://www.apsim.info/',
        },
      ]
    },
    computedData() {
      const data = this.complementarioData
      return data.map(item => {
        let nuevoLink = []
        if (item.link) {
          if (typeof item.link === 'string') {
            nuevoLink.push(item.link)
          } else {
            nuevoLink = item.link
          }
        } else if (item.descarga) {
          if (typeof item.descarga === 'string') {
            nuevoLink.push(this.obtenerLink(item.descarga))
          } else {
            item.descarga.forEach(link => {
              nuevoLink.push(this.obtenerLink(link))
            })
          }
        }
        return {
          ...item,
          link: nuevoLink,
        }
      })
    },
  },
}
</script>

<style lang="sass">
.complementario
  &__enlaces
    display: flex
    justify-content: center
    flex-wrap: wrap
    a
      margin: 0 5px
  &__btn
    font-size: 1.5em
    line-height: 1em
table
  width: calc(100% - 1px)
  min-width: 800px
  thead
    background-color: $color-sistema-e
    th
      border-color: $color-sistema-e
  th, td
    padding: 25px 20px
    text-align: center
</style>
