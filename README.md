# fuzzy-logic-in-Matlab-fuzzy-washing-machine-model
Para la realización del sistema Fuzzy Lavadora se utilizo la herramienta Fuzzy Logic ToolBox de MATLAB (Math Works Inc) permitiendo desarrollar el sistema de inferencia difusa (FIS); Funciones de membresía (MF); Reglas difusas, visualización de reglas y superficie para visualización grafica en 3D del sistema.
Construcción de sistema
Sistema de inferencia difusa: Se utilizó el editor FIS para configurar el sistema en general (rangos y variables) está conformado por los siguientes: 
Variables de Entradas:
ROPA
SUCIEDAD
Variables de Salida: 
REVOLUCIONES
AGUA
DETERGENTE
SUAVIZANTE
Conjuntos difusas y Variables Lingüísticas:
Entradas
Ropa: Poca Ropa- Mediana Ropa – Mucha Ropa
Suciedad: Poca Suciedad- Mediana Suciedad- Mucha Suciedad
Salidas
1. Revoluciones: Lenta- Mediana- Rápida
2. Agua: Poca- Mediana- Mucha
3. Detergente: Poco- Medio- Mucho
4. Suavizante: Poco- Medio- Mucho
Definición de Funciones de Pertenencia
     Para cada valor lingüístico de las variables se define una función de pertenencia que indique el grado en que la variable x está incluida en los conceptos representados por las variables lingüísticas.
Variables de entradas: 
Ropa: Rango 1-5 kg. Función tipo: Gaussmf
Poca Ropa: 0-3-1 - Mediana Ropa: 0-3-3.– Mucha Ropa: 0-3-3.
Suciedad: Rango: 0-10 %. Función tipo: Trapmf.
 Poca Suciedad: 0-0.1-3 - Mediana Suciedad: 3-4-6-7- Mucha Suciedad: 7-8-10-10.
Variables de salida: 
Revoluciones: Rango: 0-100 RPM
Lenta: 0-15-30 – Mediana: 30-45-60 – Rápida: 60-80-100
Agua: Rango: 0.100 % 
Poca: 0-15-30 – Mediana: 30-45-60 – Mucha: 60-80-100
Detergente: Rango: 0-10 %
Poco: 0-1.5-3 – Medio: 3-4.5-6 – Mucho: 6-8-10
Suavizante: Rango: 0-10 %
Poco: 0-1.5-3 – Medio: 3-4.5-6 – Mucho: 6-8-10
Reglas difusas: Para definir las reglas de control se utilizó el editor de reglas combinando las entradas y salidas obteniendo la regla en un contexto tipo If-Then de condiciones y acciones.
Mecanismo de inferencia: Se empleó el AND lógico como el mínimo entre estas combinando los resultados mediante el OR lógico como máximo. 
Defusificacion: Se empleó el método de Mandani para obtener la salida mediante el método del Centroide.

