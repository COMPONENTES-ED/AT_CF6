<template>
  <div class="curso-main-container introduccion">
    <BannerInterno></BannerInterno>
    <div class="container tarjeta tarjeta--blanca p-4 p-md-5 mb-5">
      <div class="titulo-principal color-acento-contenido" data-aos="flip-up">
        <div class="titulo-principal__numero">
          <span><i class="fas fa-info"></i></span>
        </div>
        <h1>Introducción</h1>
      </div>
      <div class="cont_intro">
        <div class="row">
          <div class="col-lg" data-aos="fade-right" data-aos-duration="550">
            <div
              class="p-4"
              style="background-color:#E3F0D4;border:2px #3BA935 dashed;border-radius:7px;"
            >
              <p class="mb-0">
                En un entorno agrícola cada vez más competitivo y condicionado
                por factores climáticos y de mercado, el uso eficiente de los
                datos se ha convertido en una herramienta clave para optimizar
                la productividad y sostenibilidad de los sistemas productivos.
                El componente de gestión y análisis de datos para el monitoreo
                de labores agrícolas está diseñado para capacitar al aprendiz en
                el manejo integral de la información generada en los procesos
                agrícolas, desde su recolección en campo hasta su análisis y
                visualización para la toma de decisiones.
              </p>
            </div>
            <p class="mt-3 mb-0">
              Este componente abarca el uso de tecnologías avanzadas como
              sensores IoT, drones y plataformas de análisis de datos, que
              permiten registrar variables críticas como temperatura, humedad,
              niveles de radiación solar y comportamiento de los cultivos.
              Mediante la aplicación de técnicas de ciencia de datos y
              algoritmos de Machine Learning, el aprendiz podrá procesar grandes
              volúmenes de información (Big Data) y generar modelos predictivos
              que mejoren la eficiencia en la gestión de recursos como el agua,
              fertilizantes y tiempo de cosecha.
            </p>
          </div>
          <div
            class="col-lg-auto d-none d-lg-block"
            data-aos="fade-left"
            data-aos-duration="550"
          >
            <figure><img src="@/assets/curso/intro1.svg" /></figure>
          </div>
        </div>
        <div class="row mt-4">
          <div
            class="col-lg-auto d-none d-lg-block"
            data-aos="fade-right"
            data-aos-duration="550"
          >
            <figure><img src="@/assets/curso/intro2.png" /></figure>
          </div>
          <div class="col-lg" data-aos="fade-left" data-aos-duration="550">
            <div class="p-4" style="background-color:#CBF0F5">
              <div class="row">
                <div
                  class="col-md-auto d-none d-md-block"
                  style="place-self:center;"
                >
                  <figure><img src="@/assets/curso/intro3.svg" /></figure>
                </div>
                <div class="col-md" style="place-self:center;">
                  <p class="mb-0">
                    La formación proporcionada se centra en desarrollar
                    competencias para procesar los datos obtenidos de sistemas
                    de monitoreo conforme a criterios técnicos. Esto incluye la
                    limpieza, transformación y análisis de datos, además de su
                    correcta interpretación y visualización mediante
                    herramientas gráficas. Al finalizar, el aprendiz estará
                    capacitado para implementar estrategias basadas en datos,
                    optimizando recursos, incrementando la productividad y
                    reduciendo los impactos ambientales negativos.
                  </p>
                </div>
              </div>
            </div>
            <p class="mt-3 mb-0">
              Este componente no solo promueve habilidades técnicas esenciales
              en el manejo de datos, sino que también fomenta un enfoque crítico
              y reflexivo sobre el papel de la tecnología en la agricultura. En
              un contexto donde la sostenibilidad es primordial, los aprendices
              estarán preparados para enfrentar los desafíos del sector con
              soluciones innovadoras y fundamentadas en datos.
            </p>
          </div>
        </div>
        <figure class="mt-4" data-aos="zoom-in-up" data-aos-duration="500">
          <div class="video">
            <iframe
              width="560"
              height="315"
              src="https://www.youtube.com/embed/13fgZu5qKvU?si=xHLN89mtyVvS8fJb"
              title="YouTube video player"
              frameborder="0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
              allowfullscreen="allowfullscreen"
            ></iframe>
          </div>
        </figure>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
