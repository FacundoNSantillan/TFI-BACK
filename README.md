# 🛠️ TFI – BACK | JFA Distribuciones  
**Trabajo Final Integrador – Diseño de Sistemas · UTN FRT**

Este repositorio corresponde al **Backend del Trabajo Final Integrador (TFI)** para la materia **Diseño de Sistemas – UTN Facultad Regional Tucumán**.  
La API provee los servicios necesarios para el funcionamiento del sistema web de **JFA Distribuciones**, gestionando la lógica de negocio, la persistencia de datos y el acceso a la información que será consumida desde el frontend.

---

## 🔗 Repositorio relacionado

Este backend trabaja junto al cliente web:

➡ **Frontend del proyecto:**  
https://github.com/FacundoNSantillan/TFI-FRONT

---

## 📝 Objetivo del Proyecto

El backend tiene como propósito implementar la capa lógica del sistema, permitiendo registrar, consultar, modificar y administrar datos de forma estructurada, segura y escalable.  
Este servidor expone una API REST encargada de comunicarse con la base de datos y responder a las solicitudes realizadas desde el frontend.

El proyecto busca:

- Desarrollar una API REST organizada, modular y mantenible  
- Implementar validaciones, manejo de errores y reglas de negocio  
- Permitir conexión a una base de datos real para persistencia  
- Facilitar su integración con el frontend desarrollado en React/TS  

---

## 🛠️ Tecnologías utilizadas / Stack

| Tecnología | Uso |
|----------|-----|
| **Node.js** | Entorno de ejecución |
| **TypeScript** | Tipado estático para mayor seguridad y control |
| **Express.js** | Framework para definir rutas, controladores y middleware |
| **PostgreSQL** (o BD seleccionada) | Persistencia de datos |
| **Dotenv** | Manejo seguro de variables de entorno |

---

## 🚀 Instalación y ejecución

### 📌 Requisitos previos

- Node.js 16+  
- npm / yarn / pnpm  
- Base de datos configurada (PostgreSQL recomendado)  
- Crear `.env` antes de iniciar el proyecto  

---

### 🔧 Instalación

```bash
git clone https://github.com/FacundoNSantillan/TFI-BACK.git
cd TFI-BACK
npm install      # o yarn install
```

📄 Variables de entorno (.env)

Crear un archivo **.env** en la raíz del proyecto con la siguiente estructura:

```env
# 🔥 Servidor
PORT=

# 🗄 Base de Datos
DB_HOST=
DB_PORT=
DB_NAME=
DB_USER=
DB_PASSWORD=

# 🔑 Autenticación / Tokens
TOKEN_SECRET=

# 🌎 Entorno
NODE_ENV=development
```

⚠️ Importante: completar con sus propios valores antes de ejecutar

▶️ Ejecutar en modo desarrollo
```bash
npm run dev
```

Servidor disponible en:
```bash
http://localhost:PORT
```


