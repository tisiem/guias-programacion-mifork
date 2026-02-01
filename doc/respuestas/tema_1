# TEMA 1. Clases y objetos

## 1. ¿Cuáles son las cuatro características básicas de la programación orientada a objetos? Describe brevemente cada una

### La abstracción consiste en modelar entidades del mundo real o conceptos del problema centrándose únicamente en los aspectos relevantes, ignorando los detalles innecesarios. En programación orientada a objetos (POO), esto se logra definiendo clases que representan conceptos y exponiendo solo la funcionalidad necesaria a través de métodos.

La encapsulación permite agrupar datos y comportamiento dentro de una misma entidad, el objeto, y controlar el acceso a sus componentes internos. De este modo se evita que el estado interno de un objeto sea modificado de forma incorrecta desde el exterior, favoreciendo la robustez y el mantenimiento del software.

La herencia permite crear nuevas clases a partir de otras existentes, reutilizando su código y ampliando o modificando su comportamiento. Esto facilita la extensión de programas sin necesidad de reescribir funcionalidades ya implementadas, promoviendo la reutilización.

El polimorfismo permite tratar objetos de diferentes clases de forma uniforme, siempre que compartan una misma interfaz o clase base. Gracias a esta característica, una misma operación puede comportarse de manera distinta según el objeto concreto sobre el que se aplique.


## 2. Cita cuatro lenguajes populares que permitan la programación orientada a objetos

### Uno de los lenguajes más conocidos que soporta la programación orientada a objetos es Java, diseñado desde su origen con este paradigma como eje central. Java obliga a estructurar prácticamente todo el código dentro de clases, lo que lo convierte en un buen ejemplo de POO “pura”.

C++ es otro lenguaje ampliamente utilizado que incorpora programación orientada a objetos como una extensión del lenguaje C. Permite mezclar estilos de programación procedimental y orientado a objetos, lo que resulta útil para transiciones desde C tradicional.

Python soporta la programación orientada a objetos de forma muy flexible, permitiendo definir clases, herencia y polimorfismo, aunque no obliga a usarlos. Esto lo hace adecuado tanto para pequeños scripts como para aplicaciones complejas.

C#, desarrollado por Microsoft, es un lenguaje moderno fuertemente orientado a objetos, con una sintaxis similar a Java y un amplio ecosistema. Está especialmente orientado al desarrollo de aplicaciones empresariales y de escritorio.


## 3. Los paradigmas anteriores a la POO, ¿Qué es la **programación estructurada**? y, todavía mejor, ¿Qué es la **programación modular**?

### La programación estructurada es un paradigma que organiza el código utilizando estructuras de control bien definidas como secuencia, selección (if) e iteración (while, for). Su objetivo principal es evitar el uso de saltos incontrolados (como goto) y mejorar la claridad, legibilidad y mantenibilidad del código.

Este paradigma se centra en dividir el programa en bloques lógicos que se ejecutan de forma ordenada. Lenguajes como C hacen un uso intensivo de la programación estructurada, basándose en funciones y estructuras de control claras.

La programación modular va un paso más allá y propone dividir el programa en módulos independientes, cada uno responsable de una parte concreta de la funcionalidad. Cada módulo expone una interfaz y oculta su implementación interna.

Aunque la programación modular mejora la organización del código, no encapsula datos y comportamiento de forma tan estricta como la POO. La programación orientada a objetos puede considerarse una evolución natural que integra y amplía estos conceptos.

## 4. ¿Qué tres elementos definen a un objeto en programación orientada a objetos?

### Un objeto en programación orientada a objetos se define, en primer lugar, por su estado, que está formado por los valores de sus atributos o variables internas. Este estado representa la información que caracteriza al objeto en un momento dado.

En segundo lugar, un objeto se define por su comportamiento, que viene determinado por los métodos que puede ejecutar. Estos métodos describen las acciones que el objeto puede realizar o las operaciones que se pueden efectuar sobre su estado.

Finalmente, un objeto posee una identidad, que lo distingue de otros objetos, incluso aunque tengan el mismo estado. Esta identidad permite que dos objetos con valores iguales sean considerados entidades diferentes dentro del programa.

## 5. ¿Qué es una clase? ¿Es lo mismo que un objeto? ¿Qué es una instancia? ¿Todos los lenguajes orientados a objetos manejan el concepto de clase?

