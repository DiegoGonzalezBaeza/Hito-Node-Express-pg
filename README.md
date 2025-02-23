# Hito_Node.js_API_Sequelize
Proyecto educativo

Thunder Client: 

Operaciones GET: 

http://localhost:3000/api/v1/users/1

Operaciones POST:

http://localhost:3000/api/v1/users/1

GET /api/v1/uses 200 # Listar todos los usuarios 
GET /api/v1/users/:id 200 # Obtener un usuario por ID 
POST /api/v1/users 201 # Crear un usuario 
PUT /api/v1/users/:id 200 # Actualizar un usuario por ID 
DELETE /api/v1/users/:id 204 # Eliminar un usuario por ID


```json
{
  "name": "hito_node.js_api_sequelize",
  "version": "1.0.0",
  "description": "Proyecto educativo",
  "main": "index.js",
  "exports": "./dist/index.js",
  "type": "module",
  "scripts": {
    "test": "vitest",
    "dev": "tsx watch src/index.ts",
    "build": "pkgroll",
    "start": "node dist/index.js"
  },
  "keywords": [],
  "author": "",
  "license": "ISC",
  "devDependencies": {
    "@types/bcryptjs": "^2.4.6",
    "@types/express": "^5.0.0",
    "@types/jsonwebtoken": "^9.0.7",
    "@types/node": "^22.10.5",
    "@types/pg": "^8.11.10",
    "@types/supertest": "^6.0.2",
    "@types/swagger-jsdoc": "^6.0.4",
    "@types/swagger-ui-express": "^4.1.7",
    "@types/winston": "^2.4.4",
    "pkgroll": "^2.6.1",
    "supertest": "^7.0.0",
    "tsx": "^4.19.2",
    "typescript": "^5.7.3",
    "vitest": "^2.1.8"
  },
  "dependencies": {
    "bcryptjs": "^2.4.3",
    "express": "^4.21.2",
    "express-rate-limit": "^7.5.0",
    "jsonwebtoken": "^9.0.2",
    "nanoid": "^5.0.9",
    "pg": "^8.13.1",
    "swagger-jsdoc": "^6.2.8",
    "swagger-ui-express": "^5.0.1",
    "winston": "^3.17.0"
  }
}
```

sirve para los entornos virtuales
```bash
npm i dotenv
```

```ts
import "dotenv/config";
```