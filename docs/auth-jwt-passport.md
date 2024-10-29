# Instalacion
```
npm i --save @nestjs/jwt passport-jwt bcrypt
npm i  --save-dev @types/passport-jwt
```

# Arrancamos el proyecto 
```
npm run start:dev
```
# Modules & Resource
```
nest g s modules/auth
nest g res modules/users
```
# Controller & Resource
```
nest g co modules/auth
nest g s modules/auth
```
