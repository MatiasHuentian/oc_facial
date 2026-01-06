# Original Clinic — Web + E-commerce (Prototipo/Maqueta)

Sitio web para **Original Clinic** (ex OpenClinic), clínica de estética facial en Chile.  
El proyecto busca una estética **SPA cálido + lujo sobrio + oficina profesional exclusiva**, con foco en **experiencia del lugar**, **confianza** y un flujo de **compra de tratamientos + agendamiento post-pago**.

---

## Descripción del proyecto

**Objetivo del sitio (Pacientes / principal):**
- Portada centrada en la experiencia del lugar (video + fotos del espacio).
- Presentación editorial de tratamientos y packs.
- **E-commerce**: compra del tratamiento (pago completo) → luego **agenda**.
- Soporte rápido: botón/CTA a **WhatsApp**.

**Sección secundaria (Profesionales):**
- Acceso discreto en la barra superior: “Panel para profesionales”.
- En primera etapa: landing informativa + captura de interesados (postulación/contacto).
- Escalable a un sistema más completo en fases posteriores.

**Restricción clave:**  
- **No mostrar precios en la portada (hero/home)**.  
- Precios solo dentro de listados/fichas de tratamientos y packs.

---

## Identidad y tono

- **Sensación:** premium, cálida, confiable, cercana (sin perder formalidad).
- Evitar: “clínica fría” y “promo barata”.
- Lenguaje visual: bloques amplios, editorial, poco texto, fotos grandes, paleta sobria (beige/madera + negro/blanco).
- Tipografía: el logo usa “Perpetua” (referencial; no obliga a usarla en todo el sitio).

---

## Contenido base ya definido

### Nombre y textos
- Nombre: **Original Clinic**
- Subtítulo (provisorio): **Facial Aesthetics**
- Slogan (provisorio): **Be Original**

### Top 6 tratamientos (Home)
1. Toxina Botulínica  
2. Sculptra (Bioestimulador de colágeno)  
3. Skinbooster  
4. Definición Mandibular  
5. Pink Glow (Mesoterapia)  
6. Limpieza Facial Profunda  

### Packs
- 🎀 Spa Day: limpieza facial profunda + lifting pestañas — $80.000  
- ✨ Limpieza facial + Pink Glow (1 sesión) — $120.000  
- ✨ Pink Glow (3 sesiones) — $240.000  
- 💎 Bótox (3 zonas) + Pink Glow (1 sesión) — $290.000  
- 🔥 Bótox Match (3 zonas para 2 personas) — $400.000  

### Confianza / respaldo
- Autorización sanitaria: **Resolución N° 2513288916**
- Credenciales:
  - Especialidad en Implantología Buco Máxilo-Facial
  - Ex Docente Universitario USS
  - Diplomado Estética Facial
  - Jefe de odontología en APS Huechuraba

### Contacto
- Dirección: Av. Apoquindo 7331 - Oficina 940 Torre 1, Las Condes  
- WhatsApp: +56 9 9325 7658  
- IG: @openclinic.cl (pronto @originalclinic.cl)  
- Email: sebastian.leon@openclinic.cl (pendiente cambio)  
- Horarios:
  - Lun–Mié 18:00–21:00
  - Jue 16:00–21:00
  - Vie 10:00–21:00
  - Sáb 15:00–21:00

---

## Assets (cliente)
- Fotos: ordenadas por tratamiento + carpeta “CLÍNICA”.
- Videos: verticales, alta calidad (nombres descriptivos).
- Logos: PDF, con y sin fondo (isotipo OC y logo completo).

Links:
- Fotos: https://drive.google.com/drive/folders/1m6lgChjUEjBKEBZ1FxxebIOGkqXIia5a?usp=sharing  
- Videos: https://drive.google.com/drive/folders/1nJ0e6SOO-pMPVwCXngSsjnFRrxFVNxsb?usp=sharing  
- Logo: https://drive.google.com/drive/folders/1oxZ4U3h_cCCNwXmtMOzV3-zG4RprPKk4?usp=sharing  

