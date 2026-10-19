<script lang="ts">
  import './sobrenosotros.css';
  import { assetUrl } from '../../../../assets';
  // Props o lógica del componente
</script>

<section id="sobre-nosotros" class="fondo-secundario sobre-seccion">

  <div class="cuadricula contenedor-seccion">
    <div class="col-span-5">
      <!-- Aquí va la imagen solicitada -->
      <div class="contenedor-imagen">
        <img src={assetUrl("imagenes/sobrenosotros-imagen.webp")} alt="Sobre nosotros" class="imagen-estudio">
      </div>
    </div>
<div class="col-span-7">
      <div class="sobre-nosotros-textos">
        <!-- Redacta aquí tu propio título con h2 y al menos dos párrafos con p -->
      <h2>Sobre nosotros</h2>
      <p>Probar Exotik Mass es romper la rutina con repostería creativa, diferente y deliciosa. Cada producto está diseñado para sorprender tus sentidos y hacer cualquier momento más divertido.</p>
      <p class="descripcion">Te ofrecemos calidad y frescura superior directo a tu puerta con solo un clic. Es la opción perfecta para regalar, compartir o darte un gusto único e innovador</p>
      </div>
    </div>
  </div>
</section>