### Una clase es una plantilla o definición que describe cómo serán los objetos de un determinado tipo. En ella se especifican los atributos y los métodos que tendrán los objetos creados a partir de esa clase.

Un objeto no es lo mismo que una clase. El objeto es una entidad concreta creada a partir de una clase, con valores específicos para sus atributos. A este proceso de creación se le llama instanciación, y el objeto resultante se denomina instancia de la clase.

No todos los lenguajes orientados a objetos manejan el concepto de clase de la misma forma. Algunos lenguajes, como Java o C++, están basados en clases, mientras que otros, como JavaScript, se basan en prototipos, aunque siguen siendo considerados orientados a objetos.


## 6. ¿Dónde se almacenan en memoria los objetos? ¿Es igual en todos los lenguajes? ¿Qué es la **recolección de basura**? 

### En lenguajes como Java, los objetos se almacenan normalmente en el montículo (heap), mientras que las variables que los referencian pueden almacenarse en la pila (stack). Esta separación permite gestionar la memoria de forma más flexible.

No es igual en todos los lenguajes. En C++, por ejemplo, un objeto puede almacenarse tanto en la pila como en el heap, dependiendo de cómo se cree. En Java, sin embargo, los objetos se crean siempre dinámicamente.

La recolección de basura (garbage collection) es un mecanismo automático de gestión de memoria que libera los objetos que ya no son accesibles desde el programa. Esto evita errores comunes en C/C++ como fugas de memoria o dobles liberaciones.


## 7. ¿Qué es un método? ¿Qué es la **sobrecarga de métodos**? 

### Un método es una función que pertenece a una clase y que define el comportamiento de los objetos de esa clase. A diferencia de las funciones en C, los métodos operan normalmente sobre el estado interno del objeto.

Los métodos pueden acceder directamente a los atributos del objeto al que pertenecen, lo que facilita la encapsulación y la coherencia entre datos y comportamiento.

La sobrecarga de métodos consiste en definir varios métodos con el mismo nombre pero con diferentes parámetros (número o tipo). El compilador selecciona automáticamente cuál usar según los argumentos proporcionados en la llamada.


## 8. Ejemplo mínimo de clase en Java, que se llame Punto, con dos atributos, x e y, con un método que se llame `calculaDistanciaAOrigen`, que calcule la distancia a la posición 0,0. Por sencillez, los atributos deben tener visibilidad por defecto. Crea además un ejemplo de uso con una instancia y uso del método

### class Punto {
    double x;
    double y;

    double calculaDistanciaAOrigen() {
        return Math.sqrt(x * x + y * y);
    }
}

class PruebaPunto {
    public static void main(String[] args) {
        Punto p = new Punto();
        p.x = 3;
        p.y = 4;
        double d = p.calculaDistanciaAOrigen();
        System.out.println(d);
    }
}



## 9. ¿Cuál es el punto de entrada en un programa en Java? ¿Qué es `static` y para qué vale? ¿Sólo se emplea para ese método `main`? ¿Para qué se combina con `final`?

### El punto de entrada de un programa en Java es el método main, cuya firma es public static void main(String[] args). Es el método que la máquina virtual ejecuta al iniciar el programa.

La palabra clave static indica que un método o atributo pertenece a la clase y no a una instancia concreta. Esto permite usarlo sin crear un objeto de esa clase.

static no se emplea únicamente para main; puede utilizarse en métodos utilitarios o constantes compartidas. Cuando se combina con final, se define un valor constante asociado a la clase que no puede modificarse.

## 10. Intenta ejecutar un poco de Java de forma básica, con los comandos `javac` y `java`. ¿Cómo podemos compilar el programa y ejecutarlo desde linea de comandos? ¿Java es compilado? ¿Qué es la **máquina virtual**? ¿Qué es el *byte-code* y los ficheros `.class`?

### Para compilar un programa Java desde la línea de comandos se utiliza javac, que genera un archivo .class. Para ejecutarlo se emplea el comando java, indicando el nombre de la clase principal.

Java es un lenguaje compilado, pero no a código máquina nativo. El código fuente se compila a byte-code, un formato intermedio independiente de la plataforma.

Este byte-code es ejecutado por la máquina virtual de Java (JVM), que actúa como intermediaria entre el programa y el sistema operativo. Esto permite que el mismo programa Java funcione en distintos sistemas sin recompilar.


