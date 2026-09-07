# Mi Peso — Seguimiento semanal de peso

Aplicación web sencilla, sin instalación ni cuentas, para que un paciente registre su peso semanalmente y siga su tendencia a lo largo del tiempo.

Los datos se guardan **solo en el propio dispositivo** del paciente (almacenamiento local del navegador) — no se envían a ningún servidor.

## Qué hace la app

- Configuración inicial: altura, peso de partida y objetivo opcional.
- Registro semanal abierto: se añade una entrada (fecha + peso) cada vez que el paciente se pesa, sin límite de semanas.
- Cálculo automático de IMC y su categoría.
- Gráfico de evolución del peso a lo largo del tiempo.
- Cálculo del ritmo de cambio semanal (kg/semana), comparado con el rango saludable de pérdida de peso recomendado: **0,5–1 kg/semana**, según las Guías Dietéticas SEEDO 2024 / Guía GIRO 2024 (Sociedad Española para el Estudio de la Obesidad).
- Avisos si el ritmo de pérdida es más rápido de lo recomendado, o si el IMC cae por debajo de 18,5.
- Botones para compartir el resumen (o copiarlo) y para imprimir/guardar como PDF antes de una consulta.

⚠️ Esta app es una herramienta de apoyo para el seguimiento del peso en casa. **No sustituye el diagnóstico ni el criterio médico** — el resultado debe revisarse siempre con el profesional sanitario correspondiente.

## Cómo publicarla (GitHub Pages)

1. Crea un repositorio nuevo en GitHub y sube estos archivos (puedes arrastrarlos directamente desde la web de GitHub, sin necesidad de usar la terminal).
2. Ve a **Settings → Pages** dentro del repositorio.
3. En "Source", selecciona la rama `main` y la carpeta `/root` (raíz).
4. Guarda. GitHub te dará una URL pública del tipo:
   `https://tu-usuario.github.io/nombre-del-repositorio/`
5. Esa URL es la que puedes convertir en código QR para repartir en el taller.

La publicación suele tardar 1–2 minutos en activarse la primera vez.

## Estructura de archivos

```
├── index.html   # La aplicación (GitHub Pages sirve este archivo automáticamente en la raíz)
├── README.md    # Este archivo
└── LICENSE      # Licencia de uso
```

## Aviso legal

Este proyecto se ofrece con fines educativos y de apoyo al seguimiento del peso en casa. No es un dispositivo médico ni ha sido validado clínicamente como herramienta diagnóstica. El uso de la aplicación no crea una relación médico-paciente ni sustituye la atención sanitaria profesional.
