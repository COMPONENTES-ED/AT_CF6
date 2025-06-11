<template>
  <div class="curso-main-container pb-3">
    <BannerInterno icono="fas fa-sitemap" titulo="Síntesis"></BannerInterno>
    <div class="container tarjeta tarjeta--blanca p-4 p-md-5">
      <div class="row">
        <div class="col-xl-auto d-none d-xl-block" data-aos="fade-right">
          <figure><img src="@/assets/curso/sintesis1.png" /></figure>
        </div>
        <div class="col-xl" data-aos="fade-left">
          <div class="p-4" style="background-color:#D7E1EB">
            <div class="row">
              <div
                class="col-md-auto d-none d-md-block"
                style="place-self:center;"
              >
                <figure><img src="@/assets/curso/sintesis2.svg" /></figure>
              </div>
              <div class="col-md" style="place-self:center;">
                <p class="mb-0">
                  El siguiente diagrama proporciona una visión general
                  sintetizada de los principales temas abordados en este
                  componente. Este mapa conceptual está diseñado para ayudar al
                  estudiante a visualizar la interconexión entre los diversos
                  aspectos que conforman el proceso de monitoreo y análisis de
                  datos en la agricultura.
                </p>
              </div>
            </div>
          </div>
          <p class="mt-3">
            En el centro del diagrama se encuentra el concepto principal de
            gestión y análisis de datos, del cual se ramifican aprendizajes
            clave que abarcan desde la recolección de datos en campo hasta la
            implementación de estrategias basadas en datos para optimizar
            recursos y aumentar la productividad. A través del uso de
            tecnologías avanzadas como sensores IoT, drones, y plataformas de
            análisis, el estudiante aprenderá cómo transformar grandes volúmenes
            de datos en decisiones prácticas y sostenibles.
          </p>
          <div class="row">
            <div class="col-lg">
              <div
                class="p-4"
                style="background-color:#E3F0D4;border:2px #3BA935 dashed;border-radius:7px;"
              >
                <p class="mb-0">
                  Cada tema se desglosa en subtemas como el desarrollo de
                  competencias en limpieza y análisis de datos, la
                  interpretación visual de la información mediante herramientas
                  gráficas, y el uso de algoritmos de Machine Learning para la
                  generación de modelos predictivos. Estos conocimientos se
                  complementan con un enfoque ético y sostenible, promoviendo
                  soluciones que minimicen el impacto ambiental mientras se
                  fomenta un pensamiento crítico sobre el papel de la tecnología
                  en la agricultura.
                </p>
              </div>
            </div>
            <div class="col-lg-auto d-none d-lg-block">
              <figure><img src="@/assets/curso/sintesis3.svg" /></figure>
            </div>
          </div>
        </div>
      </div>
      <p class="mt-4" data-aos="fade-right">
        Este diagrama sirve como una guía visual que resume la amplitud y
        profundidad de los temas cubiertos en el componente. Permite al
        estudiante comprender rápidamente las relaciones entre los conceptos y
        aplicarlos en su contexto profesional. Le invitamos a utilizar este mapa
        como un complemento al contenido detallado, sirviendo como una
        referencia rápida y un recordatorio visual de los aspectos fundamentales
        de la gestión y análisis de datos en la agricultura.
      </p>
      <div
        class="row justify-content-center p-4"
        style="background-color:#F6F6F6;border-radius:20px;"
      >
        <div class="col-lg-10 mb-5 bgs p-4 brad">
          <figure data-aos="fade-up" data-aos-duration="750">
            <img
              src="@/assets/curso/sintesis.svg"
              alt="La síntesis muestra un mapa conceptual de gestión y análisis de datos para el monitoreo de labores agrícolas, que se ramifica en 10 áreas principales. Abarca desde la importancia del uso eficiente de datos hasta la preparación para desafíos del sector, incluyendo tecnologías avanzadas (sensores IoT, drones), procesamiento de datos, desarrollo de competencias, y estrategias para optimizar recursos. Los subtemas detallan aspectos específicos como técnicas de ciencia de datos, machine learning y análisis de datos agrícolas."
            />
          </figure>
        </div>
        <div class="col-auto">
          <a
            class="anexo mb-5"
            :href="obtenerLink('/downloads/Sintesis.pdf')"
            target="_blank"
          >
            <div class="anexo__icono">
              <img src="@/assets/bullets/icono-pdf.svg" />
            </div>
            <div class="anexo__texto">
              <p>Anexo. Síntesis</p>
            </div></a
          >
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Sintesis',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
