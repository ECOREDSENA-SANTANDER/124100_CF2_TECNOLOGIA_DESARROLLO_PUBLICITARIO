<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
      .titulo-principal.color-acento-botones
        .titulo-principal__numero
          span 2
        h1 Segmentación del mercado

      .row.justify-content-center.align-items-center.mb-5(data-aos="fade-left")
        .col-lg-4
          img(src="@/assets/curso/temas/tema2/img01.png", alt="")
        .col-lg-8 
          p De acuerdo con el concepto más básico, el segmentar se refiere a “Cortar o partir algo en segmentos” (RAE, 2020). En el caso del marketing, consiste en dividir un mercado en varios grupos de individuos con características similares. La segmentación, es una herramienta que permite a los estrategas del mercadeo y la comunicación, conocer en detalle a grupos objetivo de individuos que presentan atributos particulares para el consumo de productos o el acceso a servicios específicos. 
          .cajon.color-secundario.p-4.mb-4
            p #[b Por su parte, Fernández (2009), afirma:]
            p #[b “La segmentación de mercados es una herramienta de la mercadotecnia que requiere del apoyo de disciplinas como la estadística, la psicología, la sociología y la geografía, entre otras y es a partir de una serie de variables que la segmentación determina las características que hacen único a un grupo de mercado”.]
        
        .py-4
        figure.mb-5
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
          figcaption Video: Leyenda del video

        p Para el diseño de las estrategias de marketing, el mercado se puede segmentar en dos grandes grupos: consumidores e industrial; estos, de igual forma, deben ser divididos en nichos más pequeños. El primero de ellos, como su nombre lo indica, el grupo de consumidores: tiene que ver con las personas que son usuarias de los servicios o que consumen los productos. El segundo: se refiere a las empresas que conforman nichos de mercado industriales. 

      Separador
      #t_2_1.titulo-segundo.color-acento-contenido
        h2 2.1 Concepto de mercado


</template>

<script>
export default {
  name: 'Tema2',
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
