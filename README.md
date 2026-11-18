# Tablero de Transferencias Monetarias — DPS

Tablero interactivo de los programas de transferencias monetarias de Prosperidad Social:
Renta Ciudadana, Colombia Mayor, Renta Joven y Compensación del IVA.

Muestra, por corte (histórico, año, periodo de gobierno y ciclo): beneficiarios, inversión,
participación de mujeres, ciclos ejecutados y pendientes, población atendida y distribución
territorial.

## Datos

Cifras **agregadas** de fuente institucional. No contiene datos personales: no hay nombres,
documentos, cuentas ni direcciones; el detalle llega hasta municipio.

Corte: **17 de noviembre de 2026** (histórico 2001 a esa fecha).

Fuentes del corte:

- **Fichas de seguimiento de los programas (Excel)** del GIT Gestión Estratégica y Seguimiento:
  ciclos de pago, población, territorio y resumen del año 2026. Es la fuente principal.
- **Programas - DPS 2026** (SIIF, corte 31 de agosto de 2026): norma, apropiación 2026, monto y
  proyecto de presupuesto 2027. La apropiación se muestra con su propia fecha de corte.
- **Cronograma de ciclos de pago TM**: fechas de entrega de 2026.
- Años 2023 a 2025: se conservan las cifras del informe de la DTM con corte a 28 de octubre de 2026.

Notas de lectura:

- Inversión = valor programado o liquidado para pago; no es lo efectivamente cobrado.
- Beneficiarios no se suma entre programas: una persona u hogar puede recibir varias transferencias.
- Colombia Mayor: la apropiación incluye solo el componente que cofinancia Prosperidad Social y la
  inversión liquidada incluye el aporte del Ministerio del Trabajo, por eso su avance no se calcula.
- Renta Ciudadana puede mostrar avance superior al 100 %: la apropiación es de agosto y el liquidado
  llega a noviembre.
- Renta Joven mantiene el corte del 28 de octubre en su cifra anual: el detalle del ciclo 5 se
  incorporará con la siguiente ficha de seguimiento.

## Publicación

Servido con GitHub Pages desde `index.html`. Es un solo archivo: React, Recharts y Tailwind
van embebidos, así que no necesita build ni dependencias.
