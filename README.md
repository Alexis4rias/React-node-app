# React Node App

Proyecto base para una aplicación web con **Node.js + Express** en el backend y **React** en el frontend. Actualmente tiene el servidor configurado y listo para conectarse con el cliente de React una vez que se integre.

---

## 📁 ¿Cómo está organizado?

```
react-node-app/
├── server/
│   └── index.js       # El servidor Express
├── package.json
└── package-lock.json
```

> El frontend de React todavía no está integrado en el repositorio.

---

## 🛠️ ¿Con qué está hecho?

| Parte | Herramienta |
|-------|-------------|
| Servidor | Node.js + Express 5 |
| Frontend (próximamente) | React |

---

##¿Cómo lo corro?

### 1. Clona el repositorio

```bash
git clone https://github.com/Alexis4rias/React-node-app.git
cd React-node-app
```

### 2. Instala las dependencias

```bash
npm install
```

### 3. Enciende el servidor

```bash
npm start
```

El servidor arrancará en el puerto **3001** por defecto. Si tienes una variable de entorno `PORT` definida, usará esa.

```
Server listening on 3001
```

### 4. Prueba que funciona

Abre en el navegador o en Postman:

```
http://localhost:3001/api
```

Deberías ver esto:

```json
{ "message": "Hola desde el servidor!" }
```

---

## Endpoints disponibles

| Método | Ruta | ¿Qué hace? |
|--------|------|------------|
| `GET` | `/api` | Verifica que el servidor está corriendo |

---

## Estado del proyecto

Este repositorio está en sus primeras etapas. Por ahora solo tiene el servidor base listo. Lo que viene después:

- [ ] Integrar la app de React como cliente
- [ ] Conectar el frontend con la API del servidor
- [ ] Agregar más rutas según la funcionalidad del proyecto

---

## 👤 Autor

**Alexis Arias**  
Estudiante de Ingeniería en Sistemas Computacionales  
Universidad de Montemorelos · Generación 2025–2026
