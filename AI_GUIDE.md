# 🤖 Guía Detallada para Agentes de IA - Traducción de Subtítulos .ASS

## 📖 Introducción

Esta guía está diseñada específicamente para **agentes de IA** que trabajarán con archivos de subtítulos en formato **.ass**. El objetivo es establecer lineamientos claros para realizar traducciones al **español latino** manteniendo un enfoque **sin censura** y **bien adaptado**.

---

## 🎯 Objetivos Principales

1. **Leer y analizar** todos los archivos .ass de ejemplo en este repositorio
2. **Comprender** el estilo de traducción utilizado
3. **Aplicar** los mismos principios a nuevas traducciones
4. **Mantener** la calidad y consistencia del español latino

---

## 📚 Flujo de Trabajo Recomendado

### Paso 1: Análisis Previo ⚠️ **CRÍTICO**

Antes de comenzar cualquier traducción nueva:

```
✅ LEER al menos 5-10 archivos .ass de ejemplo
✅ IDENTIFICAR patrones de traducción recurrentes
✅ ANALIZAR cómo se adaptan expresiones japonesas/inglesas al español latino
✅ COMPRENDER el nivel de libertad en la adaptación
```

### Paso 2: Comprensión del Formato .ASS

Los archivos .ass contienen:

```ass
[Script Info]
; Configuración del script
PlayResX: 1920
PlayResY: 1080

[Styles]
; Definición de estilos de texto

[Events]
; Diálogos con timestamps
Dialogue: 0,0:00:15.23,0:00:18.45,Default,,0,0,0,,Texto traducido aquí
```

**Importante**: Mantener intacta toda la estructura técnica (timings, estilos, códigos).

### Paso 3: Proceso de Traducción

#### ✅ Qué HACER:

- **Adaptar, no traducir literalmente**
  - ❌ Mal: "Estoy muy emocionado"
  - ✅ Bien: "Estoy súper emocionado" / "Me tiene bien emocionado"

- **Usar español latino natural**
  - Emplear modismos apropiados según el contexto
  - Evitar español de España (nada de "vosotros", "guay", etc.)

- **Mantener contenido sin censura**
  - No suavizar lenguaje explícito
  - Conservar la intención original del diálogo

- **Preservar contexto cultural**
  - Adaptar referencias culturales cuando sea necesario
  - Mantener el tono y registro de los personajes

#### ❌ Qué NO HACER:

- Traducciones palabra por palabra
- Usar español castellano
- Censurar o suavizar contenido adulto
- Modificar timings o estructura .ass
- Cambiar estilos definidos

---

## 🌐 Ejemplos de Adaptación al Español Latino

### Expresiones Comunes

| Original (JP/EN) | Traducción Literal ❌ | Adaptación Latino ✅ |
|-----------------|----------------------|---------------------|
| "Sugoi!" | "¡Increíble!" | "¡Qué padre!" / "¡Está brutal!" |
| "Baka" | "Idiota" | "Pendejo" / "Imbécil" |
| "Arigatou" | "Gracias" | "Gracias" / "Te lo agradezco" |
| "Yamete" | "Detente" | "Para" / "Ya basta" |
| "Ii yo" | "Está bien" | "Va" / "Dale" / "Ok" |

### Registro Informal

- Usar contracciones naturales: "pa'", "to'", "qué sé yo"
- Emplear diminutivos/aumentativos latinos: "chiquito", "grandote"
- Incluir muletillas regionales cuando aplique: "wey", "che", "boludo" (según contexto)

---

## 🔧 Aspectos Técnicos

### Estructura a Preservar

```ass
; ❌ NO MODIFICAR ESTO:
Dialogue: Layer,Start,End,Style,Name,MarginL,MarginR,MarginV,Effect,Text

; ✅ SOLO TRADUCIR EL TEXTO:
Dialogue: 0,0:01:23.45,0:01:26.78,Default,,0,0,0,,{Aquí va tu traducción}
```

### Códigos Especiales

Mantener todos los códigos de formato:
- `{\pos(x,y)}` - Posición
- `{\fad(in,out)}` - Fade in/out
- `{\c&HXXXXXX&}` - Colores
- `{\b1}`, `{\i1}`, `{\u1}` - Negrita, cursiva, subrayado

---

## 📋 Checklist de Verificación

Antes de finalizar una traducción:

- [ ] ¿Leí suficientes archivos de ejemplo?
- [ ] ¿La traducción suena natural en español latino?
- [ ] ¿Mantuve el contenido sin censura?
- [ ] ¿Preservé toda la estructura .ass?
- [ ] ¿Los timings permanecen intactos?
- [ ] ¿Los códigos de formato están completos?
- [ ] ¿El registro coincide con el personaje/contexto?

---

## 🗂️ Archivos de Referencia en Este Repositorio

Este repositorio contiene **+100 archivos .ass** que cubren:

- Diversos géneros y estilos
- Diferentes niveles de formalidad
- Variadas adaptaciones regionales
- Múltiples ejemplos de traducción sin censura

**Recomendación**: Revisar archivos con sufijos:
- `.LAT.ass` - Traducciones latinas confirmadas
- `_es.ass` - Versiones en español
- `ES-LA.ass` - Español latino verificado

---

## ⚡ Consejos Rápidos

1. **Contexto es rey**: Entender la escena ayuda a elegir mejores palabras
2. **Personajes consistentes**: Mantener el registro de cada personaje
3. **Fluidez sobre precisión**: Mejor una adaptación fluida que una traducción exacta pero rígida
4. **Revisar ejemplos**: Siempre volver a los archivos de referencia ante dudas

---

## 📞 Recursos Adicionales

Si tienes dudas durante el proceso:

1. Revisa múltiples archivos .ass similares
2. Busca patrones repetidos en las traducciones
3. Prioriza la naturalidad sobre la literalidad

---

*Esta guía debe ser consultada antes de cada sesión de traducción.*
*Los archivos .ass en este repositorio son tu mejor recurso de aprendizaje.*
