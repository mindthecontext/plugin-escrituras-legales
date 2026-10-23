# Cambios · Escrituras legales

<!-- Generado al derivar el paquete desde cambios.yaml. No editar a mano. -->

Qué cambia para quien usa este saber, versión por versión. Lo que corre de verdad el servicio lo dice su herramienta `ver_cambios`; esto es la copia del paquete.

## v0.1.16 · 2026-10-23

Con crédito hipotecario, si la ficha no dice si el banco trae su propia minuta, el saber pregunta si el banco acepta la compraventa redactada por el abogado, en vez de suponer que sí. Sólo deja de preguntar cuando la ficha dice que el banco no trae minuta.

- Herramientas: `ensamblar_borrador`, `evaluar_ficha`, `explorador_indice`, `explorador_seccion`, `explorar_biblioteca`, `listar_cobertura`, `obtener_criterios`, `preguntas_abiertas`, `preparar_ficha`, `registrar_revision`, `ver_cambios`
- Skills: `empezar-aqui`, `redactar-escritura`
- Datos: sin manifiesto

## v0.1.15 · 2026-10-23

Ajustes del explorador tras recorrerlo completo: a pantalla completa el final de la página ya no queda bajo la caja de mensaje de Claude; el botón de pantalla completa lleva su ícono; si una revisión no se guarda por un corte de conexión, el aviso lo dice en castellano y la revisión queda para reintentarla; el selector de sección se ve al recorrerlo con el teclado, y en la sección de formas los valores de la ficha ya no se cortan a mitad de palabra.

- Herramientas: `ensamblar_borrador`, `evaluar_ficha`, `explorador_indice`, `explorador_seccion`, `explorar_biblioteca`, `listar_cobertura`, `obtener_criterios`, `preguntas_abiertas`, `preparar_ficha`, `registrar_revision`, `ver_cambios`
- Skills: `empezar-aqui`, `redactar-escritura`
- Datos: sin manifiesto

## v0.1.14 · 2026-10-23

El explorador ofrece un botón «Pantalla completa» cuando la aplicación de Claude lo permite: la biblioteca se recorre con la estructura fija al costado y las versiones lado a lado, y «Volver al chat» la deja como estaba. Si la aplicación no lo permite, el botón no aparece.

- Herramientas: `ensamblar_borrador`, `evaluar_ficha`, `explorador_indice`, `explorador_seccion`, `explorar_biblioteca`, `listar_cobertura`, `obtener_criterios`, `preguntas_abiertas`, `preparar_ficha`, `registrar_revision`, `ver_cambios`
- Skills: `empezar-aqui`, `redactar-escritura`
- Datos: sin manifiesto

## v0.1.13 · 2026-10-23

En el explorador, cuando la página es angosta —como en el chat de Claude—, la estructura de la escritura se elige en un selector compacto y el detalle de la sección aparece justo debajo, sin tener que bajar. Cada sección termina con un botón para pasar a la siguiente.

- Herramientas: `ensamblar_borrador`, `evaluar_ficha`, `explorador_indice`, `explorador_seccion`, `explorar_biblioteca`, `listar_cobertura`, `obtener_criterios`, `preguntas_abiertas`, `preparar_ficha`, `registrar_revision`, `ver_cambios`
- Skills: `empezar-aqui`, `redactar-escritura`
- Datos: sin manifiesto

## v0.1.12 · 2026-10-23

Cómo se escribe cada dato dentro de una cláusula —el estado civil, el régimen, el nombre de un gravamen, la cita de una inscripción, un monto, una fecha, la numeración de las cláusulas— pasa a la biblioteca, donde el abogado validador lo ve y lo revisa en el explorador, en una sección nueva. Se corrigen dos frases que salían mal: el mandato para rectificar dice «actuando conjuntamente» o «indistintamente», y una adjudicación dice «en la partición de la herencia» en vez de «en particion herencia».

- Herramientas: `ensamblar_borrador`, `evaluar_ficha`, `explorador_indice`, `explorador_seccion`, `explorar_biblioteca`, `listar_cobertura`, `obtener_criterios`, `preguntas_abiertas`, `preparar_ficha`, `registrar_revision`, `ver_cambios`
- Skills: `empezar-aqui`, `redactar-escritura`
- Datos: sin manifiesto

## v0.1.11 · 2026-10-23

Agrega el explorador de la biblioteca, para que un abogado con rol de validador la revise: abre una página dentro de Claude con la estructura de la escritura, cada cláusula con sus versiones, los criterios que las eligen, los antecedentes indispensables y las preguntas abiertas, y deja guardada su revisión de cada pieza, atada al texto que revisó. Quien sólo usa el saber para redactar no lo ve ni puede abrirlo: el rol lo da MindTheContext. Se retira la sonda de página. No cambia cómo se redacta.

