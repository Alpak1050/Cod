# Cod

class Persona {
  constructor() {
    // Variables privadas
    let edad;
    let nombre;
    let telefono;

    // Getter y setter para la propiedad 'edad'
    this.getEdad = function () {
      return edad;
    };

    this.setEdad = function (nuevaEdad) {
      edad = nuevaEdad;
    };

    // Getter y setter para la propiedad 'nombre'
    this.getNombre = function () {
      return nombre;
    };

    this.setNombre = function (nuevoNombre) {
      nombre = nuevoNombre;
    };

    // Getter y setter para la propiedad 'telefono'
    this.getTelefono = function () {
      return telefono;
    };

    this.setTelefono = function (nuevoTelefono) {
      telefono = nuevoTelefono;
    };
  }
}

// Crear un objeto persona
const persona = new Persona();

// Establecer los valores de las propiedades utilizando los setters
persona.setEdad(25);
persona.setNombre("Juan");
persona.setTelefono("123456789");

// Obtener los valores de las propiedades utilizando los getters
console.log("Edad:", persona.getEdad());
console.log("Nombre:", persona.getNombre());
console.log("Teléfono:", persona.getTelefono());
