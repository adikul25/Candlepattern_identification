

# Identificación de patrones de velas japonesas con TA-Lib y fórmulas personalizadas

Este repositorio contiene código y recursos para identificar patrones de velas japonesas utilizando TA-Lib y fórmulas definidas de manera personalizada. El cuaderno de Jupyter proporcionado demuestra cómo detectar patrones comunes como Doji, Hammer, Morning Star, Engulfing y Harami, utilizando tanto funciones prediseñadas de TA-Lib como lógica personalizada.

## Características

- **Integración con TA-Lib**: Utiliza la potente biblioteca TA-Lib para identificar patrones comunes de velas japonesas.
- **Fórmulas de patrones personalizadas**: Implementa lógica personalizada para detectar patrones basados en condiciones específicas, lo que permite un análisis más ajustado.
- **Manejo de datos**: Procesa y visualiza datos de acciones para identificar tendencias y patrones en períodos de tiempo seleccionados.
- **Resaltado de patrones**: Resalta automáticamente los patrones detectados para facilitar el análisis.

## Instalación

Para ejecutar el cuaderno y utilizar el código, es necesario tener Python instalado junto con las bibliotecas requeridas.

## Uso

1. Carga de datos de acciones
Carga tus datos de acciones en un DataFrame de Pandas. El cuaderno demuestra el uso de precios históricos de acciones con columnas como Open, High, Low, Close, Volume, etc.

2. Detección de patrones

### Patrones de TA-Lib
Utiliza las funciones integradas de TA-Lib para detectar patrones como Doji, Engulfing, etc.

### Patrones personalizados
Implementa y aplica fórmulas personalizadas para detectar patrones específicos, como un patrón Hammer bajo ciertas condiciones.

## 3. Visualización
Visualiza los resultados utilizando Matplotlib para comprender mejor dónde ocurren los patrones en tus datos.

## 4. Análisis
Analiza la frecuencia y distribución de los patrones para informar tus estrategias de trading.
