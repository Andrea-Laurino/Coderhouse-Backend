# Tercera pre entrega del Proyecto Final

## Start

1. Configuración del archivo .env.development (default) o .env.production o .env.staging:

**Parámetros a configurar:**

- PORT
- URL MONGO LOCAL
- URL MONGO ATLAS
- NOMBRE DB
- COOKIE KEY
- SECRET KEY
- GITHUB CLIENT ID
- GITHUB SECRET KEY
- GITHUB CALLBACK URL
- JWT SECRET
- JWT EXPIRES IN
- JWT ALGORITH
- ADMIN EMAIL
- ADMIN PASSWORD
- NODE MAILER USER
- NODE MAILER PASSWORD
- TWILIO ACCOUNT SID
- TWILIO AUTH TOKEN
- TWILIO PHONE NUMBER

2. Instalación de dependencias e iniciar servidor:

   ```shell
   npm install
   ```

   ```shell
   npm start
   ```

3. Ingresar a la APP:

   ```
   http://localhost:<PORT>
   ```

### Factory / DAO y DTO

- Conceptos de Factory, DAO y DTO aplicados a la capa de persistencia.

- El DAO seleccionado por un parámetro en línea de comandos es devuelto por una Factory para que la capa de negocio opere con él.

Formato de comandos:

```bash
node indexedDB.js -m <nombre_de_la_variable_de_entorno> -p <nombre_de_la_variable_de_persistencia>
```

Ejemplos de comandos para inicializar el proyecto con diferentes variables de entorno y capas de persistencia:

```bash
node index.js -m development -p MONGO
```

```bash
node index.js -m production -p MEMORY
```

```bash
node index.js -m staging -p FILESYSTEM
```

## Credenciales Admin

### Email:

```
adminCoder@coder.com
```

### Password:

```
adminCod3r123
```
