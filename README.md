# Pokémon Bank — ATM UI (DAW901)

Interfaz web (Front-End: **HTML + CSS/Bootstrap 4**) para simular un cajero automático (**Login por PIN**, **Acciones**, **Historial**, **Gráfico**). Proyecto académico — Universidad Don Bosco (DAW901).

## ✅ Estado
- `index.html` (Login por PIN — maquetado)
- `acciones.html` (Depósito, Retiro, Consulta de saldo, Pago de servicios — maquetado con modales)
- `historial.html` (pendiente de maquetar)
- `grafico.html` (pendiente de maquetar)

## 🗂️ Estructura
pokemon-bank/
├─ index.html # Login (PIN)
├─ acciones.html # Acciones + modales
├─ historial.html # Historial (tabla + filtros) [por hacer]
├─ grafico.html # Gráfico (Chart.js) [por hacer]
├─ css/
│ └─ styles.css
├─ assets/
│ └─ pokebank.png # logo opcional
└─ docs/
├─ flujo.png|pdf # diagrama de flujo
├─ capturas/ # imágenes para el documento
└─ entrega/
└─ PokemonBank_DAW.docx

## 🧰 Stack
- **HTML5, CSS3**
- **Bootstrap 4** (CDN)
- (Fase siguiente) **Chart.js**, **SweetAlert**, **jsPDF**, **ValidateJS** (mínimo 2 demos requeridas)

## ▶️ Cómo ejecutar
Solo abrir `index.html` en el navegador. (Opcional: VS Code + extensión **Live Server**).

## 🌿 Estrategia de ramas
- Una rama por pantalla/tema:
  - `feature/historial`, `feature/grafico`, `feature/flujo`, `docs/entrega`
- Prefijos:
  - `feat/` nuevas features
  - `fix/` correcciones
  - `docs/` documentación
  - `chore/` tareas no funcionales

### Flujo de contribución (CLI)
```bash
# traer última versión
git checkout main
git pull origin main

# crear tu rama de trabajo
git checkout -b feature/historial

# cambios y commits
git add .
git commit -m "feat(historial): base table + filters placeholders"

# publicar rama y abrir PR
git push -u origin feature/historial
# luego, abrir Pull Request en GitHub y pedir revisión
