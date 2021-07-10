"# Proyecto-2" 

    
    class Alumno{
        constructor(codigo,nombre,edad,carrera,tarea){
            if (edad<0 || edad>120){
                console.log('Edad no valida... intente de nuevo');
            }
            this.codigo=codigo;
            this.nombre=nombre;
            this.edad=edad;
            this.carrera=carrera;
            this.tarea=tarea;
        }

        Mostrar_Datos(){
            console.log('Codigo: ',this.codigo,' Nombre: ',this.nombre,' Edad: ',this.edad,' Carrera: ',this.carrera); 
        }
        
        Solucion_Tarea(){
            console.log('Solucion de la tareas: ',this.tarea);
        }
    }
    