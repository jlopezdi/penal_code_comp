Para poder editar el contenido de github:
```shell
cd /carpeta_vuestra
git clone https://github.com/ku2a/penal_code_comp
cd penal_code_comp
```

Cuando alguien cambia algo podeis actualizar vuestra carpeta local con
```shell
git pull
```
Si no cuadra todo lo local con lo subido en el git os va a dar error de merge, buscais como hacer merge (preguntad a chatgpt) y haceis pull
cuando termineis comprobais los cambios que habeis hecho con
```shell
git status
```
y para enviarlo haceis
```shell
git add .
git commit -m "comentario de lo que he hecho y qn soy"
git push
```



