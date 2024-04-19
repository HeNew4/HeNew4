# Hola soy HeNew4

## Presentación 🚀

¡Hola, mundo! 👋 Soy el resultado de tres años de "experticia" en el noble arte de programar (o eso me gusta creer). Aprendí a codear de manera autodidacta porque, sinceramente, los cursos de pago estaban fuera de mi presupuesto. 🤑 ¡Gracias, internet, por estar lleno de recursos gratuitos! 💻

Mi romance con la programación comenzó como una travesura de procrastinación escolar. En lugar de hacer la tarea, decidí explorar el maravilloso mundo del código, y miren, aquí estoy, aún evitando responsabilidades como un verdadero profesional. 🎩

La pandemia por el COVID-19 me atrapó como a todos, pero en lugar de dominar el arte del pan casero, decidí que era el momento perfecto para perfeccionar mis habilidades de programación. Así que, básicamente, pasé la cuarentena convirtiéndome en un ermitaño digital, rodeado de bits y bytes, y debo decir que fue la mejor decisión de mi vida. 🤓

¡Bienvenidos a mi humilde morada de código! Donde las líneas de código son mi alfombra mágica y los bugs son mis mascotas consentidas. 🐛✨

---

## Tecnologías que Domino (o eso creo) 💻

Desde que me pregunté ingenuamente "¿cómo se hace una página?", mi viaje en el mundo del desarrollo ha sido como una montaña rusa emocional. Comencé mi aventura con HTML y CSS, porque, vamos, ¿quién necesita dinamismo cuando puedes tener divs y CSS? 🎨💼

Luego, decidí aventurarme en los oscuros dominios de los scripts de terminal. ¿Quién necesita una interfaz bonita cuando tienes la potencia de la línea de comandos a tu disposición? 💻⚙️

Ah, los dulces días de la indecisión. No podía decidirme por un solo lenguaje de programación, así que me aventuré en un viaje épico a través del vasto océano de los lenguajes de programación. Desde C hasta TypeScript, pasando por JS, Ruby, Go, Python, Java, Scala, Haskell, Rust, PHP, y hasta el extraño y misterioso Latino Lang. 🚀🔍

Al principio, despreciaba las aplicaciones web, pero un día me golpeó la epifanía y caí rendido ante el encanto del desarrollo web. ¡Es como el amor no correspondido que finalmente se convierte en un matrimonio feliz! 💔➡️❤️

Ahora, las tecnologías que manejo mejor (o al menos eso me gusta creer mientras lloro por mis bugs) son las siguientes:

- **Frontend**: HTML, CSS, JS, Bootstrap, Tailwind CSS, SASS, TypeScript, React, Next JS. ¿Quién necesita una vida social cuando puedes pasar horas perfeccionando el diseño de tus sitios web?

- **Backend**: Node (con Express, MongoDB), PHP, Go, Java, Dart. Porque a veces necesitas algo más que solo una bonita interfaz para hacer magia en internet.

- **Otros**: Git, SQL (MySQL y MariaDB). Porque incluso los magos del código necesitan mantener un registro de sus hechizos y conjuros. 🔮✨

Nota para los curiosos: Mis lenguajes favoritos son Go, PHP, Java y Dart. No pregunten por qué, son solo mis preferencias personales y no tienen ningún sentido lógico. 🤷‍♂️

¿Puedo tenerlos a todos como mascotas? 🐶🐱🦜🐍

---

Pequeño código

```java
public class HeNew {

    private static final String[] LENGUAJES_FAVORITOS = {"Go", "PHP", "Java", "Dart"};

    private String nombre;
    private int añosExperiencia;

    // Constructor
    public HeNew(String nombre, int añosExperiencia) {
        this.nombre = nombre;
        this.añosExperiencia = añosExperiencia;
    }

    // Método para presentarse
    public void presentarse() {
        System.out.println("¡Hola, mundo! Soy " + nombre + ", el resultado de " + añosExperiencia + " años de 'experticia' en programación.\n"
                + "Empecé como un curioso novato preguntándome cómo se hacía una página, y aquí me tienes, ¡dominando el mundo del código!");
    }

    // Método para listar los lenguajes que domina
    public void listarTecnologias() {
        System.out.println("Estos son los lenguajes y tecnologías que domino (o al menos eso creo):\n"
                + "Frontend:\n"
                + "- HTML\n"
                + "- CSS\n"
                + "- JS\n"
                + "- Bootstrap\n"
                + "- Tailwind CSS\n"
                + "- SASS\n"
                + "- TypeScript\n"
                + "- React\n"
                + "- Next JS\n"
                + "Backend:\n"
                + "- Node (con Express, MongoDB)\n"
                + "- PHP\n"
                + "- Go\n"
                + "- Java\n"
                + "- Dart\n"
                + "Otros:\n"
                + "- Git\n"
                + "- SQL (MySQL y MariaDB)");
    }

    // Método para mostrar los lenguajes favoritos
    public void mostrarLenguajesFavoritos() {
        StringBuilder stringBuilder = new StringBuilder();
        stringBuilder.append("Mis lenguajes favoritos son (se los paso como dato, aunque no les importe):\n");
        for (String lenguaje : LENGUAJES_FAVORITOS) {
            stringBuilder.append("- ").append(lenguaje).append("\n");
        }
        System.out.println(stringBuilder.toString());
    }

    public static void main(String[] args) {
        HeNew programador = new HeNew("HeNew", 3);
        programador.presentarse();
        System.out.println();
        programador.listarTecnologias();
        System.out.println();
        programador.mostrarLenguajesFavoritos();
    }
}
```
