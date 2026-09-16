# Ejercicio-1Modelado-basico-e-instanciacion-Persona-
[Uploading <?xml version="1.0" encoding="UTF-8"?>
<module type="JAVA_MODULE" version="4">
  <component name="NewModuleRootManager" inherit-compiler-output="true">
    <exclude-output />
    <content url="file://$MODULE_DIR$">
      <sourceFolder url="file://$MODULE_DIR$/src" isTestSource="false" />
    </content>
    <orderEntry type="inheritedJdk" />
    <orderEntry type="sourceFolder" forTests="false" />
  </component>
</module>Ej 2.1.1.iml…]()

<img width="1290" height="244" alt="image" src="https://github.com/user-attachments/assets/612a902f-7a73-4db3-9d31-cbd23a2f171b" />

LOGICA DE RESOLUCION
- **La clase _persona_** funciona como el molde que define los datos (nombre y edad) que tendrá cada persona en el programa
- **Instanciación en la memoria:** Al usar el operador _new_, se solicita espacio dinámico e independiente en la memoria heap para construir cada objeto concreto
- **Operador de acceso punto (.):** Permite ingresar directamente a las variables internas de cada objeto para asignar y leer sus datos

FUNCIONAMIENTO 
- **Definicion de la clase:** Se declara la estructura _persona_ con sus atributos publicos
- **Creacion del objeto:** Al ejecutar _Persona persona1 = new Persona();_ 
  - La JVM reserva memoria en el heap para el objeto
  - se ejecuta el constructor por defecto, asignando valores iniciales (null a nombre y 0 a edad)
  - La direccion de memoria del objeto se guarda en la variable de referencia _persona1_
- **Asignación de datos:** Al ejecutar _persona1.nombre = "Ana";_ se viaja a la ubicación de memoria de _persona1_ y se actualiza su atributo. Los datos de _persona2_ se guardan en otra dirección independiente del heap
- **Lectura:** Se utiliza la notación de punto (_persona1.nombre_) para extraer los calores de cada instancia y mostrarlos por consola
