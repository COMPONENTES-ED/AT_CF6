<template>
  <div class="curso-main-container pb-3">
    <BannerInterno></BannerInterno>
    <div class="container tarjeta tarjeta--blanca p-4 p-md-5 mb-5">
      <div class="titulo-principal color-acento-contenido" data-aos="flip-up">
        <div class="titulo-principal__numero"><span>8</span></div>
        <h1>Aplicaciones prácticas del monitoreo de datos</h1>
      </div>
      <div class="row mt-4">
        <div class="col-lg" data-aos="fade-right">
          <div
            class="p-4 h-100 d-flex align-content-center flex-wrap"
            style="background-color:#CBF0F5;"
          >
            <div class="row">
              <div class="col-md-auto d-none d-md-block">
                <figure><img src="@/assets/curso/tema8/1.svg" /></figure>
              </div>
              <div class="col-md">
                <p class="mb-0">
                  La aplicación práctica de tecnologías y estrategias de gestión
                  de datos en la agricultura puede entenderse mejor a través de
                  estudios de caso y ejemplos reales. Estos ejemplos ofrecen una
                  visión integral de cómo se implementan sistemas de monitoreo y
                  análisis en contextos específicos, destacando los desafíos,
                  soluciones y resultados obtenidos.
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-auto d-none d-lg-block" data-aos="fade-left">
          <figure><img src="@/assets/curso/tema8/2.png" /></figure>
        </div>
      </div>
      <Separador></Separador>
      <div class="titulo-segundo" data-aos="flip-up">
        <h2 id="t_8_1">
          8.1 Implementación de un sistema de monitoreo en cultivos de maíz
        </h2>
      </div>
      <div class="cont_2_4">
        <p data-aos="fade-right">
          El maíz es uno de los cultivos más importantes a nivel mundial, pero
          su producción enfrenta desafíos significativos debido a las
          condiciones climáticas cambiantes y la variabilidad del suelo. Este
          estudio de caso se centra en la implementación de un sistema de
          monitoreo basado en sensores IoT y plataformas de análisis de datos en
          una plantación de maíz en una región semiárida.
        </p>
        <div class="cont_decorativo mb-4 mt-5" data-aos="fade-right">
          <div class="row">
            <div class="col-auto pe-0" style="place-self:center;">
              <figure><img src="@/assets/curso/tema2/4.svg" /></figure>
            </div>
            <div class="col ps-2" style="place-self:center;">
              <h3 class="mb-0 pe-4">Descripción del Proyecto</h3>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-lg-auto d-none d-lg-block" data-aos="fade-right">
            <figure><img src="@/assets/curso/tema8/3.png" /></figure>
          </div>
          <div class="col-lg" data-aos="fade-left">
            <AccordionRED tipo="a" clase-tarjeta="tarjeta">
              <div class="row col-xl-11 m-auto" titulo="Objetivo">
                <p>
                  Optimizar el uso del agua y mejorar la productividad del
                  cultivo.
                </p>
              </div>
              <div class="row col-xl-11 m-auto" titulo="Tecnologías utilizadas">
                <p>
                  Sensores de humedad del suelo, estaciones meteorológicas y
                  plataformas de análisis como Tableau.
                </p>
              </div>
              <div class="row col-xl-11 m-auto" titulo="Resultados">
                <p>
                  Reducción del consumo de agua en un 25 % y aumento del
                  rendimiento del cultivo en un 15 %.
                </p>
              </div>
            </AccordionRED>
            <p class="mb-0">
              <strong>Nota:</strong> este caso demuestra cómo el monitoreo
              continuo y el análisis de datos en tiempo real pueden transformar
              la gestión del riego y mejorar la sostenibilidad.
            </p>
          </div>
        </div>
      </div>
      <Separador></Separador>
      <div class="titulo-segundo" data-aos="flip-up">
        <h2 id="t_8_2">
          8.2 Uso de <em>Big Data</em> para la predicción de rendimiento en
          plantaciones de café
        </h2>
      </div>
      <div class="row">
        <div class="col-lg" data-aos="fade-right">
          <p>
            El café es un cultivo de alto valor, pero su producción está
            altamente influenciada por factores como el clima, el manejo del
            suelo y la aparición de plagas. Este estudio de caso explora cómo
            una cooperativa cafetera utiliza <em>Big Data</em> para predecir el
            rendimiento de sus plantaciones y planificar estrategias de manejo
            más efectivas.
          </p>
          <div class="cont_decorativo mb-4 mt-5" data-aos="fade-right">
            <div class="row">
              <div class="col-auto pe-0" style="place-self:center;">
                <figure><img src="@/assets/curso/tema2/4.svg" /></figure>
              </div>
              <div class="col ps-2" style="place-self:center;">
                <h3 class="mb-0 pe-4">Descripción del Proyecto</h3>
              </div>
            </div>
          </div>
          <div class="p-4" style="background-color:#E3F0D4;">
            <ol class="lista-ol--cuadro mb-0">
              <li class="d-flex">
                <div
                  class="lista-ol--cuadro__vineta"
                  style="background-color:#78B62E;"
                >
                  <span class="fw-bold" style="color:#12263F;">1</span>
                </div>
                <span
                  >Objetivo: predecir el rendimiento de la cosecha y optimizar
                  la distribución de insumos.</span
                >
              </li>
              <li class="d-flex">
                <div
                  class="lista-ol--cuadro__vineta"
                  style="background-color:#78B62E;"
                >
                  <span class="fw-bold" style="color:#12263F;">2</span>
                </div>
                <span
                  >Tecnologías utilizadas: análisis de datos climáticos
                  históricos, modelado predictivo con Python y sistemas de
                  información geográfica (SIG).</span
                >
              </li>
              <li class="d-flex mb-0">
                <div
                  class="lista-ol--cuadro__vineta"
                  style="background-color:#78B62E;"
                >
                  <span class="fw-bold" style="color:#12263F;">3</span>
                </div>
                <span
                  >Resultados: mejora de la precisión en las predicciones de
                  rendimiento en un 20 % y reducción de costos operativos en un
                  10 %.</span
                >
              </li>
            </ol>
          </div>
          <p class="mt-4 mb-0">
            <strong>Nota:</strong> este ejemplo destaca el valor del análisis
            predictivo en la planificación estratégica y la mejora de la
            eficiencia operativa.
          </p>
        </div>
        <div class="col-lg-auto d-none d-lg-block" data-aos="fade-left">
          <figure><img src="@/assets/curso/tema8/4.png" /></figure>
        </div>
      </div>
      <Separador></Separador>
      <div class="titulo-segundo" data-aos="flip-up">
        <h2 id="t_8_3">
          8.3 Aplicación de <em>Machine Learning</em> en el monitoreo de
          invernaderos
        </h2>
      </div>
      <div class="cont_2_4">
        <div class="row">
          <div class="col-lg-auto d-none d-lg-block" data-aos="fade-right">
            <figure><img src="@/assets/curso/tema8/5.png" /></figure>
          </div>
          <div class="col-lg" data-aos="fade-left">
            <div
              class="p-4 h-100 d-flex align-content-center flex-wrap"
              style="background-color:#CBF0F5;"
            >
              <div class="row">
                <div class="col-md-auto d-none d-md-block">
                  <figure><img src="@/assets/curso/tema8/6.svg" /></figure>
                </div>
                <div class="col-md">
                  <p class="mb-0">
                    Los invernaderos ofrecen un entorno controlado para la
                    producción agrícola, pero requieren una gestión cuidadosa
                    para optimizar el uso de recursos y maximizar la
                    productividad. Este estudio de caso examina cómo se aplican
                    algoritmos de <em>Machine Learning</em> para monitorear y
                    controlar las condiciones dentro de un invernadero de
                    cultivo de tomate.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="row mt-4">
          <div class="col-lg" data-aos="fade-left">
            <AccordionRED tipo="a" clase-tarjeta="tarjeta">
              <div class="row col-xl-11 m-auto" titulo="Objetivo">
                <p>
                  Automatizar el control del microclima y optimizar el uso de
                  energía y agua.
                </p>
              </div>
              <div class="row col-xl-11 m-auto" titulo="Tecnologías utilizadas">
                <p>
                  Sensores de temperatura y humedad, cámaras multiespectrales y
                  algoritmos de <em>Machine Learning</em> para predecir las
                  necesidades del cultivo.
                </p>
              </div>
              <div class="row col-xl-11 m-auto" titulo="Resultados">
                <p>
                  Reducción del consumo de energía en un 30 % y mejora del
                  rendimiento del cultivo en un 20 %.
                </p>
              </div>
            </AccordionRED>
            <p class="mb-0">
              <strong>Nota:</strong> este caso ilustra cómo el uso de IA y ML
              puede llevar la gestión de invernaderos a un nivel superior de
              eficiencia y sostenibilidad.
            </p>
          </div>
          <div class="col-lg-auto d-none d-lg-block" data-aos="fade-right">
            <figure><img src="@/assets/curso/tema8/7.png" /></figure>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Tema8',
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
