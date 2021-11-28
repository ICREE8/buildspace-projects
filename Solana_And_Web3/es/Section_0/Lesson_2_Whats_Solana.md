# Lesson_2_Whats_Solana

Vamos a pasar mucho tiempo sumergiéndonos en Solana en este proyecto y si lo construyes tendrás mucho tiempo para aprender sobre qué diablos es Solana.

No te preocupes, abarcaremos a un montón de cosas como por que Solana tiene tarifas de gasolina bajas, cómo es que funciona realmente rápido, etc.

No quiero que pasemos mucho tiempo en teoría aquí.

Lo último que quiero que hagas es que vayas por la madriguera de blockchain y comiences a ver toneladas de videos aleatorios de YT o publicaciones de Wikipedia. Creo que hacer esas cosas es bueno, pero solo termina este proyecto primero. ¡Entonces baja por la madriguera del conejo!

Prometo que toda tu investigación tendrá mucho más sentido una vez que despegues este proyecto.

Sin embargo, creo que es valioso tener una comprensión básica de algunos de los conceptos y obtener una imagen de alto nivel de cómo funcionan las cosas en Solana. Entonces, hagámoslo :).

👩‍💻 Programas
En Solana, escribimos "programas de Solana".

Nota: ¡Esto es como un contrato inteligente si conoce Ethereum!

Un programa de Solana es solo un fragmento de código que vive en la cadena de bloques. La cadena de bloques es un lugar donde cualquiera puede ejecutar código por una tarifa. Puede pensar en la cadena de bloques como AWS o Heroku. Pero, en lugar de estar dirigidas por una gran corporación, estas cadenas están dirigidas por "mineros". En el mundo de Solana los llamamos "validadores".

🏦 Cuentas
En Solana, los programas son "apátridas". Esto es muy diferente de Ethereum. En Ethereum, tu escribes "contratos inteligentes" y estos a su vez mantienen un estado en el que se puede almacenar datos sobre variables en los contratos inteligentes.

En Solana, el funcionamiento es que los usuarios tienen "cuentas" y los programas de Solana pueden interactuar con las "cuentas" de los usuarios. Un usuario puede poseer miles de cuentas. La forma más fácil de pensar en una cuenta es como un archivo. Los usuarios pueden tener muchos archivos diferentes. Los desarrolladores pueden escribir programas que puedan comunicarse con estos archivos.

El programa en sí no contiene los datos de un usuario. El programa solo habla con "cuentas" que contienen los datos del usuario.

¡Esa es prácticamente toda la teoría que realmente necesitamos repasar ahora mismo! Si todavía no tiene sentido, ¡no se preocupe! Esto me tomó un tiempo comprenderlo. Creo que tiene más sentido cuando nos metemos en el código.

👀 "¿Debería usar Solana o Ethereum?"
Hmmmm. Esta es una pregunta difícil. También puede ser una pregunta incorrecta. Lo siento, sé que no es la respuesta que desea, pero la respuesta real es: depende.

Por ejemplo, hoy en día, realmente no hablamos sobre qué idioma del servidor backend es el "mejor".

Simplemente elegimos el que nos resulte más cómodo o el que tenga más sentido dado nuestro caso de uso. Por ejemplo, si su objetivo es la velocidad, escribir su backend en Go puede tener sentido. Si solo desea hacer algo, algo como Node o Ruby podría ser mejor.

Así es como deberíamos ver las diferentes cadenas de bloques. Cada uno tiene sus pros y sus contras, y debe elegir el que se adapte a su caso de uso o nivel de comodidad. Solana es conocida como la cadena de bloques súper rápida y de bajo costo de gas, ¡y en este proyecto lo manipularemos para que pueda tener una idea de cómo le gusta! Forme su propia opinión !!

⛓ Futuro de cadena cruzada.
Cada blockchain tiene sus pros y sus contras. No creo que ninguna de las grandes cadenas de bloques sea "la mejor". Y no es necesario que solo uno sea el mejor. La competencia es buena. Un mundo donde solo Apple fabrica teléfonos inteligentes sería una mierda. Un mundo donde solo Krispy Kreme hiciera donas sería una mierda. Necesitamos mucha gente que impulse la industria a su manera.

Esta es solo una toma personal, pero creo que nos estamos moviendo rápidamente hacia un mundo en el que vamos a tener muchas cadenas de bloques diferentes (que ya están sucediendo ahora). En realidad, esto es algo bueno. En lugar de que una cadena de bloques sea un claro ganador, tenemos muchas cadenas diferentes, cada una con sus propias especialidades.

Pero tendremos puentes que permitirán que diferentes cadenas hablen entre sí.

Eso significa que puede implementar su programa en Solana y hacer que se comunique con un contrato en una cadena de bloques diferente como Ethereum, Avalanche, Polygon, etc. Por ejemplo, puede comprar un NFT en Ethereum y luego moverlo a Solana si lo desea. O, tal vez, podría tener un puente que le permita mover fácilmente tokens de la cadena Solana a la cadena Ethereum.

Lo que sería una mierda es si tuviéramos más de 100 cadenas diferentes y ninguna de ellas pudiera hablar entre sí. Luego, cada cadena se convierte en un jardín amurallado donde la transferencia de datos entre cadenas es casi imposible. Los usuarios pierden la libertad de elección.

Los puentes son cada vez más populares. ¡Siéntete libre de leer esta publicación cuando quieras! Pero por ahora, empecemos a construir
