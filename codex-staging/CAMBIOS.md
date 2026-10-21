# Cambios · Escrituras legales

<!-- Generado al derivar el paquete desde cambios.yaml. No editar a mano. -->

Qué cambia para quien usa este saber, versión por versión. Lo que corre de verdad el servicio lo dice su herramienta `ver_cambios`; esto es la copia del paquete.

## v0.1.4 · 2026-10-21

La forma de la ficha trae ahora todos sus campos, cada uno con cómo se escribe, sacados del esquema y no de una lista escrita a mano. Aparecen los que la segunda prueba tuvo que adivinar: la inscripción de cada gravamen, su acreedor, el número, banco y beneficiario del vale vista, el plazo para devolverlo y si el banco trae su minuta. La declaración DFL-2 toma el documento de la evidencia antecedente_dfl2, la misma que se revisa, en vez de pedirlo en un campo aparte que nadie encontraba.

- Herramientas: `ensamblar_borrador`, `evaluar_ficha`, `listar_cobertura`, `obtener_criterios`, `preguntas_abiertas`, `preparar_ficha`, `ver_cambios`
- Skills: `empezar-aqui`, `redactar-escritura`
- Datos: sin manifiesto

## v0.1.3 · 2026-10-21

La ficha del caso dice cómo se escribe cada dato que la prueba en staging tuvo que adivinar: la cuota como texto con su signo («100%»), fojas, número y año como números sin puntos, el número del plano y de cada unidad como texto, el rol de avalúo en cada unidad, el plazo de entrega cuando la entrega es a la inscripción y qué pasa con un saldo a plazo. El esqueleto trae una unidad con su rol, y un dato mal escrito se señala con el formato correcto.

- Herramientas: `ensamblar_borrador`, `evaluar_ficha`, `listar_cobertura`, `obtener_criterios`, `preguntas_abiertas`, `preparar_ficha`, `ver_cambios`
- Skills: `empezar-aqui`, `redactar-escritura`
- Datos: sin manifiesto

## v0.1.2 · 2026-10-21

Corrige textos de la biblioteca que encontró la prueba en staging. Un departamento solo se escribe en singular («dicha unidad», «entregar el inmueble») y no como si fueran varias unidades. «Precio pagado íntegro» sólo se propone si todo el precio se paga al firmar; con saldo a plazo ya no choca con la renuncia a la acción resolutoria, y la renuncia con saldo financiado por el vendedor queda como pregunta abierta (PA-12). La declaración sobre deudores de alimentos ya no afirma una consulta «con esta fecha» que el saber no conoce. Con varias unidades, la que no trae rol queda marcada [FALTA] en vez de desaparecer de la frase.

- Herramientas: `ensamblar_borrador`, `evaluar_ficha`, `listar_cobertura`, `obtener_criterios`, `preguntas_abiertas`, `preparar_ficha`, `ver_cambios`
- Skills: `empezar-aqui`, `redactar-escritura`
- Datos: sin manifiesto

## v0.1.1 · 2026-10-21

Corrige fallas de fondo que encontró la primera prueba en staging. Los montos de cada forma de pago se escriben en la moneda del precio (una partida en pesos salía en Unidades de Fomento). Cuando el abogado decide redactar una partida en un espacio libre, el borrador la muestra marcada y el expediente la registra; antes desaparecía. Ninguna partida, persona o gravamen puede quedar fuera del borrador sin una pregunta al abogado. Un dato desconocido ya no cuenta como distinto de un valor (se advertía de un compareciente extranjero sin saber la nacionalidad). Con un solo departamento sin rol propio se usa el rol del inmueble. Las marcas [FALTA] ya no se cortan y una cuota mal escrita no interrumpe la revisión de la ficha.

- Herramientas: `ensamblar_borrador`, `evaluar_ficha`, `listar_cobertura`, `obtener_criterios`, `preguntas_abiertas`, `preparar_ficha`, `ver_cambios`
- Skills: `empezar-aqui`, `redactar-escritura`
- Datos: sin manifiesto

## Línea base · v0.1.0 · 2026-10-21

Primera versión del saber. Arma el borrador de una escritura de compraventa de inmueble urbano entre personas naturales, al contado o con mutuo hipotecario, a partir de la ficha del caso: exige los antecedentes que pide la inscripción, elige las cláusulas con criterios de una biblioteca y le pregunta al abogado lo que no puede decidir. Entrega la minuta con un expediente que dice por qué va cada párrafo y deja en blanco, marcado, lo que no sabe. Advertencia de esta versión: la biblioteca es una semilla sintética, sin validar por abogados; sirve para mostrar y revisar, no para firmar.

- Herramientas: `ensamblar_borrador`, `evaluar_ficha`, `listar_cobertura`, `obtener_criterios`, `preguntas_abiertas`, `preparar_ficha`, `ver_cambios`
- Skills: `empezar-aqui`, `redactar-escritura`
- Datos: sin manifiesto

Antes de v0.1.0 no hay registro de cambios.
