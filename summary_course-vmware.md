
---
Summary GIT UDEMY COURSE 
echo "# curso_vmware" >> README.md
git init
git add README.md

git clone repo

git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/sergioxjaque/curso_vmware.git
git push -u origin main

------------------------------------------
** Tipos de disco 
* thin --> No reserva todo el tamaño, lo ocupa en la medida que lo necesita
hasta alcanzar el tamaño definida.

* thick (2 tipos)
-->  Lazy zeroed --> consume la capacidad definida del disco + formatea a medida que va a usar
-->  Eager zeroed --> consume la capacidad definida del disco + formato lento (escribe 000)
     (Proceso mas lento de los 3)
	 

** donde se ven las alarmas de aprovisionamiento thin ?

