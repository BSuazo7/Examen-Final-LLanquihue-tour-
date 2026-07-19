Llanquihue Tour - Examen Final Transversal (EFT)
Descripción del Proyecto
Este proyecto representa la solución final para la gestión administrativa de la agencia de turismo Llanquihue Tour. El sistema ha sido diseñado bajo el paradigma de Programación Orientada a Objetos (POO) en Java, integrando de manera modular todas las funcionalidades requeridas para el examen final.

Principios de POO Aplicados
Encapsulamiento: Todos los atributos de las clases son privados, con acceso controlado mediante métodos getters y setters públicos.
Herencia: Se implementó una jerarquía clara con la clase base Persona y sus subclases Cliente y Empleado.
Composición: La clase Persona utiliza la clase Direccion para gestionar la ubicación de los usuarios.
Polimorfismo: Se utiliza la interfaz Registrable para tratar diferentes tipos de objetos (Cliente, Empleado, Producto) de forma unificada en una colección.
Interfaces: La interfaz Registrable define el contrato común para todas las entidades gestionables del sistema.
Sobrecarga y Sobrescritura: Se aplicó sobrescritura de métodos (@Override) y sobrecarga de métodos en la clase Cliente.
Estructura de Paquetes
model: Clases de dominio e interfaces.
data: Gestión de colecciones y lógica polimórfica.
utils: Herramientas para la carga de datos desde archivos externos.
app: Clase principal para la ejecución del sistema.
Instrucciones de Ejecución
Abra el proyecto en IntelliJ IDEA.
Verifique que la carpeta data_files se encuentre en la raíz del proyecto.
Ejecute la clase Main ubicada en src/app/Main.java.
El sistema cargará automáticamente los datos desde clientes.txt y mostrará el resumen polimórfico en la consola.
Desarrollado como parte de la Evaluación Final Transversal de Desarrollo Orientado a Objetos I.
