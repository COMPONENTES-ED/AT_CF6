<template>
  <div class="curso-main-container pb-3">
    <BannerInterno></BannerInterno>
    <div class="container tarjeta tarjeta--blanca p-4 p-md-5 mb-5">
      <div class="titulo-principal color-acento-contenido" data-aos="flip-up">
        <div class="titulo-principal__numero"><span>5</span></div>
        <h1>Técnicas de análisis y modelado de datos</h1>
      </div>
      <div class="row" data-aos="fade-up">
        <div class="col-lg pe-lg-0">
          <div
            class="h-100 p-4 d-flex align-content-center flex-wrap"
            style="background-color:#CBF0F5;"
          >
            <p class="mb-0">
              El análisis y modelado de datos representan el núcleo del proceso
              de toma de decisiones basado en datos en la agricultura. Estas
              técnicas permiten transformar grandes volúmenes de información en
              insights valiosos, facilitando la predicción de rendimientos, la
              detección temprana de problemas y la optimización de recursos.
            </p>
          </div>
        </div>
        <div class="col-lg-auto ps-lg-0 d-none d-lg-block">
          <figure><img src="@/assets/curso/tema5/1.png" /></figure>
        </div>
      </div>
      <Separador></Separador>
      <div class="titulo-segundo" data-aos="flip-up">
        <h2 id="t_5_1">
          5.1 Estadística descriptiva aplicada a datos agrícolas
        </h2>
      </div>
      <p data-aos="fade-right">
        La estadística ha sido una herramienta fundamental en la agricultura
        desde sus inicios. A través del análisis de datos históricos y actuales,
        los métodos estadísticos permiten comprender patrones y relaciones
        dentro de los sistemas productivos. Esto es esencial para evaluar el
        impacto de diferentes prácticas agrícolas y optimizar el manejo de
        cultivos.
      </p>
      <div class="row mt-4">
        <div class="col-lg-auto d-none d-lg-block" data-aos="fade-right">
          <figure><img src="@/assets/curso/tema5/2.png" /></figure>
        </div>
        <div class="col-lg" data-aos="fade-left">
          <div
            class="p-4 h-100 d-flex align-content-center flex-wrap"
            style="background-color:#E3F0D4;border:2px #3BA935 dashed;border-radius:7px;"
          >
            <div class="row">
              <div class="col-md-auto d-none d-md-block">
                <figure><img src="@/assets/curso/tema5/3.svg" /></figure>
              </div>
              <div class="col-md">
                <p class="mb-0">
                  En la agricultura moderna, la estadística descriptiva y la
                  inferencia estadística se utilizan para analizar variaciones
                  en el rendimiento, estudiar la relación entre variables como
                  el clima y la producción, y evaluar la efectividad de
                  distintas estrategias de manejo.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="cont_decorativo mb-4 mt-5" data-aos="fade-right">
        <div class="row">
          <div class="col-auto pe-0" style="place-self:center;">
            <figure><img src="@/assets/curso/tema2/4.svg" /></figure>
          </div>
          <div class="col ps-2" style="place-self:center;">
            <h3 class="mb-0 pe-4">Técnicas estadísticas principales</h3>
          </div>
        </div>
      </div>
      <TabsC class="color-acento-contenido">
        <div class="py-3 py-md-4" titulo="Estadística descriptiva">
          <div class="row p-4 col-xl-11 m-auto">
            <div class="col-md-auto mb-4 mb-md-0 col-7 m-auto">
              <figure><img src="@/assets/curso/tema5/4.svg" /></figure>
            </div>
            <div class="col-md">
              <h5>Estadística descriptiva</h5>
              <p class="mb-0">
                Medidas como media, mediana, moda, varianza y desviación
                estándar para resumir datos.
              </p>
            </div>
          </div>
        </div>
        <div class="py-3 py-md-4" titulo="Regresión lineal">
          <div class="row p-4 col-xl-11 m-auto">
            <div class="col-md-auto mb-4 mb-md-0 col-7 m-auto">
              <figure><img src="@/assets/curso/tema5/4.svg" /></figure>
            </div>
            <div class="col-md">
              <h5>Regresión lineal</h5>
              <p class="mb-0">
                Relación entre una variable dependiente y una o más variables
                independientes, útil para predecir rendimientos basados en
                insumos.
              </p>
            </div>
          </div>
        </div>
        <div class="py-3 py-md-4" titulo="Análisis de varianza (ANOVA)">
          <div class="row p-4 col-xl-11 m-auto">
            <div class="col-md-auto mb-4 mb-md-0 col-7 m-auto">
              <figure><img src="@/assets/curso/tema5/4.svg" /></figure>
            </div>
            <div class="col-md">
              <h5>Análisis de varianza (ANOVA)</h5>
              <p class="mb-0">
                Comparación de medias entre diferentes grupos para evaluar el
                efecto de prácticas agrícolas o tratamientos.
              </p>
            </div>
          </div>
        </div>
      </TabsC>
      <p class="mt-4" data-aos="fade-right">
        Estas técnicas son esenciales para un análisis preliminar de los datos y
        proporcionan una base sólida para la aplicación de modelos más
        avanzados.
      </p>
      <Separador></Separador>
      <div class="titulo-segundo" data-aos="flip-up">
        <h2 id="t_5_2">
          5.2 Modelos predictivos y su implementación en cultivos
        </h2>
      </div>
      <div class="cont_2_4">
        <div class="row mt-4">
          <div class="col-lg-auto d-none d-lg-block" data-aos="fade-right">
            <figure><img src="@/assets/curso/tema5/5.png" /></figure>
          </div>
          <div class="col-lg" data-aos="fade-left">
            <p>
              Los modelos predictivos son herramientas clave en la agricultura
              de precisión. Estos modelos utilizan datos históricos y en tiempo
              real para prever resultados futuros, como el rendimiento de los
              cultivos, la aparición de plagas o enfermedades, y la demanda de
              recursos.
            </p>
            <div class="p-4" style="background-color:#D7E1EB;">
              <p class="mb-0">
                El desarrollo y aplicación de modelos predictivos permiten a los
                agricultores anticipar problemas y optimizar sus prácticas antes
                de que ocurran. Esto no solo reduce riesgos, sino que también
                mejora la eficiencia operativa y maximiza la rentabilidad.
              </p>
            </div>
          </div>
        </div>
        <div class="cont_decorativo mb-4 mt-5" data-aos="fade-right">
          <div class="row">
            <div class="col-auto pe-0" style="place-self:center;">
              <figure><img src="@/assets/curso/tema2/4.svg" /></figure>
            </div>
            <div class="col ps-2" style="place-self:center;">
              <h3 class="mb-0 pe-4">Tipos de modelos predictivos</h3>
            </div>
          </div>
        </div>
        <div class="row justify-content-center">
          <div class="col-lg mb-4 mb-lg-0 col-md-9" data-aos="zoom-in">
            <div
              class="p-4 h-100 bg-white text-center cont_2_2"
              style="box-shadow:0px 4px 20px rgba(0,0,0,.1);border-radius:14px;"
            >
              <figure class="mb-3">
                <img
                  class="d-inline"
                  src="@/assets/curso/tema5/6.svg"
                  style="max-width:88px;"
                />
              </figure>
              <h5>Regresión múltiple</h5>
              <p class="mt-4">
                Predice valores continuos basados en múltiples variables
                independientes.
              </p>
            </div>
          </div>
          <div class="col-lg mb-4 mb-lg-0 col-md-9" data-aos="zoom-in">
            <div
              class="p-4 h-100 bg-white text-center cont_2_2"
              style="box-shadow:0px 4px 20px rgba(0,0,0,.1);border-radius:14px;"
            >
              <figure class="mb-3">
                <img
                  class="d-inline"
                  src="@/assets/curso/tema5/7.svg"
                  style="max-width:88px;"
                />
              </figure>
              <h5>Árboles de decisión</h5>
              <p class="mt-4">
                Dividen los datos en grupos homogéneos para hacer predicciones
                basadas en condiciones específicas.
              </p>
            </div>
          </div>
          <div class="col-lg col-md-9" data-aos="zoom-in">
            <div
              class="p-4 h-100 bg-white text-center cont_2_2"
              style="box-shadow:0px 4px 20px rgba(0,0,0,.1);border-radius:14px;"
            >
              <figure class="mb-3">
                <img
                  class="d-inline"
                  src="@/assets/curso/tema5/8.svg"
                  style="max-width:88px;"
                />
              </figure>
              <h5><em>Random Forest</em></h5>
              <p class="mt-4">
                Conjunto de árboles de decisión que mejora la precisión al
                reducir la variabilidad y el sobreajuste.
              </p>
            </div>
          </div>
        </div>
      </div>
      <p class="mt-4" data-aos="fade-right">
        Los modelos predictivos permiten tomar decisiones informadas y basadas
        en datos, mejorando la planificación y ejecución de actividades
        agrícolas.
      </p>
      <Separador></Separador>
      <div class="titulo-segundo" data-aos="flip-up">
        <h2 id="t_5_3">5.3 Análisis de variables y parámetros clave</h2>
      </div>
      <div class="row mt-4">
        <div class="col-lg-auto d-none d-lg-block" data-aos="fade-right">
          <figure><img src="@/assets/curso/tema5/9.png" /></figure>
        </div>
        <div class="col-lg" data-aos="fade-left">
          <p>
            El análisis de variables y parámetros es esencial para comprender
            las dinámicas complejas dentro de los sistemas agrícolas. Las
            variables son elementos medibles que influyen en el sistema
            productivo, mientras que los parámetros son valores que describen
            características de toda la población o del sistema en estudio.
          </p>
          <p class="mb-0">
            Identificar y analizar las variables clave permite a los
            agricultores entender mejor los factores que afectan el rendimiento
            y la salud de los cultivos. Asimismo, el estudio de parámetros
            estadísticos como la media y la desviación estándar ayuda a evaluar
            la consistencia y variabilidad de las prácticas agrícolas.
          </p>
        </div>
      </div>
      <div class="cont_decorativo mb-4 mt-5" data-aos="fade-right">
        <div class="row">
          <div class="col-auto pe-0" style="place-self:center;">
            <figure><img src="@/assets/curso/tema2/4.svg" /></figure>
          </div>
          <div class="col ps-2" style="place-self:center;">
            <h3 class="mb-0 pe-4">Clasificación y análisis</h3>
          </div>
        </div>
      </div>
      <div class="cont_3_1 pt-4 pb-4 pb-xl-5 pt-xl-5">
        <div class="tarjeta bg-white p-4 p-lg-5 pb-lg-4">
          <CarouselRED tipo="b">
            <div class="row pt-lg-4 col-xl-11 m-auto">
              <div class="col-lg-7 mb-4 mb-lg-0">
                <h5>Variables independientes y dependientes</h5>
                <p class="mt-4">
                  Identificación de causas y efectos dentro del sistema
                  agrícola.
                </p>
              </div>
              <div class="col-lg-5">
                <figure class="m-auto col-12 col-md-8 col-lg-12">
                  <img src="@/assets/curso/tema5/10.png" />
                </figure>
              </div>
            </div>
            <div class="row pt-lg-4 col-xl-11 m-auto">
              <div class="col-lg-7 mb-4 mb-lg-0">
                <h5>Variables cualitativas y cuantitativas</h5>
                <p class="mt-4">Clasificación de datos según su naturaleza.</p>
              </div>
              <div class="col-lg-5">
                <figure class="m-auto col-12 col-md-8 col-lg-12">
                  <img src="@/assets/curso/tema5/11.png" />
                </figure>
              </div>
            </div>
            <div class="row pt-lg-4 col-xl-11 m-auto">
              <div class="col-lg-7 mb-4 mb-lg-0">
                <h5>Parámetros de centralización y dispersión</h5>
                <p class="mt-4">
                  Evaluación del rendimiento promedio y la variabilidad en los
                  datos.
                </p>
              </div>
              <div class="col-lg-5">
                <figure class="m-auto col-12 col-md-8 col-lg-12">
                  <img src="@/assets/curso/tema5/12.png" />
                </figure>
              </div>
            </div>
          </CarouselRED>
        </div>
      </div>
      <p class="mt-4" data-aos="fade-right">
        El análisis detallado de variables y parámetros permite realizar ajustes
        finos en la gestión agrícola, mejorando la precisión y la eficacia de
        las intervenciones.
      </p>
      <div
        class="titulo-sexto color-acento-contenido mt-5"
        data-aos="fade-down"
      >
        <h5>Figura 3.</h5>
        <span>Resumen técnicas de análisis de datos en agricultura.</span>
      </div>
      <div class="p-3 p-lg-4 pt-xl-5 pb-xl-5" style="background-color:#EAEFF4;">
        <figure data-aos="fade-up">
          <img
            src="@/assets/curso/tema5/13.svg"
            alt="El diagrama «Resumen técnicas de análisis de datos en agricultura» se ramifica en cinco temas principales: la importancia del análisis y modelado (que facilita decisiones y transforma información), los beneficios (incluyendo predicción y optimización), las técnicas utilizadas (como análisis estadístico y minería de datos), los pasos para realizar el análisis (desde recopilación hasta evaluación), y los retos y consideraciones (como calidad de datos y mantenimiento de modelos).
"
          />
        </figure>
      </div>
      <figcaption class="mt-2 fw-normal">Fuente: OIT, 2024.</figcaption>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Tema5',
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
