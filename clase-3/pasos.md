# si empezamos desde cero
git init
git add .
git commit -m "algun comentario"
git brunch -M main
**previo deberiamos haber creado un repo en github para que nos de el git remote**
git remote add origin y la url que sacamos de github
git push -u origin main

**podemos usar git status para obtener una informacionndetallada del estado de nuestro repo**

# si estoy actualizando
**cuando queremos actualizar el repo debemos hacer esto**
git add .
git commit -m "algun comentario"
git push

# aclaracion
**si nos equivocamos al poner el git remote usamos el comando**
git remote set-url origin URL