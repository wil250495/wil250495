<!DOCTYPE html>
<html>
<head>
<style>
  /* Estilos para los nodos */
  ul {
    list-style-type: none;
    padding: 0;
  }
  
  li {
    margin-left: 20px;
    position: relative;
  }
  
  li::before {
    content: "";
    position: absolute;
    left: -10px;
    top: 5px;
    border-left: 2px solid black;
    height: 10px;
  }
  
  /* Estilos para el título */
  h1 {
    text-align: center;
  }
</style>
</head>
<body>
  <h1>Las Fuerzas del Mercado</h1>
  <ul>
    <li>Oferta y Demanda
      <ul>
        <li>Conceptos esenciales de la economía de mercado</li>
        <li>Determinan cantidad y precios de bienes</li>
      </ul>
    </li>
    <li>Mercados y Competencia
      <ul>
        <li>Definición de mercado</li>
        <li>Compradores y vendedores</li>
      </ul>
    </li>
    <li>Mercado Competitivo
      <ul>
        <li>Muchos compradores y vendedores</li>
        <li>Impacto insignificante en precio de mercado</li>
      </ul>
    </li>
    <!-- Continuar con más elementos -->
  </ul>
</body>
</html>