- Herramientas: `ensamblar_borrador`, `evaluar_ficha`, `explorador_indice`, `explorador_seccion`, `explorar_biblioteca`, `listar_cobertura`, `obtener_criterios`, `preguntas_abiertas`, `preparar_ficha`, `registrar_revision`, `ver_cambios` · aparece `explorador_indice`, `explorador_seccion`, `explorar_biblioteca`, `registrar_revision` · desaparece `sonda_de_pagina`, `sonda_eco`
- Skills: `empezar-aqui`, `redactar-escritura`
- Datos: sin manifiesto

## v0.1.10 · 2026-10-23

La sonda de página le avisa a la aplicación qué alto tiene, para que se vea completa. Sigue siendo un diagnóstico del equipo, sólo en staging.

- Herramientas: `ensamblar_borrador`, `evaluar_ficha`, `listar_cobertura`, `obtener_criterios`, `preguntas_abiertas`, `preparar_ficha`, `sonda_de_pagina`, `sonda_eco`, `ver_cambios`
- Skills: `empezar-aqui`, `redactar-escritura`
- Datos: sin manifiesto

## v0.1.9 · 2026-10-23

La sonda de página muestra qué aplicación la abre y si esa aplicación declara que puede pasar las llamadas de la página al servidor. Sigue siendo un diagnóstico del equipo, sólo en staging.

- Herramientas: `ensamblar_borrador`, `evaluar_ficha`, `listar_cobertura`, `obtener_criterios`, `preguntas_abiertas`, `preparar_ficha`, `sonda_de_pagina`, `sonda_eco`, `ver_cambios`
- Skills: `empezar-aqui`, `redactar-escritura`
- Datos: sin manifiesto

## v0.1.8 · 2026-10-23

Agrega una herramienta de diagnóstico para el equipo, la sonda de página: abre una página dentro de Claude y comprueba que las llamadas hechas desde ella llegan con la identidad de quien la usa. Es temporal y no cambia cómo se redacta: prepara el explorador de la biblioteca para validarla.

- Herramientas: `ensamblar_borrador`, `evaluar_ficha`, `listar_cobertura`, `obtener_criterios`, `preguntas_abiertas`, `preparar_ficha`, `sonda_de_pagina`, `sonda_eco`, `ver_cambios` · aparece `sonda_de_pagina`, `sonda_eco`
- Skills: `empezar-aqui`, `redactar-escritura`
- Datos: sin manifiesto

## v0.1.7 · 2026-10-21

Corrige lo que encontró una lectura completa de los borradores. La venta ya no remite a una cláusula de alzamiento cuando no hay nada que alzar. Con crédito, el pago de la deuda que se alza es una instrucción de la vendedora sobre lo que el banco le entrega, y ya no contradice la cláusula del precio. El cónyuge que autoriza comparece siempre, con el género que corresponde. La retención por deuda de alimentos es una instrucción al notario, no un pago ya hecho. Un gravamen que la biblioteca no sabe alzar (una prohibición del SERVIU) sale como espacio libre marcado y no como una deuda. Los avisos tributarios dependen del caso.

- Herramientas: `ensamblar_borrador`, `evaluar_ficha`, `listar_cobertura`, `obtener_criterios`, `preguntas_abiertas`, `preparar_ficha`, `ver_cambios`
- Skills: `empezar-aqui`, `redactar-escritura`
- Datos: sin manifiesto

## v0.1.6 · 2026-10-21

Corrige textos de la biblioteca que encontró la prueba con crédito hipotecario. Cuando la compra se paga con crédito y el vendedor tiene una hipoteca que se alza al firmar, el saber pregunta al abogado de dónde sale el pago de esa deuda (del préstamo del banco del comprador, de sumas en custodia o con el acreedor compareciendo), en vez de suponer fondos en custodia que no existen. El vale vista ya no remite a instrucciones «por separado» que luego se escriben en la escritura. Cada rol de avalúo va con su unidad, y los avisos sobre roles ya no afirman lo que la ficha no dice.

- Herramientas: `ensamblar_borrador`, `evaluar_ficha`, `listar_cobertura`, `obtener_criterios`, `preguntas_abiertas`, `preparar_ficha`, `ver_cambios`
- Skills: `empezar-aqui`, `redactar-escritura`
- Datos: sin manifiesto

## v0.1.5 · 2026-10-21

Corrige fallas del motor que encontró la prueba con crédito hipotecario. Con varios compradores, cada uno aparece con su cuota («doña A, un 50%, y don B, un 50%») en vez de un porcentaje suelto. La hipoteca y la prohibición de un mismo acreedor se alzan en un solo párrafo, con una sola instrucción de pago. «La parte compradora» se designa una vez para todos los compradores. Con el precio en UF y sin su equivalencia en pesos, la pregunta sólo ofrece versiones en UF, cada una con su riesgo. La lista de faltantes coincide con las marcas del borrador.

- Herramientas: `ensamblar_borrador`, `evaluar_ficha`, `listar_cobertura`, `obtener_criterios`, `preguntas_abiertas`, `preparar_ficha`, `ver_cambios`
- Skills: `empezar-aqui`, `redactar-escritura`
- Datos: sin manifiesto

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
