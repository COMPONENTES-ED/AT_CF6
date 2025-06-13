<template>
  <div class="curso-main-container pb-3">
    <BannerInterno></BannerInterno>
    <div class="container tarjeta tarjeta--blanca p-4 p-md-5 mb-5">
      <div class="titulo-principal color-acento-contenido" data-aos="flip-up">
        <div class="titulo-principal__numero"><span>6</span></div>
        <h1>Aplicaciones prácticas del monitoreo de datos</h1>
      </div>
      <div
        class="p-4 h-100 d-flex align-content-center flex-wrap"
        style="background-color:#E3F0D4;border:2px #3BA935 dashed;border-radius:7px;"
        data-aos="fade-up"
        data-aos-duration="600"
      >
        <div class="row">
          <div class="col-md-auto d-none d-md-block">
            <figure><img src="@/assets/curso/tema6/1.svg" /></figure>
          </div>
          <div class="col-md">
            <p class="mb-0">
              La agricultura moderna se enfrenta a desafíos complejos que exigen
              soluciones prácticas e innovadoras. La integración de tecnologías
              de monitoreo y análisis de datos ha permitido desarrollar
              aplicaciones que optimizan cada etapa del proceso productivo,
              desde la siembra hasta la cosecha. Estas aplicaciones no solo
              mejoran la eficiencia operativa, sino que también promueven la
              sostenibilidad al reducir el uso de insumos y mitigar el impacto
              ambiental.
            </p>
          </div>
        </div>
      </div>
      <Separador></Separador>
      <div class="titulo-segundo" data-aos="flip-up">
        <h2 id="t_6_1">6.1 Gestión de sistemas de riego inteligente</h2>
      </div>
      <div class="row">
        <div class="col-lg" data-aos="fade-right">
          <div class="p-4" style="background-color:#CBF0F5;">
            <p class="mb-0">
              El riego es una de las actividades más críticas en la agricultura,
              especialmente en regiones con recursos hídricos limitados. Los
              sistemas de riego inteligente utilizan datos en tiempo real para
              optimizar la cantidad y frecuencia del riego, asegurando que cada
              planta reciba la cantidad exacta de agua que necesita.
            </p>
          </div>
          <p class="mb-0 mt-4">
            Estos sistemas combinan sensores de humedad del suelo con algoritmos
            de análisis que ajustan automáticamente los ciclos de riego en
            función de las condiciones climáticas y las necesidades específicas
            de los cultivos. Esto no solo reduce el desperdicio de agua, sino
            que también mejora la salud del suelo y aumenta los rendimientos.
          </p>
        </div>
        <div class="col-lg-auto d-none d-lg-block" data-aos="fade-left">
          <figure><img src="@/assets/curso/tema6/2.png" /></figure>
        </div>
      </div>
      <div class="cont_2_4 pt-5">
        <div class="cont_decorativo mb-4" data-aos="fade-right">
          <div class="row">
            <div class="col-auto pe-0" style="place-self:center;">
              <figure><img src="@/assets/curso/tema2/4.svg" /></figure>
            </div>
            <div class="col ps-2" style="place-self:center;">
              <h3 class="mb-0 pe-4">Implementación en campo</h3>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-lg-auto d-none d-lg-block" data-aos="fade-right">
            <figure><img src="@/assets/curso/tema6/3.png" /></figure>
          </div>
          <div class="col-lg" data-aos="fade-left">
            <AccordionRED tipo="a" clase-tarjeta="tarjeta">
              <div
                class="row col-xl-11 m-auto"
                titulo="Sensores de humedad y temperatura del suelo"
              >
                <p>
                  Capturan datos críticos que alimentan el sistema de riego.
                </p>
              </div>
              <div
                class="row col-xl-11 m-auto"
                titulo="Controladores automáticos"
              >
                <p>Ajustan el riego en función de los datos recibidos.</p>
              </div>
              <div class="row col-xl-11 m-auto" titulo="Sistemas híbridos">
                <p>
                  Permiten a los agricultores supervisar y ajustar el sistema
                  desde cualquier lugar.
                </p>
              </div>
            </AccordionRED>
            <p class="mb-0">
              El riego inteligente es una herramienta poderosa para gestionar
              recursos de manera eficiente y sostenible.
            </p>
          </div>
        </div>
      </div>
      <Separador></Separador>
      <div class="titulo-segundo" data-aos="flip-up">
        <h2 id="t_6_2">
          6.2 Monitoreo de plagas y enfermedades en tiempo real
        </h2>
      </div>
      <div class="cont_1_1">
        <div class="row" data-aos="fade-up">
          <div class="col-lg pe-lg-0">
            <div
              class="h-100 p-4 d-flex align-content-center flex-wrap"
              style="background-color:#D7E1EB;"
            >
              <p class="mb-0">
                Las plagas y enfermedades representan una amenaza constante para
                la agricultura, causando pérdidas significativas si no se
                manejan adecuadamente. El monitoreo en tiempo real utiliza
                sensores, imágenes satelitales y modelos predictivos para
                detectar la presencia de plagas y enfermedades antes de que se
                conviertan en un problema generalizado.
              </p>
            </div>
          </div>
          <div class="col-lg-auto ps-lg-0 d-none d-lg-block">
            <figure><img src="@/assets/curso/tema6/4.png" /></figure>
          </div>
        </div>
        <div class="row mt-5">
          <div class="col-lg-auto d-none d-lg-block" data-aos="fade-right">
            <figure><img src="@/assets/curso/tema6/5.svg" /></figure>
          </div>
          <div class="col-lg" data-aos="fade-left">
            <p>
              Esta detección temprana permite a los agricultores tomar medidas
              inmediatas, como la aplicación localizada de pesticidas o el
              ajuste de prácticas culturales, minimizando el impacto en los
              cultivos y reduciendo la dependencia de productos químicos.
            </p>
            <div class="cont_decorativo mb-4 mt-5" data-aos="fade-right">
              <div class="row">
                <div class="col-auto pe-0" style="place-self:center;">
                  <figure><img src="@/assets/curso/tema2/4.svg" /></figure>
                </div>
                <div class="col ps-2" style="place-self:center;">
                  <h3 class="mb-0 pe-4">Tecnologías utilizadas</h3>
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
                    ><strong>Cámaras multiespectrales:</strong> identifican
                    patrones en las hojas que indican infecciones.</span
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
                    ><strong>Modelos predictivos:</strong> anticipan brotes de
                    plagas basados en datos climáticos y de cultivo.</span
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
                    ><strong>Sistemas de alerta temprana:</strong> notifican a
                    los agricultores cuando se detectan condiciones favorables
                    para plagas o enfermedades.</span
                  >
                </li>
              </ol>
            </div>
            <p class="mt-4 mb-0">
              El monitoreo de plagas y enfermedades mejora la seguridad
              alimentaria y reduce las pérdidas económicas.
            </p>
          </div>
        </div>
        <Separador></Separador>
        <div class="titulo-segundo" data-aos="flip-up">
          <h2 id="t_6_3">
            6.3 Optimización de la producción mediante análisis de datos
            climáticos
          </h2>
        </div>
      </div>
      <p data-aos="fade-right">
        El clima es uno de los factores más influyentes en la producción
        agrícola. Un análisis preciso de los datos climáticos permite a los
        agricultores anticipar eventos como sequías, heladas o lluvias intensas,
        y adaptar sus estrategias para minimizar los riesgos asociados.
      </p>
      <div class="row mt-4">
        <div class="col-lg-auto d-none d-lg-block" data-aos="fade-right">
          <figure><img src="@/assets/curso/tema6/6.png" /></figure>
        </div>
        <div class="col-lg" data-aos="fade-left">
          <div
            class="p-4 h-100 d-flex align-content-center flex-wrap"
            style="background-color:#F3F0EA;border:2px #9D978D dashed;border-radius:7px;"
          >
            <div class="row">
              <div class="col-md-auto d-none d-md-block">
                <figure><img src="@/assets/curso/tema6/7.svg" /></figure>
              </div>
              <div class="col-md">
                <p class="mb-0">
                  El uso de datos climáticos históricos y en tiempo real ayuda a
                  planificar actividades agrícolas como la siembra y la cosecha,
                  asegurando que se realicen en las condiciones más favorables.
                  Además, la integración de estos datos con modelos predictivos
                  mejora la toma de decisiones a largo plazo, como la selección
                  de cultivos adaptados a condiciones climáticas específicas.
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
            <h3 class="mb-0 pe-4">Elementos estratégicos</h3>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-lg-8" data-aos="fade-right">
          <div
            class="p-3 p-lg-4"
            style="background-color:#01B9D1;border-radius:10px;"
          >
            <ul class="lista-ul mb-0">
              <li class="d-flex bg-white p-2" style="border-radius:4px;">
                <i class="fas fa-check-circle" style="color:#78B62E;"></i
                ><span
                  ><strong>Estaciones meteorológicas:</strong> proporcionan
                  datos climáticos precisos y localizados.</span
                >
              </li>
              <li class="d-flex bg-white p-2" style="border-radius:4px;">
                <i class="fas fa-check-circle" style="color:#78B62E;"></i
                ><span
                  ><strong>Tableau:</strong> facilita la creación de
                  <em>dashboards</em> interactivos que integran múltiples
                  fuentes de datos.</span
                >
              </li>
              <li class="d-flex bg-white p-2 mb-0" style="border-radius:4px;">
                <i class="fas fa-check-circle" style="color:#78B62E;"></i
                ><span
                  ><strong><em>Software</em> de modelado climático:</strong>
                  simula escenarios futuros y su impacto en la producción.</span
                >
              </li>
            </ul>
          </div>
          <p class="mb-0 mt-4">
            La optimización basada en datos climáticos ayuda a los agricultores
            a gestionar la incertidumbre y mejorar la resiliencia de sus
            sistemas productivos.
          </p>
        </div>
        <div class="col-lg-4 d-none d-lg-block" data-aos="fade-left">
          <figure><img src="@/assets/curso/tema6/8.png" /></figure>
        </div>
      </div>
      <div
        class="titulo-sexto color-acento-contenido mt-5"
        data-aos="fade-down"
      >
        <h5>Figura 4.</h5>
        <span
          >Resumen aplicaciones prácticas del monitoreo y procesamiento de
          datos.</span
        >
      </div>
      <div class="p-3 p-lg-4 pt-xl-5 pb-xl-5" style="background-color:#EAEFF4;">
        <figure data-aos="fade-up">
          <img
            src="@/assets/curso/tema6/9.svg"
            alt="El diagrama «Resumen aplicaciones prácticas del monitoreo y procesamiento de datos», es un mapa conceptual que se estructura en cuatro secciones principales: los desafíos en la agricultura, la integración de tecnologías de monitoreo y análisis de datos, las aplicaciones específicas (que incluyen optimización del proceso productivo, mejora de eficiencia operativa y promoción de la sostenibilidad), y los beneficios de estas aplicaciones como el aumento de productividad y la reducción de costos."
          />
        </figure>
      </div>
      <figcaption class="mt-2 fw-normal">Fuente: OIT, 2024.</figcaption>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Tema6',
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
