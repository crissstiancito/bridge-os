# Informe de Prompts — Lista de Chequeo Virtual de Guardia

**Asignatura:** Proyecto Lista de Chequeo Virtual (Asistente de Guardia)
**Herramienta de IA principal:** Claude (Claude Code / Claude Design)
**Enlace a la herramienta:** https://crissstiancito.github.io/bridge-os/

---

## 1. Objetivo
Diseñar y alimentar una **lista de chequeo virtual** que funcione como asistente de
guardia, integrando navegación, fórmulas, cálculos, seguridad y normativa, de forma
clara, portable y editable.

## 2. Plataforma y portabilidad
- Aplicación web de un solo archivo (HTML/CSS/JS), **sin conexión** (PWA instalable en
  iPhone y Android).
- Publicada con **GitHub Pages** (gratis, HTTPS). El progreso se guarda en el propio
  dispositivo (`localStorage`).

## 3. Estructura (fases)
Puerto · Zarpe · Navegación · Navegación especial · Normativa · Maniobra · Puerto/Atraque ·
Comunicaciones · Meteorología · Cierre/Entrega · Emergencias. Cada fase agrupa sus ítems
de control con nota técnica y normas de referencia (RIPA, SOLAS, STCW, SHOA, IALA-B).

## 4. Uso de IA — prompts utilizados (resumen)
Los prompts se dieron de forma conversacional e iterativa. Ejemplos representativos:

1. **Estructura y contenido**
   > "Organiza una lista de chequeo de guardia dividida en fases (Puerto, Navegando,
   > Fondeo, Entrega, Meteorología, Comunicaciones…) con sus ítems de control."

2. **Síntesis de fórmulas de navegación**
   > "Sintetiza las fórmulas esenciales de la guardia: velocidad–tiempo–distancia (D=V·T),
   > marcación verdadera (Mv=Rv+Mr), distancia al horizonte (≈2,08·√altura del ojo),
   > corrección total, margen bajo la quilla (UKC) y CPA/TCPA."

3. **Cálculos interactivos (calculadoras)**
   > "Crea calculadoras funcionales: calado medio y asiento, guinda disponible, conversión
   > de rumbos (Rv→Rm→Rc), velocidad·distancia·tiempo, regla de los doce (mareas),
   > longitud de cadena de fondeo y escala de carta."

4. **Referencia náutica**
   > "Agrega referencia rápida: balizamiento IALA-B Chile, señales sonoras RIPA, guion VHF
   > de emergencia (MAYDAY/PAN-PAN/SECURITÉ), frases normalizadas OMI (SMCP), nudos,
   > banderas, unidades e inglés para timoneles."

5. **Diseño / interfaz**
   > "Quiero un diseño profesional con identidad marina (mar, buques), animaciones y que
   > sea fácil de interactuar." → Diseño editorial naval (azul marino + oro, tipografías
   > serif), rosa de los vientos y mar animados, checklist por fase con progreso.

6. **Portabilidad / entrega**
   > "Conviértelo en app instalable para Apple y Android y publícala en un enlace."

## 5. Alimentación continua
El contenido se nutre del material de las asignaturas (Navegación Costera, Deberes de la
guardia, Reglamentación marítima, RIPA/COLREG, IALA-B, Maniobras, Estabilidad, etc.).
La estructura permite **seguir agregando** ítems, fórmulas y referencias sin rehacer la app.

## 6. Referencias / fuentes
- RIPA/COLREG (Convenio internacional para prevenir abordajes).
- SOLAS · STCW (OMI).
- IALA-B (sistema de balizamiento, región B — Chile).
- SHOA: derroteros, cartas, Lista de Faros, tablas de marea.
- DIRECTEMAR (Autoridad Marítima de Chile).
- IMO SMCP — Frases normalizadas para las comunicaciones marítimas.
- Material de la formación TUTMC (1.º, 2.º y 3.º semestre).

> Nota: herramienta de apoyo a la formación; no sustituye las publicaciones náuticas
> oficiales vigentes ni el criterio del oficial de guardia.
