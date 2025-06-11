<template>
  <div class="curso-main-container pb-3">
    <BannerInterno></BannerInterno>
    <div class="container tarjeta tarjeta--blanca p-4 p-md-5 mb-5">
      <div class="titulo-principal color-acento-contenido" data-aos="flip-up">
        <div class="titulo-principal__numero"><span>3</span></div>
        <h1>Ciclo de vida de los datos agrícolas</h1>
      </div>
      <div class="row">
        <div class="col-lg-auto d-none d-lg-block" data-aos="fade-right">
          <figure><img src="@/assets/curso/tema3/1.png" /></figure>
        </div>
        <div class="col-lg" data-aos="fade-left">
          <p class="mb-4">
            El manejo de datos en la agricultura no es un proceso aislado, sino
            un ciclo continuo que abarca desde la recolección de datos hasta su
            análisis y posterior aplicación en la toma de decisiones. Este ciclo
            de vida asegura que los datos sean gestionados de manera efectiva,
            maximizando su valor en cada etapa. En el contexto agrícola, donde
            las decisiones deben tomarse rápidamente y con precisión, la
            comprensión del ciclo de vida de los datos es crucial.
          </p>
          <div class="p-4" style="background-color:#F3F0EA;">
            <p class="mb-0">
              En este apartado se abordan las etapas principales del ciclo de
              vida de los datos agrícolas, proporcionando al aprendiz un marco
              estructurado para comprender cómo se gestionan y utilizan los
              datos en sistemas productivos. Desde la recolección y
              almacenamiento hasta la visualización y análisis, se explorarán
              las mejores prácticas y tecnologías aplicadas en cada fase.
            </p>
          </div>
        </div>
      </div>
      <Separador></Separador>
      <div class="titulo-segundo" data-aos="flip-up">
        <h2 id="t_3_1">
          3.1 Recolección de datos: sensores IoT, estaciones meteorológicas y
          drones
        </h2>
      </div>
      <div class="row">
        <div class="col-lg" data-aos="fade-right">
          <div class="p-4 h-100" style="background-color:#CBF0F5;">
            <div class="row">
              <div class="col-md-auto d-none d-md-block">
                <figure><img src="@/assets/curso/tema3/2.svg" /></figure>
              </div>
              <div class="col-md">
                <p class="mb-0">
                  La recolección de datos es el primer paso en el ciclo de vida
                  de los datos y sienta las bases para todo el proceso de
                  gestión de la información. En la agricultura, los datos se
                  recopilan de múltiples fuentes, incluidas tecnologías
                  avanzadas como sensores IoT, estaciones meteorológicas y
                  drones. Estas herramientas permiten capturar información
                  detallada sobre las condiciones del suelo, el clima y la salud
                  de los cultivos en tiempo real.
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-auto d-none d-lg-block" data-aos="fade-left">
          <figure><img src="@/assets/curso/tema3/3.png" /></figure>
        </div>
      </div>
      <p class="mt-4" data-aos="fade-right">
        La precisión y la frecuencia de la recolección de datos son esenciales
        para garantizar decisiones informadas. Además, la automatización de este
        proceso a través de tecnologías IoT reduce los errores humanos y asegura
        la consistencia en la captura de información.
      </p>
      <div class="cont_decorativo mb-4 mt-5" data-aos="fade-right">
        <div class="row">
          <div class="col-auto pe-0" style="place-self:center;">
            <figure><img src="@/assets/curso/tema2/4.svg" /></figure>
          </div>
          <div class="col ps-2" style="place-self:center;">
            <h3 class="mb-0 pe-4">Aspectos clave</h3>
          </div>
        </div>
      </div>
      <div class="cont_3_1 mt-5 pt-4 pb-4 pb-xl-5 pt-xl-5">
        <div class="tarjeta bg-white p-4 p-lg-5 pb-lg-4">
          <CarouselRED tipo="b">
            <div class="row pt-lg-4 col-xl-11 m-auto">
              <div class="col-lg-5 mb-4 mb-lg-0">
                <figure class="m-auto col-12 col-md-8 col-lg-12">
                  <img src="@/assets/curso/tema3/5.png" />
                </figure>
              </div>
              <div class="col-lg-7">
                <h5>Sensores IoT</h5>
                <p class="mt-4">
                  Dispositivos que miden variables como humedad, temperatura y
                  pH del suelo.
                </p>
              </div>
            </div>
            <div class="row pt-lg-4 col-xl-11 m-auto">
              <div class="col-lg-5 mb-4 mb-lg-0">
                <figure class="m-auto col-12 col-md-8 col-lg-12">
                  <img src="@/assets/curso/tema3/6.png" />
                </figure>
              </div>
              <div class="col-lg-7">
                <h5>Estaciones meteorológicas</h5>
                <p class="mt-4">
                  Proporcionan datos climáticos específicos como precipitación,
                  velocidad del viento y radiación solar.
                </p>
              </div>
            </div>
            <div class="row pt-lg-4 col-xl-11 m-auto">
              <div class="col-lg-5 mb-4 mb-lg-0">
                <figure class="m-auto col-12 col-md-8 col-lg-12">
                  <img src="@/assets/curso/tema3/7.png" />
                </figure>
              </div>
              <div class="col-lg-7">
                <h5>Drones</h5>
                <p class="mt-4">
                  Capturan imágenes de alta resolución y datos multiespectrales
                  para evaluar la salud de los cultivos y detectar problemas.
                </p>
              </div>
            </div>
          </CarouselRED>
        </div>
      </div>
      <p class="mt-4" data-aos="fade-right">
        Estas tecnologías permiten un monitoreo constante y detallado de los
        sistemas agrícolas, facilitando la toma de decisiones proactivas.
      </p>
      <Separador></Separador>
      <div class="titulo-segundo" data-aos="flip-up">
        <h2 id="t_3_2">3.2 Limpieza y transformación de datos</h2>
      </div>
      <div class="cont_2_4">
        <div class="row">
          <div class="col-lg" data-aos="fade-right">
            <p>
              Los datos recolectados en campo suelen contener errores, valores
              faltantes o inconsistencias que deben ser corregidos antes de su
              análisis. La limpieza y transformación de datos son etapas
              esenciales que garantizan la calidad y utilidad de la información.
            </p>
            <p class="mb-0">
              Este proceso no solo mejora la precisión de los modelos
              predictivos, sino que también optimiza la toma de decisiones al
              eliminar ruidos que podrían distorsionar los resultados. La
              limpieza incluye la corrección de errores y la normalización de
              datos, mientras que la transformación adapta la información a
              formatos específicos para su análisis posterior.
            </p>
          </div>
          <div class="col-lg-auto d-none d-lg-block" data-aos="fade-left">
            <figure><img src="@/assets/curso/tema3/8.png" /></figure>
          </div>
        </div>
        <div class="cont_decorativo mb-4 mt-5" data-aos="fade-right">
          <div class="row">
            <div class="col-auto pe-0" style="place-self:center;">
              <figure><img src="@/assets/curso/tema2/4.svg" /></figure>
            </div>
            <div class="col ps-2" style="place-self:center;">
              <h3 class="mb-0 pe-4">Aspectos clave</h3>
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
                  src="@/assets/curso/tema3/9.svg"
                  style="max-width:88px;"
                />
              </figure>
              <h5>Técnicas de limpieza</h5>
              <p class="mt-4">
                Eliminación de duplicados, imputación de datos faltantes y
                detección de valores atípicos.
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
                  src="@/assets/curso/tema3/10.svg"
                  style="max-width:88px;"
                />
              </figure>
              <h5>Transformación de datos</h5>
              <p class="mt-4">
                Conversión de datos categóricos en numéricos, escalado y
                normalización.
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
                  src="@/assets/curso/tema3/11.svg"
                  style="max-width:88px;"
                />
              </figure>
              <h5>Herramientas recomendadas</h5>
              <p class="mt-4">
                <em>Software</em> como Excel, Python (Pandas, Numpy) y R para
                automatizar procesos de limpieza y transformación.
              </p>
            </div>
          </div>
        </div>
      </div>
      <p class="mt-4" data-aos="fade-right">
        La limpieza y transformación son pasos fundamentales para garantizar que
        los análisis sean precisos y confiables.
      </p>
      <Separador></Separador>
      <div class="row">
        <div class="col-lg" data-aos="fade-right">
          <div class="titulo-segundo" data-aos="flip-up">
            <h2 id="t_3_3">
              3.3 Almacenamiento y organización de datos: herramientas y
              técnicas
            </h2>
          </div>
          <p>
            El almacenamiento adecuado de datos asegura su accesibilidad,
            seguridad y uso eficiente a lo largo del tiempo. En la agricultura,
            donde se generan grandes volúmenes de información de manera
            continua, es fundamental contar con sistemas de almacenamiento
            robustos y organizados.
          </p>
          <div class="p-4 mt-4" style="background-color:#F3F0EA">
            <div class="row">
              <div
                class="col-md-auto d-none d-md-block"
                style="place-self:center;"
              >
                <figure><img src="@/assets/curso/tema3/12.svg" /></figure>
              </div>
              <div class="col-md" style="place-self:center;">
                <p class="mb-0">
                  La elección del sistema de almacenamiento ya sea local o en la
                  nube, depende de varios factores, como la escalabilidad, el
                  costo y los requisitos de seguridad. Una buena organización
                  facilita la integración de datos de múltiples fuentes y su uso
                  eficiente en análisis posteriores.
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-auto d-none d-lg-block" data-aos="fade-left">
          <figure><img src="@/assets/curso/tema3/13.png" /></figure>
        </div>
      </div>
      <div class="cont_2_4 pt-5">
        <div class="cont_decorativo mb-4" data-aos="fade-right">
          <div class="row">
            <div class="col-auto pe-0" style="place-self:center;">
              <figure><img src="@/assets/curso/tema2/4.svg" /></figure>
            </div>
            <div class="col ps-2" style="place-self:center;">
              <h3 class="mb-0 pe-4">Aspectos clave</h3>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-lg-auto d-none d-lg-block" data-aos="fade-right">
            <figure><img src="@/assets/curso/tema3/14.png" /></figure>
          </div>
          <div class="col-lg" data-aos="fade-left">
            <AccordionRED tipo="a" clase-tarjeta="tarjeta">
              <div
                class="row col-xl-11 m-auto"
                titulo="Bases de datos relacionales"
              >
                <p>
                  Herramientas como MySQL y PostgreSQL para gestionar datos
                  estructurados.
                </p>
              </div>
              <div
                class="row col-xl-11 m-auto"
                titulo="Almacenamiento en la nube"
              >
                <p>Soluciones escalables como Google Cloud, AWS y Azure.</p>
              </div>
              <div class="row col-xl-11 m-auto" titulo="Sistemas híbridos">
                <p>
                  Combinan almacenamiento local y en la nube para maximizar
                  eficiencia y seguridad.
                </p>
              </div>
            </AccordionRED>
            <p class="mb-0">
              La organización adecuada permite una recuperación rápida y un
              análisis más efectivo de los datos almacenados.
            </p>
          </div>
        </div>
      </div>
      <Separador></Separador>
      <div class="titulo-segundo" data-aos="flip-up">
        <h2 id="t_3_4">
          3.4 Análisis y visualización: Representación gráfica y
          <em>dashboards</em>
        </h2>
      </div>
      <p data-aos="fade-right">
        El análisis y la visualización de datos son etapas donde la información
        bruta se transforma en conocimiento útil. En la agricultura, estas
        etapas son cruciales para identificar patrones, prever problemas y tomar
        decisiones basadas en datos.
      </p>
      <div class="row mt-4">
        <div class="col-lg" data-aos="fade-right">
          <div class="p-4 h-100" style="background-color:#E3F0D4;">
            <div class="row">
              <div class="col-md-auto d-none d-md-block">
                <figure><img src="@/assets/curso/tema3/15.svg" /></figure>
              </div>
              <div class="col-md">
                <p class="mb-0">
                  Las herramientas de visualización, como <em>dashboards</em>
                  interactivos, facilitan la comprensión de datos complejos y
                  permiten monitorear múltiples variables en tiempo real. Esto
                  es especialmente útil para gestionar grandes extensiones de
                  tierra, donde el monitoreo manual sería impráctico y costoso.
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-auto d-none d-lg-block" data-aos="fade-left">
          <figure><img src="@/assets/curso/tema3/16.png" /></figure>
        </div>
      </div>
      <div class="cont_decorativo mb-4 mt-5" data-aos="fade-right">
        <div class="row">
          <div class="col-auto pe-0" style="place-self:center;">
            <figure><img src="@/assets/curso/tema2/4.svg" /></figure>
          </div>
          <div class="col ps-2" style="place-self:center;">
            <h3 class="mb-0 pe-4">Aspectos clave</h3>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-lg-auto d-none d-lg-block" data-aos="fade-right">
          <figure><img src="@/assets/curso/tema3/17.png" /></figure>
        </div>
        <div class="col-lg" data-aos="fade-left">
          <AccordionRED tipo="a" clase-tarjeta="tarjeta">
            <div
              class="row col-xl-11 m-auto"
              titulo="Análisis descriptivo y predictivo"
            >
              <p>
                Uso de modelos estadísticos para identificar tendencias y prever
                resultados.
              </p>
            </div>
            <div
              class="row col-xl-11 m-auto"
              titulo="<em>Dashboards</em> interactivos"
            >
              <p>
                Herramientas como Tableau y Power BI para representar datos de
                manera visual y dinámica.
              </p>
            </div>
            <div
              class="row col-xl-11 m-auto"
              titulo="Librerías de visualización en Python"
            >
              <p>
                Matplotlib, Seaborn y Plotly para crear gráficos personalizados.
              </p>
            </div>
          </AccordionRED>
          <p class="mb-0">
            La capacidad de analizar y visualizar datos efectivamente es
            esencial para la toma de decisiones informadas en la gestión
            agrícola.
          </p>
        </div>
      </div>
      <div
        class="titulo-sexto color-acento-contenido mt-5"
        data-aos="fade-down"
      >
        <h5>Figura 2.</h5>
        <span>Resumen ciclo de vida de las datos agrícolas.</span>
      </div>
      <div class="p-3 p-lg-4 pt-xl-5 pb-xl-5" style="background-color:#EAEFF4;">
        <figure data-aos="fade-up">
          <img
            src="@/assets/curso/tema3/18.svg"
            alt="El diagrama «Resumen ciclo de vida de los datos agrícolas», presenta un mapa conceptual que se divide en tres áreas principales: la definición del ciclo de vida de los datos con sus etapas desde la generación hasta la aplicación, la importancia del ciclo en la agricultura (que incluye la precisión de la información, accesibilidad y uso para decisiones), y los beneficios del manejo eficiente que comprende la optimización de recursos, sostenibilidad de cultivos y capacidad de respuesta a cambios.
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
  name: 'Tema3',
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
