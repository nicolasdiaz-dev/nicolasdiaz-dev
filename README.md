# 👋 Nicolás Díaz — AI Solutions Developer

**Especializado en agentes de IA, automatización operativa y reporting inteligente**

🔗 **[Portfolio interactivo](https://nicolasdiaz-dev.github.io/nicolasdiaz-dev/)** | 🔗 **[Sudaka — Asistente operativo](https://nicolasdiaz-dev.github.io/nicolasdiaz-dev/sudaka/)** | 💼 **[LinkedIn](https://www.linkedin.com/in/nicolas-diaz-641a17346)** | 📧 **[Contacto](mailto:nicolas.diaz@gout.com.ar)**

---

## 📋 Resumen ejecutivo

Desarrollador especializado en **IA operativa y automatización de procesos** en GOUT | Global Outsourcing. Me dedico a diseñar e implementar soluciones de negocio que conectan agentes de IA con canales reales (WhatsApp, Telegram, email) y transforman operaciones manuales en sistemas escalables.

Con experiencia en **20+ repositorios** (mayoría privados en producción), trabajo en:

- 🤖 **Agentes de IA**: Clasificación, derivación y soporte operativo 24/7  
- 📊 **Dashboards ejecutivos**: KPIs en tiempo real, proyecciones, análisis por Claude  
- ⚙️ **Pipelines de datos**: Recolección, transformación y reporting automatizado  
- 🔗 **Integraciones complejas**: APIs de Google, Meta, Botmaker, NICE, SFTP/FTP  

Experiencia en **producción real** con Google Cloud Run, Oracle Cloud, Supabase y arquitecturas event-driven con control de costos y observabilidad.

---

## 🎯 Qué hago

**Automatización operativa**  
Desarrollo agentes de IA conversacionales que corren 24/7 clasificando mensajes, detectando oportunidades y derivando a equipos correctos sin intervención humana.

**Reporting ejecutivo inteligente**  
Construyo dashboards multi-cliente que consolidan datos de campañas, contact center y CRM, con análisis automático generado por IA.

**Integraciones productivas**  
Conecto Google Ads, Meta Ads, Gmail, Drive, Sheets, Botmaker y plataformas internas con arquitecturas robustas y control de permisos.

**Herramientas propias**  
Desarrollo utilidades local-first: dictado de voz sin dependencias externas, consolas de monitoreo con D3, agents SDK integrados.

---

## 🛠️ Stack tecnológico

### Lenguajes & Datos
```
Python | JavaScript | SQL | PowerShell | JSON | CSV | pandas | SQL (PostgreSQL)
```

### IA & Agentes
```
Anthropic Claude | Claude Agent SDK | OpenAI | OpenClaw | Prompt Design | Tool Use | Clasificación de Intenciones | Conversational AI
```

### Dashboards & Visualización
```
Streamlit | Power BI | Looker Studio | React + Vite | Plotly | Google Sheets | D3.js
```

### Automatización e Integraciones
```
GitHub Actions | Google Workspace APIs | Google Ads API | Meta Graph API | Botmaker API | SFTP/FTP | n8n | Webhooks | REST APIs
```

### Cloud & Deploy
```
Google Cloud Run | Google Cloud Platform (GCP) | Oracle Cloud (OCI) | Supabase | Vercel | Render | Streamlit Cloud | GitHub Actions
```

### Plataformas Operativas
```
OpenClaw | Botmaker | NICE inContact | Google Workspace | Gmail | Calendar | Drive
```

---

## 🚀 Proyectos destacados

*Todos estos son repositorios reales corriendo en producción. Las descripciones están sanitizadas sin datos internos, credenciales ni información sensible.*

### 🤖 Agentes de IA

#### **Azul** — Sales AI Agent (DirecTV Perú)
Agente de primera atención para el canal de ventas en WhatsApp. Filtra prospectos, detecta intenciones, califica leads y deriva conversaciones al equipo correcto.

- Corre 24/7 en Google Cloud Run  
- Claude con tool use como motor conversacional  
- Deduplicación de mensajes en PostgreSQL/Supabase  
- Registro de leads en Google Sheets  
- Tests, CI y observabilidad integrados  

**Stack:** Python · Flask · Anthropic Claude · Botmaker · PostgreSQL/Supabase · Google Sheets · Cloud Run

---

#### **Sudaka / OpenClaw** — Asistente operativo
Agente personal de soporte operativo desplegado en Oracle Cloud ARM. Accede a información, prepara reportes, ejecuta flujos controlados y asiste tareas recurrentes por Telegram con aprobación explícita.

- Integración con Gmail, Calendar, Drive, GitHub  
- Memoria contextual y skills por contexto  
- Acciones sensibles con aprobación dos-factores  
- Acceso seguro vía OCI Bastion  

**Stack:** OpenClaw · Python · Oracle Cloud (OCI) · Telegram · Google Workspace · GitHub

➡️ **[Presentación pública](https://nicolasdiaz-dev.github.io/nicolasdiaz-dev/sudaka/)**

---

#### **Jarvis (Iron-Claude)** — Asistente de voz local
Asistente de voz personal basado en Claude Agent SDK con interfaz neuronal en el navegador. Reconocimiento y síntesis de voz 100% local sin dependencias externas.

- Whisper para transcripción local  
- Integración con GitHub, Gmail, Calendar, Drive, Obsidian  
- Lectura libre, escritura con aprobación  

**Stack:** Node.js · Claude Agent SDK · Web Speech API · MCP

---

#### **Director de Performance** — Agente de marketing
Genera reportes HTML ejecutivos de campañas Meta Ads, Google Ads y atribución de ventas. Pipeline: recolectar datos → análisis de IA → HTML ejecutivo con umbrales configurables.

**Stack:** Python · Claude · Meta Graph API · Google Ads API · Google Sheets

---

#### **Luna / Agentes Botmaker**
Agentes conversacionales para WhatsApp que clasifican intenciones, detectan prospectos y derivan conversaciones.

**Stack:** Python · Flask · Claude · Botmaker · Redis · n8n · Render · Cloud Run

---

### 📊 Dashboards & Reporting

#### **App_Ads** — Plataforma de métricas (LATAM)
Monitorea inversión, ventas y proyecciones de campañas por cliente y región (DirecTV, Prosegur, Claro, Movistar, Zaaz en 8 países).

- Tres frontends: React + Vite (Vercel) · Flask (Render) · Streamlit  
- Funciones serverless Python en Vercel  
- Sincronización horaria desde Sheets a Supabase con GitHub Actions  

**Stack:** React · Python · Flask · Streamlit · Google Ads API · Meta Graph API · Supabase · Vercel

---

#### **Hunter Uruguay** — Dashboard comercial
Seguimiento en tiempo real: leads, ventas, KPIs vs. ayer, conversión diaria, ranking de asesores.

**Stack:** Python · Streamlit · Plotly · Google Sheets · Streamlit Cloud

---

#### **Movistar México — Dashboard ADS**
Campañas Google Ads y Facebook: KPIs del mes, proyecciones, funnel impresiones→ventas, detalle diario.

**Stack:** Python · Streamlit · Plotly · Render

---

#### **Reportería Supervisores**
Lee datos operativos de Sheets, genera HTML interactivo con análisis de IA y envía automáticamente por Gmail.

**Stack:** Node.js · Google Sheets API · Gmail API (OAuth2) · Claude

---

#### **Reporte Desborde** — Monitoreo operativo
Comportamiento de llamadas y ventanas operativas (DirecTV Argentina).

**Stack:** Python · Streamlit/Flask · pandas · GitHub Actions

---

### ⚙️ Automatización de datos

#### **Botmaker_auto** — Pipeline de sesiones
Extrae sesiones y métricas desde API de Botmaker con caché inteligente y publica reportes por cola en Sheets.

**Stack:** Python · Botmaker API · Google Sheets API · GitHub Actions

---

#### **NICE_AUTO** — Reportería contact center
Descarga diaria de NICE inContact, filtro por campaña, acumulados mensuales, control de duplicados.

**Stack:** PowerShell · NICE inContact · Google Sheets API · GitHub Actions

---

#### **CRM_SFTP** — Sincronización operativa
Descarga, limpieza y carga desde SFTP/FTP hacia hojas de seguimiento (gestiones, productividad, tickets).

**Stack:** Python · pandas · SFTP/FTP · Google Sheets API

---

### 🛠️ Herramientas propias

#### **Vide Coding Local** — Dictado por voz local
Dictado 100% local para escribir, programar y responder mensajes. `Ctrl+Space`, hablás, y el texto se pega donde tengas el cursor.

- Transcripción local con `faster-whisper`  
- Modos de escritura: código, emails, mensajes  
- Overlay flotante con estado y nivel de voz  
- Historial privado local  

**Stack:** Python · faster-whisper · Windows

---

#### **Synapse Private Console** — Consola de repositorios
Consola privada en producción para monitorear repositorios de GitHub con vista de red neuronal (D3), lista, palette y filtros.

- GitHub App real con permisos mínimos  
- Login propio con cookie firmada  
- Headers de seguridad (CSP, HSTS)  
- Cero secretos en el navegador  

**Stack:** React · Vite · D3 · Vercel Serverless · GitHub App

---

## 💡 Patrones & Código

### Webhook de agente con deduplicación
```python
@app.route("/agente/webhook", methods=["POST"])
def receive_message():
    payload = request.get_json(force=True)
    message_id = payload["_id"]

    if already_processed(message_id):
        return {"status": "duplicate"}, 200

    mark_processed(message_id)
    reply = agent.respond(
        contact_id=payload["contactId"],
        text=payload["text"],
    )
    botmaker.send(payload["chatChannelId"], reply)
    return {"status": "ok"}, 200
```

### Google Sheets con Service Account
```python
from google.oauth2.service_account import Credentials
from googleapiclient.discovery import build

SCOPES = ["https://www.googleapis.com/auth/spreadsheets"]

credentials = Credentials.from_service_account_file(
    "credentials.json", scopes=SCOPES
)

sheets = build("sheets", "v4", credentials=credentials)

def append_rows(spreadsheet_id: str, range_name: str, rows: list[list[str]]) -> None:
    sheets.spreadsheets().values().append(
        spreadsheetId=spreadsheet_id,
        range=range_name,
        valueInputOption="USER_ENTERED",
        body={"values": rows},
    ).execute()
```

### Query en Google Ads API
```python
def campaign_daily_query(customer_id: str, start_date: str, end_date: str):
    query = f"""
        SELECT
          campaign.name,
          segments.date,
          metrics.cost_micros,
          metrics.conversions,
          metrics.clicks
        FROM campaign
        WHERE segments.date BETWEEN '{start_date}' AND '{end_date}'
    """

    return google_ads_service.search(
        customer_id=customer_id,
        query=query,
    )
```

### Flujo operativo seguro con aprobación
```python
def run_sensitive_action(action_name: str, payload: dict, approved: bool) -> str:
    if not approved:
        return "Pendiente de aprobación explícita"

    audit_log.info("running_action", extra={
        "action": action_name,
        "payload_keys": sorted(payload.keys()),
    })

    return execute_controlled_action(action_name, payload)
```

---

## 🎓 Áreas de especialización

- **IA aplicada a operaciones reales** — Agentes en producción con tool use, memoria, validaciones  
- **Automatización comercial** — Pipelines end-to-end, integraciones multi-API  
- **Contact center & soporte** — Clasificación, derivación, reportería  
- **Reporting ejecutivo** — Dashboards multi-cliente con análisis automático  
- **Local-first & privacy** — Herramientas sin dependencias externas  
- **Cloud architecture** — GCP, OCI, diseño cost-effective, observabilidad  

---

## 📬 Conecta conmigo

📧 **Email:** [nicolas.diaz@gout.com.ar](mailto:nicolas.diaz@gout.com.ar)  
🔗 **GitHub:** [@nicolasdiaz-dev](https://github.com/nicolasdiaz-dev)  
💼 **LinkedIn:** [nicolas-diaz-641a17346](https://www.linkedin.com/in/nicolas-diaz-641a17346)  
🌐 **Portfolio:** [nicolasdiaz-dev.github.io](https://nicolasdiaz-dev.github.io/nicolasdiaz-dev/)  

---

**Última actualización:** julio 2026  
*Este perfil resume 20+ proyectos en producción privados. Los ejemplos son sanitizados sin datos internos ni credenciales.*
