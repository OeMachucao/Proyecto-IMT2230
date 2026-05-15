### LSA entre Tecnologia Militar y Ética: El caso de Palantir en el Conflico de Gaca

Este proyecto busca realizar un Análisis Semántico Latente (LSA) utilizando la Descomposición en Valores Singulares (SVD) sobre un corpus de documentos relacionados con la empresa Palantir Technologies y su rol en el conflicto de Gaza. El objetivo es descubrir la estructura latente y las asociaciones semánticas entre el discurso corporativo, el periodístico y el de derechos humanos.

## Descripción del Proyecto
El corpus seleccionado consiste en una colección de **51 documentos** (hasta el momento) que analizan la participación de **Palantir Technologies** en el conflicto de Gaza. La investigación se sitúa en la intersección de:
*  **Tecnología de vanguardia**
*  **Defensa nacional**
*  **Implicaciones éticas en Derechos Humanos**

## Paso 1: Definir y Construir el Corpus
Para que el algoritmo de **SVD** pueda extraer patrones significativos, hemos construido una "biblioteca de datos" diversa y curada manualmente, garantizando que el análisis no se contamine con información irrelevante.

### Los Tres Pilares Estratégicos que escogimos:
1. **Pilar 1: Visión Corporativa** 
   - **Fuentes:** Secciones de "News" o "Investors" de Palantir.
   - **Enfoque:** Eficiencia, defensa, vigilancia, IA y resultados financieros.
2. **Pilar 2: Visión Crítica / Ética** 
   - **Fuentes:** Informes de Amnistía Internacional, Human Rights Watch y medios críticos como Al Jazeera.
   - **Enfoque:** Derechos humanos, violaciones, ética y derecho internacional.
3. **Pilar 3: Visión Periodística** 
   - **Fuentes:** Reuters, AP, The Guardian y BBC.
   - **Enfoque:** Contexto fáctico y hechos que conectan ambos mundos.

---

##  Herramientas y Configuración
Para asegurar la reproducibilidad del proyecto, se utiliza **Python 3.13** y un pipeline de extracción automatizado.

### Librerías Necesarias:
Es indispensable instalar las siguientes librerías para procesar las fuentes:

```bash
# Instalación de librerías principales
pip install newspaper3k