## 11. En el código anterior de la clase `Punto` ¿Qué es `new`? ¿Qué es un **constructor**? Pon un ejemplo de constructor en una clase `Empleado` que tenga DNI, nombre y apellidos

### La palabra clave new se utiliza para crear un nuevo objeto en memoria. Al usarla, se reserva espacio para el objeto y se inicializa llamando a su constructor.

Un constructor es un método especial que tiene el mismo nombre que la clase y no devuelve ningún valor. Su función es inicializar el estado del objeto al crearse.

class Empleado {
    String dni;
    String nombre;
    String apellidos;

    Empleado(String dni, String nombre, String apellidos) {
        this.dni = dni;
        this.nombre = nombre;
        this.apellidos = apellidos;
    }
}


## 12. ¿Qué es la referencia `this`? ¿Se llama igual en todos los lenguajes? Pon un ejemplo del uso de `this` en la clase `Punto`

### La referencia this se utiliza para referirse al objeto actual, es decir, a la instancia sobre la que se está ejecutando un método. Permite distinguir entre atributos del objeto y variables locales con el mismo nombre.

No todos los lenguajes utilizan el mismo nombre; por ejemplo, en C++ se emplea this, mientras que en Python se utiliza self. El concepto, no obstante, es el mismo.

class Punto {
    double x;
    double y;

    void setX(double x) {
        this.x = x;
    }
}


## 13. Añade ahora otro nuevo método que se llame `distanciaA`, que reciba un `Punto` como parámetro y calcule la distancia entre `this` y el punto proporcionado

### double distanciaA(Punto otro) {
    double dx = this.x - otro.x;
    double dy = this.y - otro.y;
    return Math.sqrt(dx * dx + dy * dy);
}



## 14. El paso del `Punto` como parámetro a un método, es **por copia** o **por referencia**, es decir, si se cambia el valor de algún atributo del punto pasado como parámetro, dichos cambios afectan al objeto fuera del método? ¿Qué ocurre si en vez de un `Punto`, se recibiese un entero (`int`) y dicho entero se modificase dentro de la función? 

### En Java, los objetos se pasan por valor, pero el valor que se copia es la referencia al objeto. Esto significa que si se modifican los atributos del objeto dentro del método, los cambios sí afectan al objeto original.

Sin embargo, si se reasigna la referencia dentro del método, esa reasignación no afecta al objeto fuera del método. Este comportamiento suele describirse como “paso por valor de la referencia”.

En el caso de tipos primitivos como int, se copia directamente el valor. Por tanto, cualquier modificación del entero dentro del método no afecta al valor original.


## 15. ¿Qué es el método `toString()` en Java? ¿Existe en otros lenguajes? Pon un ejemplo de `toString()` en la clase `Punto` en Java

### El método toString() se utiliza para obtener una representación textual de un objeto. En Java, todas las clases heredan este método de la clase base Object.

Este método existe en otros lenguajes con nombres similares o funciones equivalentes, como __str__ en Python. Su objetivo es facilitar la depuración y la impresión de objetos.

class Punto {
    double x;
    double y;

    public String toString() {
        return "(" + x + ", " + y + ")";
    }
}


## 16. Reflexiona: ¿una clase es como un `struct` en C? ¿Qué le falta al `struct` para ser como una clase y las variables de ese tipo ser instancias?


### Una clase se parece a un struct en C en el sentido de que ambos agrupan datos relacionados bajo un mismo tipo. En C, un struct permite definir registros con distintos campos.

Sin embargo, a un struct le faltan elementos clave para ser una clase completa. No encapsula comportamiento de forma natural, no controla la visibilidad y no soporta herencia ni polimorfismo.

Además, las variables de tipo struct no tienen identidad ni métodos asociados de forma directa, mientras que las instancias de una clase sí integran datos y comportamiento en una única entidad.


## 17. Quitemos un poco de magia a todo esto: ¿Como se podría “emular”, con `struct` en C, la clase `Punto`, con su función para calcular la distancia al origen? ¿Qué ha pasado con `this`?

### En C, la clase Punto puede emularse mediante un struct y una función que reciba dicho struct como parámetro.

typedef struct {
    double x;
    double y;
} Punto;

double distanciaAOrigen(Punto p) {
    return sqrt(p.x * p.x + p.y * p.y);
}


En este caso, el concepto de this desaparece. El objeto sobre el que se opera se pasa explícitamente como argumento a la función, lo que evidencia que this no es magia, sino una referencia implícita que Java gestiona automáticamente.
