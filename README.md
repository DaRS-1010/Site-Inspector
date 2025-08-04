# 🕵️‍♂️ Site Inspector – Web Storage Scanner

Una herramienta ligera en JavaScript para analizar **cookies**, `localStorage`, `sessionStorage` e `indexedDB` en sitios web sospechosos.  
Ideal para detectar estafas cripto, técnicas de phishing o scripts que recolectan datos sensibles sin consentimiento.

---

## 🚀 ¿Cómo usarlo?

1. Abre la **consola del navegador** (F12 o clic derecho > Inspeccionar > Consola)
2. Copia y pega el contenido de `siteInspector.js`
3. Presiona Enter

🔍 El script mostrará si se detectan patrones como `token`, `wallet`, `usdt`, `key`, etc.  
✔️ Si todo está limpio, también te lo dirá.

---

## 🧠 ¿Qué analiza?

- `document.cookie`
- `localStorage`
- `sessionStorage`
- `indexedDB` (nombre y versión)
- Todo contra patrones sospechosos predefinidos

---

## 💡 ¿Por qué usarlo?

Sitios fraudulentos suelen:

- Simular paneles con saldos en criptomonedas (USDT, BTC…)
- Pedir credenciales o “comisiones de retiro”
- Ejecutar scripts que roban datos del navegador
- Usar redes como **TRC20** para aparentar legitimidad

Este script ayuda a revisar si hay actividad sospechosa en el lado del cliente.

---

## 📦 Opcional: versión bookmarklet

Pega el contenido de `bookmarklet.txt` en tus favoritos para ejecutarlo con un clic.

---

## 🛡 Disclaimer

Esta herramienta es solo para fines educativos y de investigación.  
**No garantiza seguridad total ni sustituye herramientas profesionales.**

---
