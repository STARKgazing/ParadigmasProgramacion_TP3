
Para este TP3, se re-organizo la estructura del directorio donde se encuentra la app de ToDo List.

El directorio **Models** tiene un archivo **Tarea.ts** en el que se crea una tarea y su constructor que define la estructura de una tarea:

-----

export class Tarea {
    private _titulo: string;
    private _descripcion: string;
    private _estado: EstadoTarea;
    private _dificultad: DificultadTarea;
    private _fechaCreacion: string;
    private _fechaFinalizacion: string | null;

    constructor(
        titulo: string,
        descripcion: string,
        estado: EstadoTarea,
        dificultad: DificultadTarea,
        fechaCreacion: string,
        fechaFinalizacion: string | null = null
    ) {
        this._titulo = titulo;
        this._descripcion = descripcion;
        this._estado = estado;
        this._dificultad = dificultad;
        this._fechaCreacion = fechaCreacion;
        this._fechaFinalizacion = fechaFinalizacion;
    }

-----

Tambien 
