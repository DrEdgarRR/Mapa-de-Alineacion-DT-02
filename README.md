# Mapa de Alineación de Competencias y Cursos (DT-02)

Aplicación web para que el profesorado de la **Pontificia Universidad Católica de Puerto Rico** alinee los objetivos de su curso con las 11 competencias institucionales (RAI) y genere el **Formulario DT-02 modificado** de la Oficina de Avalúo Institucional.

## Cómo se usa

1. Escriba la información del curso: año académico, recinto, colegio, programa y curso.
2. Cargue el prontuario en Word (`.docx`) o PDF, o pegue el texto de los objetivos.
3. Revise los objetivos detectados. La aplicación toma solo los **objetivos terminales (T1, T2…)** y **capacitantes (C1a, C1b…)** de la sección de objetivos.
4. Pulse **Alinear objetivos**.
5. Revise la propuesta. En cada RAI aparecen hasta 5 objetivos, en orden de mayor a menor alineación. Puede ajustar el nivel, desmarcar o añadir objetivos y marcar **X** o **A**.
6. Descargue el **DT-02 en Word**. El documento se genera sobre la plantilla institucional.

Para trabajar con otro prontuario, pulse **↺ Comenzar de nuevo**.

## Privacidad

El prontuario se procesa completamente en el navegador del usuario. No se envía ni se guarda en ningún servidor.

## Cómo funciona la alineación

Cada objetivo recibe una puntuación de 0 a 100 por competencia:

| Nivel | Puntuación |
|---|---|
| Fuerte | 75–100 |
| Moderada | 55–74 |
| Débil | 35–54 |

Por debajo de 35 no se considera alineación. La puntuación se calcula a partir de los verbos de la taxonomía de Bloom y los términos clave de cada RAI. Es una propuesta: la decisión final corresponde al profesor y al comité de avalúo.

## Archivos

- `index.html`: la aplicación completa, en un solo archivo. Incluye la plantilla institucional del DT-02.

Desarrollado para el Colegio de Administración de Empresas, PUCPR.
