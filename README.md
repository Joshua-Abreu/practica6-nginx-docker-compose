# Práctica 6: Servidor web Nginx con Docker Compose

Servidor web Nginx corriendo en local con Docker Compose. Sirve una página `index.html` con "Hola Mundo" ubicada en la carpeta `src`, montada como volumen en `/usr/share/nginx/html`.

## Cómo probarlo

```bash
git clone https://github.com/Joshua-Abreu/practica6-nginx-docker-compose.git
cd practica6-nginx-docker-compose
docker compose up -d
```

Abrir http://localhost:8080 en el navegador. Debe mostrar "Hola Mundo".

Para apagarlo:

```bash
docker compose down
```
