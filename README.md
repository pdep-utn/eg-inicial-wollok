

## Ejercicio inicial para dar Objetos

[![build](https://github.com/pdep-utn/eg-inicial-wollok/actions/workflows/ci.yml/badge.svg)](https://github.com/pdep-utn/eg-inicial-wollok/actions/workflows/ci.yml)

### Primera parte: qué te puedo cobrar

- La materia la representamos como un String
- **nico**: te cobra 50 pesos por cada letra de la materia que da.
  Ejemplos: por "historia" te cobra 8 * 50 = 400
  por "matemáticas" te cobra 11 * 50 = 550
  
- **carlono**
  cobra una cantidad variable (por ahora es 300, se ajusta por inflación)

- **camila**
  - si está de buen humor, te cobra 250 
  - si no, te cobra 700

  es de humor variable

- **lucas**, es un alumno
  - tiene plata ($ 400) y tiene un profe preferido, que puede cambiar.
  - está feliz si su profe preferido le puede dar clases particulares de geografía
  - nico le cobra 450 (9 * 50), carlono le cobra 300, camila 250 ó 700.

### Segunda parte: me piace

- Sabemos las materias que estudia Lucas: [ "historia", "matematicas", "fisica" ]
- Queremos saber si un profe le cae bien un alumno
  - A Nico le cae bien los que estudian Física.
  - A Carlono le caen bien todos.
  - A Camila le caen bien los que estudian más de 3 materias.
- Ahora aparece una alumna nueva: **Melanie**, qué necesitamos que sepa contestar para incorporarla a nuestra solución.
