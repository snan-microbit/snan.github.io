<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculadora Solo HTML (Estática)</title>
</head>
<body>

    <!-- Contenedor principal de la calculadora -->
    <div class="calculadora-estatica" style="
        display: grid;
        grid-template-columns: repeat(4, 60px);
        gap: 10px;
        padding: 15px;
        background-color: #333;
        border-radius: 10px;
        width: fit-content;
        margin: 20px;
    ">
        
        <!-- Pantalla de visualización (simulada con un input deshabilitado) -->
        <input type="text" value="0" disabled style="
            grid-column: span 4;
            height: 40px;
            background-color: #eee;
            border: none;
            border-radius: 5px;
            text-align: right;
            padding: 0 10px;
            font-size: 1.5em;
            box-sizing: border-box;
        ">

        <!-- Botones (etiquetas div para simular botones sin funcionalidad) -->
        <div style="/* Estilo botón */ height: 50px; background-color: #e74c3c; color: white; display: flex; justify-content: center; align-items: center; border-radius: 5px; cursor: pointer;">C</div>
        <div style="/* Estilo botón */ height: 50px; background-color: #f7941b; color: white; display: flex; justify-content: center; align-items: center; border-radius: 5px; cursor: pointer;">/</div>
        <div style="/* Estilo botón */ height: 50px; background-color: #f7941b; color: white; display: flex; justify-content: center; align-items: center; border-radius: 5px; cursor: pointer;">*</div>
        <div style="/* Estilo botón */ height: 50px; background-color: #f7941b; color: white; display: flex; justify-content: center; align-items: center; border-radius: 5px; cursor: pointer;">-</div>
        
        <div style="/* Estilo botón */ height: 50px; background-color: #fff; display: flex; justify-content: center; align-items: center; border-radius: 5px; cursor: pointer;">7</div>
        <div style="/* Estilo botón */ height: 50px; background-color: #fff; display: flex; justify-content: center; align-items: center; border-radius: 5px; cursor: pointer;">8</div>
        <div style="/* Estilo botón */ height: 50px; background-color: #fff; display: flex; justify-content: center; align-items: center; border-radius: 5px; cursor: pointer;">9</div>
        <div style="/* Estilo botón */ height: 50px; background-color: #f7941b; color: white; display: flex; justify-content: center; align-items: center; border-radius: 5px; cursor: pointer;">+</div>

        <div style="/* Estilo botón */ height: 50px; background-color: #fff; display: flex; justify-content: center; align-items: center; border-radius: 5px; cursor: pointer;">4</div>
        <div style="/* Estilo botón */ height: 50px; background-color: #fff; display: flex; justify-content: center; align-items: center; border-radius: 5px; cursor: pointer;">5</div>
        <div style="/* Estilo botón */ height: 50px; background-color: #fff; display: flex; justify-content: center; align-items: center; border-radius: 5px; cursor: pointer;">6</div>
        
        <!-- Botón de igual que ocupa dos filas -->
        <div style="/* Estilo botón */ height: 110px; background-color: #2ecc71; color: white; display: flex; justify-content: center; align-items: center; border-radius: 5px; cursor: pointer; grid-row: span 2;">=</div>

        <div style="/* Estilo botón */ height: 50px; background-color: #fff; display: flex; justify-content: center; align-items: center; border-radius: 5px; cursor: pointer;">1</div>
        <div style="/* Estilo botón */ height: 50px; background-color: #fff; display: flex; justify-content: center; align-items: center; border-radius: 5px; cursor: pointer;">2</div>
        <div style="/* Estilo botón */ height: 50px; background-color: #fff; display: flex; justify-content: center; align-items: center; border-radius: 5px; cursor: pointer;">3</div>

        <div style="/* Estilo botón */ height: 50px; background-color: #fff; grid-column: span 2; display: flex; justify-content: center; align-items: center; border-radius: 5px; cursor: pointer;">0</div>
        <div style="/* Estilo botón */ height: 50px; background-color: #fff; display: flex; justify-content: center; align-items: center; border-radius: 5px; cursor: pointer;">.</div>

    </div>

</body>
</html>
