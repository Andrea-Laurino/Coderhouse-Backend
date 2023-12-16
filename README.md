# Cuarta práctica integradora del PF

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

## Modo Desarrollo

Puedes iniciar la aplicación en el entorno de desarrollo con el siguiente comando:

```bash
npm run dev
```

Esto iniciará el servidor y creará usuarios y productos en la base de datos de la app para realizar testings:

- 20 Productos (con Faker)
- Usuarios con los roles "admin", "user" y "premium"

## Credenciales de Admin:

Estas credenciales de admin están definidas en el archivo .env para tests con el role de admin.

### Email:

```
adminCoder@coder.com
```

### Password:

```
adminCod3r123
```

# Credenciales de users con roles asignados para testing:

## Credenciales de Admin (role:"admin") creado en la DB al iniciar la app:

### Email:

```
admin@correo.com
```

### Password:

```
1234
```

## Credenciales de User (role:"user") creado en la DB al iniciar la app:

### Email:

```
user@correo.com
```

### Password:

```
1234
```

## Credenciales de User Premium (role:"premium") creado en la DB al iniciar la app:

### Email:

```
premium@correo.com
```

### Password:

```
1234
```
