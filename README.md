# recipe-app-api
Recipe app for source code

#### Build in docker
```
docker-compose build
docker-compose up
```

The App run in http://127.0.0.1:8000/

#### Endpoints
- Crear usuario
- Generar token para usuario
- Datos sobre usuario

```
api/user/create/ 
api/user/token/
api/user/me/
```

- Recetas
- Ingredientes para recetas
- Tags para recetas

```
api/recipe/recipes/
api/recipe/ingredients/
api/recipe/tags/
```