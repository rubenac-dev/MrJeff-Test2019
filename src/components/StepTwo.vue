<template>
  <div class="step">
    <div class="exercise">
      <h1>Task 2a - Styles 馃帹</h1>
      <p>El equipo de dise帽o ha pedido algunos cambios en el componente. 
        Quieren probar si los usuarios lo entienden mejor mostrando los nombres de los pasos 
        en la parte superior en vez de en la inferior.</p>
      <p><strong>Requisitos:</strong></p>
      <ul>
        <li>Modifica los estilos del componente para que el nombre de cada paso se muestre sobre 茅l, en vez de debajo.
          El componente debe ser configurable para soportar ambas variantes, tanto la original como la nueva.</li>
      </ul>
    </div>
    <div class="exercise">
      <h1>Task 2b - Responsiveness 馃摫</h1>
      <p>El componente va a empezar a usarse en m贸viles (&lt;768px), donde presenta algunos problemas.</p>
      <p><strong>Requisitos:</strong></p>
      <ul>
        <li>Haz que en disposivos m贸viles s贸lo se muestre el nombre del paso activo.</li>
      </ul>
      <p><strong>Bonus:</strong></p>
      <ul>
        <li>En los anchos de pantalla m谩s peque帽os, o si los nombres de los pasos son un poco largos, surge otro problema de visualizaci贸n. Prop贸n alguna soluci贸n sencilla pero efectiva.</li>
        <li>Implementa las tareas con un enfoque mobile-first y elementos de accesibilidad.</li>
      </ul>
    </div>
    <div class="info">Avanza al siguiente paso para continuar con la prueba!</div>
  </div>
</template>

<script>
export default {
  name: 'step-two',

  props: {
    currentStep: {
      type: Number
    }
  }
}
</script>
