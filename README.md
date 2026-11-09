# 🤖 Automatización de Contenidos y ETL con n8n

## 📌 Descripción del Proyecto
Este repositorio documenta e implementa un flujo de trabajo automatizado (*Workflow*) desarrollado en **n8n**, 
diseñado para optimizar la distribución multicanal de contenidos (*cross-posting*) y mantener un registro de auditoría operativo 
en la nube de forma totalmente autónoma. El sistema conecta el feed RSS de publicaciones literarias en **Substack**, procesa y filtra 
los lotes mediante validaciones temporales, realiza una integración vía API REST con la **Facebook Graph API** para la publicación en 
redes sociales, y consolida los metadatos transaccionales en una base de datos de **Google Sheets** para su trazabilidad y control.
