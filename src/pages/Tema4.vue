<template>
  <div class="curso-main-container pb-3">
    <BannerInterno></BannerInterno>
    <div class="container tarjeta tarjeta--blanca p-4 p-md-5 mb-5">
      <div class="titulo-principal color-acento-contenido" data-aos="flip-up">
        <div class="titulo-principal__numero"><span>4</span></div>
        <h1>Herramientas tecnológicas en el monitoreo agrícola</h1>
      </div>
      <p data-aos="fade-down" data-aos-duration="600">
        La tecnología ha revolucionado la forma en que se gestionan los sistemas
        agrícolas. Desde la recopilación de datos hasta su análisis, las
        herramientas tecnológicas han permitido a los agricultores tomar
        decisiones más precisas y proactivas. Este capítulo explora las
        principales herramientas tecnológicas utilizadas en el monitoreo y
        procesamiento de datos agrícolas, destacando su impacto en la eficiencia
        y sostenibilidad del sector.
      </p>
      <div class="row mt-4">
        <div class="col-lg" data-aos="fade-right">
          <div
            class="p-4 h-100 d-flex align-content-center flex-wrap"
            style="background-color:#E3F0D4;border:2px #3BA935 dashed;border-radius:7px;"
          >
            <div class="row">
              <div class="col-md-auto d-none d-md-block">
                <figure><img src="@/assets/curso/tema4/1.svg" /></figure>
              </div>
              <div class="col-md">
                <p class="mb-0">
                  En un entorno de producción agrícola altamente competitivo, la
                  capacidad de integrar tecnologías avanzadas como sensores IoT,
                  plataformas de visualización y software analítico ha llevado a
                  la agricultura a un nuevo nivel de precisión y control. Estas
                  herramientas no solo mejoran la recolección y análisis de
                  datos, sino que también optimizan recursos y aumentan la
                  productividad.
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-auto d-none d-lg-block" data-aos="fade-left">
          <figure><img src="@/assets/curso/tema4/2.png" /></figure>
        </div>
      </div>
      <Separador></Separador>
      <div class="titulo-segundo" data-aos="flip-up">
        <h2 id="t_4_1">4.1 Sensores IoT: tipos y usos prácticos</h2>
      </div>
      <div class="cont_2_4">
        <div class="row mt-4">
          <div class="col-lg-auto d-none d-lg-block" data-aos="fade-right">
            <figure><img src="@/assets/curso/tema4/3.png" /></figure>
          </div>
          <div class="col-lg" data-aos="fade-left">
            <p>
              Los sensores IoT (Internet de las Cosas) son dispositivos que
              recopilan datos en tiempo real y los transmiten a través de redes
              para su análisis y uso. En la agricultura, estos sensores juegan
              un papel crucial en la monitorización de las condiciones
              ambientales y del suelo, proporcionando información precisa y
              continua que permite a los agricultores responder rápidamente a
              cambios en las condiciones del campo.
            </p>
            <div class="p-4" style="background-color:#D7E1EB;">
              <p class="mb-0">
                La implementación de sensores IoT en la agricultura ha permitido
                la transición hacia la agricultura de precisión, donde cada
                decisión se basa en datos específicos y localizados. Estos
                dispositivos recopilan información crítica como la humedad del
                suelo, la temperatura, los niveles de nutrientes y la radiación
                solar.
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
              <h3 class="mb-0 pe-4">Tipos de sensores</h3>
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
                  src="@/assets/curso/tema4/4.svg"
                  style="max-width:88px;"
                />
              </figure>
              <h5>Sensores de humedad del suelo</h5>
              <p class="mt-4">
                Miden el contenido de agua en el suelo para optimizar el riego.
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
                  src="@/assets/curso/tema4/5.svg"
                  style="max-width:88px;"
                />
              </figure>
              <h5>Sensores de temperatura y humedad ambiental</h5>
              <p class="mt-4">Ayudan a controlar el microclima del cultivo.</p>
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
                  src="@/assets/curso/tema4/6.svg"
                  style="max-width:88px;"
                />
              </figure>
              <h5>Sensores de pH y nutrientes</h5>
              <p class="mt-4">
                Evalúan la salud del suelo y los requerimientos de
                fertilización.
              </p>
            </div>
          </div>
        </div>
      </div>
      <p class="mt-4" data-aos="fade-right">
        Estos sensores permiten una monitorización continua y detallada,
        facilitando la toma de decisiones proactivas y basadas en datos.
      </p>
      <Separador></Separador>
      <div class="titulo-segundo" data-aos="flip-up">
        <h2 id="t_4_2">4.2 Plataformas y software para el análisis de datos</h2>
      </div>
      <div class="row" data-aos="fade-up">
        <div class="col-lg pe-lg-0">
          <div
            class="h-100 p-4 d-flex align-content-center flex-wrap"
            style="background-color:#E4F7FA;"
          >
            <p class="mb-0">
              El análisis de datos en la agricultura requiere de herramientas
              especializadas que permitan interpretar grandes volúmenes de
              información de manera eficiente. Las plataformas y software de
              análisis son fundamentales para convertir los datos brutos en
              conocimientos accionables, facilitando la toma de decisiones
              informadas.
            </p>
          </div>
        </div>
        <div class="col-lg-auto ps-lg-0 d-none d-lg-block">
          <figure><img src="@/assets/curso/tema4/7.png" /></figure>
        </div>
      </div>
      <div class="row mt-5">
        <div
          class="col-lg-auto ps-lg-0 d-none d-lg-block"
          data-aos="fade-right"
        >
          <figure><img src="@/assets/curso/tema4/8.svg" /></figure>
        </div>
        <div class="col-lg pe-lg-0" data-aos="fade-left">
          <p>
            Estas herramientas permiten realizar análisis descriptivos,
            predictivos y prescriptivos, adaptados a las necesidades específicas
            de cada sistema productivo. Además, la integración de datos de
            múltiples fuentes en un solo sistema mejora la capacidad de los
            agricultores para identificar patrones y tendencias, optimizando así
            la gestión agrícola.
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
          <div class="p-4" style="background-color:#F3F0EA;">
            <ol class="lista-ol--cuadro mb-0">
              <li class="d-flex">
                <div
                  class="lista-ol--cuadro__vineta"
                  style="background-color:#78B62E;"
                >
                  <span class="fw-bold" style="color:#12263F;">1</span>
                </div>
                <span
                  ><strong
                    >Plataformas de análisis como Tableau y Power BI:</strong
                  >
                  proporcionan dashboards interactivos para visualizar datos
                  clave.</span
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
                  ><strong>Software estadístico como R y Python:</strong>
                  permiten análisis avanzados y modelado predictivo.</span
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
                  ><strong>Sistemas de gestión agrícola (FMS):</strong> integran
                  datos de monitoreo y análisis para una gestión integral del
                  campo.</span
                >
              </li>
            </ol>
          </div>
          <p class="mt-4 mb-0">
            El uso de estas herramientas facilita el manejo de datos complejos y
            mejora la eficiencia operativa en la agricultura.
          </p>
        </div>
      </div>
      <Separador></Separador>
      <div class="titulo-segundo" data-aos="flip-up">
        <h2 id="t_4_3">
          4.3 Visualización con herramientas como Excel y Tableau
        </h2>
      </div>
      <div class="row">
        <div class="col-lg mb-4 mb-lg-0" data-aos="fade-up">
          <div
            class="h-100 p-4 d-flex align-content-center flex-wrap"
            style="background-color:#D7E1EB;border-radius:10px;"
          >
            <p class="mb-0">
              La visualización de datos es un componente esencial en el
              procesamiento de información agrícola. A través de gráficos, mapas
              y dashboards, los agricultores pueden interpretar datos complejos
              de manera rápida y efectiva, lo que facilita la identificación de
              patrones y la toma de decisiones.
            </p>
          </div>
        </div>
        <div
          class="col-lg d-none d-lg-block"
          data-aos="fade-down"
          data-aos-duration="800"
        >
          <figure><img src="@/assets/curso/tema4/9.png" /></figure>
        </div>
        <div class="col-lg" data-aos="fade-up">
          <div
            class="h-100 p-4 d-flex align-content-center flex-wrap"
            style="background-color:#C8E2AA;border-radius:7px;"
          >
            <p class="mb-0">
              Herramientas como Excel y Tableau son ampliamente utilizadas en el
              sector agrícola para crear representaciones visuales claras y
              concisas de datos. Estas herramientas permiten a los usuarios
              transformar grandes conjuntos de datos en información visualmente
              comprensible, ayudando a comunicar hallazgos y monitorear
              indicadores clave.
            </p>
          </div>
        </div>
      </div>
      <div class="cont_1_1 pt-5">
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
        <div class="row mt-4">
          <div class="col-lg-8" data-aos="fade-right">
            <div
              class="p-3 p-lg-4"
              style="background-color:#01B9D1;border-radius:10px;"
            >
              <ul class="lista-ul mb-0">
                <li class="d-flex bg-white p-2" style="border-radius:4px;">
                  <i class="fas fa-check-circle" style="color:#78B62E;"></i
                  ><span
                    ><strong>Excel:</strong> ofrece funcionalidades básicas de
                    visualización y análisis de datos a través de gráficos y
                    tablas dinámicas.</span
                  >
                </li>
                <li class="d-flex bg-white p-2" style="border-radius:4px;">
                  <i class="fas fa-check-circle" style="color:#78B62E;"></i
                  ><span
                    ><strong>Tableau:</strong> facilita la creación de
                    dashboards interactivos que integran múltiples fuentes de
                    datos.</span
                  >
                </li>
                <li class="d-flex bg-white p-2 mb-0" style="border-radius:4px;">
                  <i class="fas fa-check-circle" style="color:#78B62E;"></i
                  ><span
                    ><strong>Visualización personalizada:</strong> uso de
                    librerías como Matplotlib y Seaborn en Python para análisis
                    más detallados.</span
                  >
                </li>
              </ul>
            </div>
            <p class="mb-0 mt-4">
              La visualización de datos es fundamental para comunicar insights
              de manera efectiva y tomar decisiones basadas en evidencia.
            </p>
          </div>
          <div class="col-lg-4 d-none d-lg-block" data-aos="fade-left">
            <figure><img src="@/assets/curso/tema4/10.png" /></figure>
          </div>
        </div>
        <Separador></Separador>
        <div class="titulo-segundo" data-aos="flip-up">
          <h2 id="t_4_4">
            4.4 Introducción al uso de Python y R para análisis avanzado
          </h2>
        </div>
      </div>
      <div class="row">
        <div class="col-lg-auto d-none d-lg-block" data-aos="fade-right">
          <figure><img src="@/assets/curso/tema4/11.png" /></figure>
        </div>
        <div class="col-lg" data-aos="fade-left">
          <p>
            Python y R son lenguajes de programación ampliamente utilizados en
            el análisis de datos, especialmente en sectores como la agricultura,
            donde se manejan grandes volúmenes de datos complejos. Estos
            lenguajes ofrecen poderosas bibliotecas y herramientas para la
            limpieza, análisis, modelado y visualización de datos.
          </p>
          <p class="mb-0">
            La adopción de Python y R en la agricultura ha permitido un análisis
            más avanzado, incluyendo modelos predictivos y técnicas de Machine
            Learning. Estos lenguajes no solo facilitan la automatización de
            tareas, sino que también proporcionan la flexibilidad necesaria para
            adaptar los análisis a las necesidades específicas de cada sistema
            productivo.
          </p>
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
        <div class="col-lg" data-aos="fade-right">
          <AccordionRED tipo="a" clase-tarjeta="tarjeta">
            <div class="row col-xl-11 m-auto" titulo="Python">
              <p>
                Bibliotecas como pandas, numpy y scikit-learn para análisis de
                datos y aprendizaje automático.
              </p>
            </div>
            <div class="row col-xl-11 m-auto" titulo="R">
              <p>
                herramientas como ggplot2 y dplyr para visualización y
                manipulación de datos.
              </p>
            </div>
            <div
              class="row col-xl-11 m-auto"
              titulo="Automatización y escalabilidad"
            >
              <p>
                Creación de scripts que permiten análisis repetitivos y
                escalables.
              </p>
            </div>
          </AccordionRED>
          <p class="mb-0">
            El uso de Python y R permite a los agricultores y analistas manejar
            datos complejos y realizar análisis detallados, mejorando
            significativamente la toma de decisiones.
          </p>
        </div>
        <div class="col-lg-auto d-none d-lg-block" data-aos="fade-left">
          <figure><img src="@/assets/curso/tema4/12.png" /></figure>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Tema4',
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
