# PROYECTO-SOCIOTECNOLOGICO-III
Proyecto para la universidad y optar por el nuevo año 
modulos del sistema informatico para gestion de estudiantes y PAE

primero lo primero, que me pide un sistema web cuando lo voy a utilizar? 

-pagina principal de presentacion. con sus respectivos botones para iniciar session:
	*iniciar session: 
	-nombre usuario
	-cargo
	-contraseña

	y si no estoy registrado? ingresa los siguientes datos y te registras
	*registro
	-numero de cedula
	-nombre
	-apellido
	-cargo
	-nombre de usuario
	-contraseña

-Login: distintos accesos:

*administradores(director, y dub director) podran realizar cualquier gestion de procesos en el sistema, tendran acceso a todo ya que som los duros

*gente del pae(la que haga ese trabajo) solo gestionaran procesos del pae y podran administrar ese tipo de alimentos que lleguen  y con sus respectivas grafiquitas y ña cuestion

*inscripciones(para la secretaria) inscribir muchachos en el nuevo año escolar de manera eficaz

de ahi me envia al index de la pagina

-estructura base del sistema:

cabecera -> nombre de la escuela

menu -> 
*alumnos
*nuevo proceso de inscripciones : inscribir a uno solo, inscribir en un solo grado, inscribir a todos los estudiantes (solo adms o secretaria por que la señora del pae no va a registrar){
	-abrir nueva jornada de inscripciones -> {
		 si el alumno tiene nota superior o igual a 'D' pasa
		 si el alumno tiene nota inferior a 'D' repite y no pasa al siguiente año
	}
	-las secciones {
		segun hayan alumnos se iran creando nuevas secciones y tendran un seleccionador para asignarle el profesor 
	}
}
*seccion del pae: registra la cantidad de alimentos que entran en la institucion, cantidad, kilos, tipo de alimento (arroz, carne, legumbres etc)
* seccion de profesores
*calendario de eventos dentro de la institucion
SUPER IDEA 
DIVIDIR LOS MODULOS DE TRABAJO EN LA INSTITUCION EN SECCIONES INDIVIDUALEs
