# SDL_Lab_2
## Содержимое Dockerfile
```Dockerfile
FROM nginx:1.11-alpine
COPY index.html /usr/share/nginx/html/index.html
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
```
## Содержимое index.html
```html
<!DOCTYPE HTML>
<html>
 <head>
  <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
  <title>Hello World</title>
 </head>
 <body>
  <p>Родионов М.В.</p>
  <p>Студенческий билет - 17Б1468</p>
 </body>
</html>
```
## Результат выполнения
![Результат](/1.jpg)
