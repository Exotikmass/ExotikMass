<script lang="ts">
  import './heroe.css';
  import { assetUrl } from '../../../../assets';
  // Props o lógica del componente
</script>

<section class="fondo-principal seccion-heroe" id="heroe" aria-labelledby="heroe-titulo">
    <div class="cuadricula contenedor-seccion contenedor-heroe">
      <div class="col-span-5 contenedor-texto">
        <span class="heroe-etiqueta">Repostería creativa · Exotik Mass</span>
        <h1 id="heroe-titulo">Un toque exótico.<br>Un bocado <em>inolvidable.</em></h1>
        <p>Masas suaves, chocolate y combinaciones que sorprenden. Descubre nuestra repostería para compartir, regalar o darte ese gusto que alegra el día.</p>
        <div class="contenedor-boton">
          <a class="boton boton-secundario" href="#catalogo">Explorar productos ↗</a>
          <a class="boton boton-blanco" href="#contacto">Contáctanos</a>
        </div>
        <div class="heroe-nota">Hecho para disfrutar · Para regalar y compartir</div>
      </div>
      <div class="col-span-7 heroe-imagen-contenedor">
        <img src={assetUrl("imagenes/heroe-imagen.webp")} alt="Repostería de Exotik Mass con cobertura de chocolate" class="heroe-imagen" fetchpriority="high">
        <span class="heroe-sello">La creatividad se convierte en sabor.</span>
      </div>
    </div>
  </section>