---

## Alcance por fases (resumen)

### Fase 1 — Maqueta / Prototipo navegable (prioridad actual)
Pantallas mock:
- Home (Pacientes)
- Tratamientos (listado)
- Tratamiento (ficha)
- Packs (listado)
- Carrito
- Checkout (mock)
- Pago OK
- Agenda post-pago (mock)
- Profesionales (landing)

### Fase 2 — Sitio público MVP (sin pago real si se decide)
- Home completo + navegación + SEO básico + WhatsApp + contacto.

### Fase 3 — E-commerce real
- Integración Getnet (pago web real, no POS).
- Compra completa del tratamiento.

### Fase 4 — Agenda real post-pago
- Pendiente de definición: confirmación automática vs confirmación manual.

---

## Pendientes críticos (no avanzar sin decidir)
- Agenda post-pago:
  - ¿Confirmación automática o sujeta a confirmación manual?
- Reembolso/cambios/no-show:
  - ¿Política para compras que no se agendan o cancelaciones?
- Evaluación previa:
  - ¿Algún tratamiento requiere evaluación antes de comprar?

---

## Estructura recomendada del Home (Pacientes)
1. Header fijo: logo + menú + CTA “Agendar evaluación” + link “Panel para profesionales”  
2. Hero: video corto del lugar + titular + subtítulo + CTAs  
3. Confianza: resolución sanitaria + credenciales resumidas  
4. La Clínica: fotos + texto editorial  
5. Top tratamientos: cards sin precio  
6. Packs/programas: presentación sobria  
7. Categorías (inyectables / piel / lifting)  
8. Cómo funciona: elige → paga → agenda  
9. Equipo/doctor: credenciales  
10. Ubicación/contacto: mapa + WhatsApp  
11. Footer

---

# README para humanos (uso diario)

## Cómo usar este repositorio/prototipo
1) Revisa el Home y el flujo paciente:
- Home → Tratamientos → Ficha → Carrito → Checkout → Pago OK → Agenda → Confirmación

2) El objetivo de esta etapa es **validar estética + estructura + UX**, no backend.

## Qué NO hacer en esta etapa
- No implementar pagos reales aún.
- No integrar agenda real aún.
- No sobrecargar el home con precios/promociones.

## Qué revisar con el cliente
- Si el home transmite: cálido + premium + confiable.
- Si el flujo compra → agenda se entiende.
- Si tratamientos/packs se ven “programas” (no “oferta”).

---

# README para IA (instrucciones de trabajo)

## Tu rol
Eres diseñador/a web + UX + prototyper front-end. Debes proponer o generar un prototipo estático premium/editorial para Original Clinic.

## Restricciones
- No inventar información: si falta, usa placeholders marcados.
- No poner precios en el hero/portada.
- Mantener tono premium sobrio, nada agresivo.
- Priorizar mobile y performance.

## Entregables esperados
- Home (con secciones definidas arriba) en alta calidad visual.
- Flujo mock navegable (tratamientos → compra → agenda).
- Copy base (titular, subtítulo, microcopy CTA, clínica, confianza, cómo funciona).
- Mini sistema visual (colores/tipo/componentes).
- Checklist de implementación (SEO, analítica, performance, accesibilidad).

## Decisiones ya tomadas
- Home enfatiza la experiencia del lugar (video + fotos).
- Precios fuera de portada; dentro de tratamientos/packs.
- Estilo editorial tipo lounge/SPA premium.

## Pendientes
- Agenda: confirmación automática vs manual.
- Políticas de cambios/reembolsos/no-show.
- Tratamientos que requieran evaluación previa.

## Output recomendado
- Prototipo HTML estático (Tailwind CDN + CSS mínimo) o maqueta Figma.
- Incluir comentarios claros de reemplazo de assets y textos.

---
