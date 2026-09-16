# 📝 Gestor de Tareas

> pagina web para la creación y gestión de tareas desarrollada como proyecto académico.

---
# 👥 Integrantes del equipo
- Ana Villanova
- Omar Gutierrez
- Angel Morales
- Daniela Beltran
- Frederick Jimenez 

## 📌 Descripción

**Gestor de Tareas** es una pagina web diseñada para facilitar la creación, consulta, modificación y eliminación de tareas.

El proyecto está basado  en un sistema **CRUD** (Crear, Leer, Actualizar y Eliminar), permitiendo al usuario administrar sus tareas de manera sencilla e intuitiva.

Como nueva funcionalidad, se incorporó una **papelera de reciclaje**, diseñada para evitar que una tarea sea eliminada de forma permanente inmediatamente.

---

## ✨ Funcionalidades

### 📋 Gestión de tareas

La pagina web permite realizar las operaciones principales de un CRUD:

- **Crear:** agregar nuevas tareas a la lista.
- **Leer:** visualizar las tareas registradas.
- **Actualizar:** modificar la información de una tarea.
- **Eliminar:** retirar una tarea de la lista principal.

Donde su archivo mas importante es el llamado app/page.js el cual contiene todo el codigo de la funcionalidad de la pagina web. Ademas, tenemos el archivo llamado app/global.css donde se puede editar el estilo y colocar mas agradable la pagina web para el usuario 

### 🗑️ Papelera

La pagina web cuenta con una papelera que almacena temporalmente las tareas eliminadas.

Cuando el usuario presiona **Eliminar**, la tarea desaparece de la lista principal y pasa a la papelera. Desde allí se presentan dos opciones:

- **Restaurar:** devuelve la tarea a la lista principal de tareas.
- **Eliminar definitivamente:** elimina la tarea de forma permanente.

De esta manera, la papelera permite recuperar tareas eliminadas accidentalmente antes de borrarlas definitivamente.

---

## 🔄 Flujo de eliminación

```text
        📋 LISTA DE TAREAS
                │
                │ Eliminar
                ▼
        🗑️ PAPELERA
          /           \
         /             \
   ♻️ Restaurar    ❌ Eliminar
         │          definitivamente
         ▼             │
   📋 Vuelve a la      ▼
   lista de tareas   🗑️ Eliminada
                    permanentemente

```

---

## Como correr el proyecto
Se clona el prepositorio y se abre la terminal en el proyecto e ejecuta:
```text
    npm install
    npm run dev
```
Se genera una url y se copia e pega en el navegador este link:
```text
    http://localhost:3000
```

