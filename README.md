# CONTENEDORES:FILAS Y COLUMNAS
ACTVIDAD 1
CREAR 4 COLUMNAS EN BOOTSTRAP. APLICAR DIFERENTES COLORES
ACTIVIDAD 2
CREAR 2 COLUMNAS Y 2 FILAS. USAR DIFERENTES COLORES PARA CADA UNA DE ELLAS
ACTIVIDAD 3
CREAR 3 FILAS, LA PRIMERA CONTENDRA 2 COLUMNAS, LA SEGUNDA 3 COLUMNAS Y LA TERCERA 2 COLUMNAS

1:
<div class="container text-center">
  <div class="row">
    <div class="col-3 bg-primary text-white p-3">Columna 1</div>
    <div class="col-3 bg-success text-white p-3">Columna 2</div>
    <div class="col-3 bg-danger text-white p-3">Columna 3</div>
    <div class="col-3 bg-warning text-dark p-3">Columna 4</div>
  </div>
</div>

2:
<div class="row">
  <div class="col-6 bg-danger text-white p-4">Rojo (Danger)</div>
  <div class="col-6 bg-primary text-white p-4">Azul (Primary)</div>
</div>
<div class="row">
  <div class="col-6 bg-success text-white p-4">Verde (Success)</div>
  <div class="col-6 bg-warning text-dark p-4">Amarillo (Warning)</div>
</div>

3:
<div class="container text-center">
  <div class="row mb-2">
    <div class="col-6 bg-primary p-3 border">F1 - C1</div>
    <div class="col-6 bg-primary p-3 border">F1 - C2</div>
  </div>

  <div class="row mb-2">
    <div class="col-4 bg-success p-3 border">F2 - C1</div>
    <div class="col-4 bg-success p-3 border">F2 - C2</div>
    <div class="col-4 bg-success p-3 border">F2 - C3</div>
  </div>

  <div class="row">
    <div class="col-6 bg-danger p-3 border text-white">F3 - C1</div>
    <div class="col-6 bg-danger p-3 border text-white">F3 - C2</div>
  </div>
</div>
