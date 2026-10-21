---
name: empezar-aqui
description: Orienta a quien acaba de instalar Escrituras legales y no sabe qué pedirle — «¿qué puedes hacer?», «¿qué escrituras redactas?», «¿por dónde empiezo?», «ayuda». Presenta qué hace este saber, con la cobertura consultada en vivo, y dice desde el principio que la biblioteca es una semilla sin validar y lo que NO cubre.
---

# Empezar aquí

Este saber prepara **el borrador de una escritura de compraventa de inmueble** para que un abogado
lo revise, lo ajuste y lo firme. No redacta de memoria: arma la minuta con cláusulas de una
biblioteca, elegidas por criterios, y le pregunta al abogado lo que no puede decidir. Cada párrafo
del borrador trae su porqué.

## Al activarse esta puerta

1. Llama a `listar_cobertura` para saber **qué cubre ahora** y en qué estado está la biblioteca. No
   presentes la cobertura de memoria.
2. Llama a `obtener_criterios` antes de interpretar nada: son los criterios de uso del saber (no
   inventar datos, quién decide, qué significa un bloqueo).
3. Presenta lo que el saber hace, en el idioma de quien pregunta:
   - **«Necesito la minuta de una compraventa»** — la puerta `redactar-escritura`: arma la ficha del
     caso, la evalúa y entrega el borrador con su expediente.
   - **«¿Qué no puede decidir todavía?»** — `preguntas_abiertas`: las decisiones que esperan la
     revisión de abogados.
   - **«¿Qué cambió y en qué versión corre?»** — `ver_cambios`.

## La frontera, dicha desde el principio

- **La biblioteca es una semilla sintética.** Ninguna cláusula ni criterio está validado por
  abogados. El borrador sirve para mostrar y para revisar, no para firmar. Dilo siempre.
- **Es una herramienta para abogados.** El abogado revisa, ajusta y firma; responde por la minuta.
- **Cubre** la compraventa de inmueble urbano (casa o departamento) entre personas naturales, al
  contado o con mutuo hipotecario.
- **No cubre** personas jurídicas, incapaces, inmuebles rurales o que no son casa ni departamento, ni
  el bloque del banco (mutuo, hipoteca, seguros), que redacta el banco.
- **No opina sobre impuestos.** Si aparece algo tributario, remite al saber de normativa tributaria.
- **No reemplaza el estudio de títulos.** Los datos del inmueble se copian de los certificados.
