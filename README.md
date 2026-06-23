# 📄 Analizador de Hojas de Vida con IA

Extrae automáticamente **Nombre, Correo, Celular, Universidad y Estudios** de hojas de vida (PDF, DOCX, TXT) y exporta todo a un Excel organizado por columnas.

---

## ⚙️ Instalación

### 1. Instalar dependencias

```bash
pip install -r requirements.txt
```

### 2. Obtener API Key de Anthropic

1. Ve a **https://console.anthropic.com**
2. Inicia sesión / regístrate
3. En el menú lateral → **API Keys** → **Create Key**
4. Copia la clave (empieza por `sk-ant-...`)

---

## 🚀 Uso

```bash
python analizador_hv.py
```

### Pasos en la interfaz:

1. **API Key** → Pega tu clave de Anthropic en el campo superior izquierdo
2. **Agregar HV** → Selecciona uno o varios archivos (PDF / DOCX / TXT)
3. **⚡ ANALIZAR** → La IA procesa cada CV automáticamente
4. **📊 Exportar Excel** → Guarda el archivo con todas las columnas separadas

---

## 📊 Columnas en el Excel

| Columna | Descripción |
|---|---|
| N° | Número de registro |
| Nombre Completo | Nombre y apellidos |
| Correo | Email de contacto |
| Celular | Teléfono / Celular |
| Universidad | Institución educativa |
| Nivel Estudios | Profesional, Técnico, Magíster… |
| Título / Carrera | Programa académico |
| Año Graduación | Año en que se graduó |
| Archivo Origen | Nombre del archivo original |

---

## 📁 Formatos soportados

- **PDF** (`.pdf`) — Cualquier hoja de vida en PDF con texto seleccionable
- **Word** (`.docx`) — Documentos de Microsoft Word
- **Texto** (`.txt`) — Archivos de texto plano

---

## 💡 Requisitos del sistema

- Python 3.9 o superior
- Conexión a internet (para la API de Anthropic)
- API Key de Anthropic (hay créditos gratis al registrarse)
