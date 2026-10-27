# MenoReuma · prototipo de investigación

Herramienta educativa para explorar decisiones sobre perimenopausia y menopausia en enfermedades reumáticas. **No está validada para uso asistencial, no prescribe y no estima probabilidades individuales.** Versión 0.1.0, evidencia consultada el 27 de octubre de 2026.

Abra `index.html` en un navegador. Funciona sin instalación y sin conexión; los enlaces bibliográficos requieren internet. No utiliza servidor, analítica, cookies ni almacenamiento de casos. Use únicamente casos ficticios. Imprimir o exportar crea una copia bajo responsabilidad de quien la utiliza.

## Contenido

- `index.html`: prototipo autónomo con reglas explicables, datos desconocidos explícitos, casos sintéticos e impresión.
- `REVISION.md`: síntesis crítica preliminar, estrategia reproducible y límites metodológicos.
- `evidencia.csv`: matriz de evidencia seleccionada y alcance de validación.
- `VALIDACION.md`: evaluación necesaria antes de uso clínico.
- `tests.cjs`: comprobaciones automatizadas de reglas de seguridad.
- `catalogo-pubmed.csv`: catálogo bibliográfico de 717 artículos, con cribado humano pendiente; no equivale a estudios incluidos.
- `busqueda-pubmed.json`: búsqueda y procedencia de los 719 identificadores recuperados (incluye dos registros no representados como artículos en el catálogo).

## Qué representa

Se encontró evidencia para usar marcadores establecidos de seguridad, actividad de enfermedad y salud ósea dentro de una evaluación clínica. No se estableció, en las fuentes evaluadas, un panel molecular validado externamente que seleccione de manera integral la terapia menopáusica en estas poblaciones. Las citocinas y otros candidatos permanecen en la sección exploratoria y no accionan tratamientos.

La revisión es **preliminar y de alcance limitado**: búsqueda sistemática inicial en PubMed más guías y búsqueda dirigida; aún no es una revisión sistemática completada conforme a PRISMA. No hay doble cribado, extracción independiente, evaluación formal completa de sesgo ni búsqueda de Embase/CENTRAL/LILACS. No citar como evidencia de eficacia del software ni como revisión sistemática definitiva.

Fibromialgia se incluye como condición reumática de dolor nociplástico, no como enfermedad autoinmune demostrada. No se modifican DMARD, inmunosupresión, antiagregación ni anticoagulación.

## Publicación

GitHub Pages: servir desde `main`, carpeta raíz. El repositorio no debe recibir datos de pacientes, identificadores ni expedientes. El código y la síntesis requieren revisión clínica y metodológica antes de cualquier implementación asistencial. No existe aval institucional, aprobación regulatoria ni certificación clínica implícita.
