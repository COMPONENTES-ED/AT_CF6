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
          tema: 'Monitoreo de Variables en Sistemas Productivos',
          referencia: 'Edu.co. (n.d.). [Documento PDF].',
          tipo: 'Documento',
          link:
            'https://repositorio.ucaldas.edu.co/entities/publication/933cb604-6417-4792-82d8-a157c78af90a',
        },
        {
          tema: 'Sensores IoT en Agricultura',
          referencia:
            'Campus, A. [@AgroTechCampus]. (s/f). IoT en la Agricultura. [Video]. Youtube.',
          tipo: 'Video',
          link: 'https://www.youtube.com/watch?v=BU77lTxF5KY',
        },
        {
          tema: 'Análisis de Datos Agrícolas',
          referencia: 'Researchgate.net. (n.d.). [Documento PDF].',
          tipo: 'Documento',
          link:
            'https://www.researchgate.net/publication/373610354_Analisis_de_Datos_Agropecuarios',
        },
        {
          tema: 'Simuladores de Cultivos',
          referencia:
            'Food and Agriculture Organization of the United Nations. (2019). AquaCrop. [Simulador]. FAO.',
          tipo: 'Simulador',
          link: 'http://www.fao.org/aquacrop/es/',
        },
        {
          tema: 'Ética en la Gestión de Datos Agrícolas',
          referencia:
            'Mark, R. (2019). Ethics of using AI and big data in agriculture: The case of a large agriculture multinational. ORBIT Journal, 2(2), 1–27. https://doi.org/10.29297/orbit.v2i2.109',
          tipo: 'Documento',
          link:
            'https://www.sciencedirect.com/science/article/pii/S2515856220300110',
        },
        {
          tema: 'Sostenibilidad en Agricultura',
          referencia:
            'Español, C. en [@cnnee]. (n.d.). ¿Cómo se puede alcanzar una agricultura sostenible?. [Video]. Youtube.',
          tipo: 'Video',
          link: 'https://www.youtube.com/watch?v=c26KwI1Vc6o',
        },
        {
          tema: 'Simulador de Gestión Agrícola',
          referencia:
            'Home. (2019, septiembre 13). [Simulador Web]. APSIM; APSIM Initiative.',
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
