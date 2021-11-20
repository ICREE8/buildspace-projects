# Lesson_2_Whats_Solana

En este proyecto vamos a pasar bastante tiempo sumergidos en Solana y tendrás mucho tiempo para aprender sobre qué diablos es Solana **mientras realmente desarrollas** en ella.

No te preocupes, explicaremos un montón de cosas como por ejemplo: como es que Solana tiene tarifas de gasolina bajas**(gas-fees)**, cómo es realmente rápido, etc.

**No quiero que pasemos mucho tiempo en teoría aquí.**

Lo último que quiero que hagas es que te vayas por la cueva del conejo de **Blockchain** y comiences a ver toneladas de videos aleatorios de YT o publicaciones de Wikipedia. Creo que hacer esas cosas es bueno, **pero solo termina este proyecto primero.** ¡Y despues bajas por la cueva del conejo!

Prometo que toda tu investigación tendrá mucho más sentido una vez que terminés este proyecto.

Sin embargo, creo que es valioso tener una comprensión básica de algunos de los conceptos y así obtener una imagen de alto nivel de cómo funcionan las cosas en Solana. Entonces, hagámoslo :).

### 👩‍💻 Programas
En Solana, escribimos "programas de Solana".

*Nota: ¡Esto es como un contrato inteligente si ya conoces Ethereum!*

Un programa de Solana es solo un fragmento de código que vive en la cadena de bloques. La cadena de bloques es un lugar donde cualquiera puede ejecutar código pagando una tarifa. Puedes pensar en la cadena de bloques como AWS o Heroku. Pero, en lugar de estar dirigidas por una gran corporación, estas cadenas están dirigidas por "mineros". En el mundo de Solana los llamamos "validadores"**(validators)**.

### 🏦 Cuentas
En Solana, los programas son "sin estado"**(stateless)**. **Esto lo hace muy diferente de Ethereum**. En Ethereum, tu escribes "contratos inteligentes" y los contratos realmente mantienen un estado en el que verdaderamente puedes almacenar datos sobre variables directamente en los contratos.

En Solana, el funcionamiento es que los usuarios tienen "cuentas" y los programas de Solana pueden interactuar con estas  "cuentas" de los usuarios. Un usuario puede poseer miles de cuentas en la cadena de bloques de Solana. La forma más fácil de pensar en una cuenta es pensar en un archivo. Los usuarios pueden tener muchos archivos diferentes. Y los desarrolladores pueden escribir programas que pueden comunicarse con estos archivos.

**El programa en sí no contiene los datos de un usuario. El programa solo habla con "cuentas" que contienen los datos del usuario.**

¡Esa es prácticamente toda la teoría que realmente necesitamos repasar en este momento! Si todavía no tiene sentido, ¡no te preocupes! Esto me tomó un tiempo comprenderlo. Creo que tiene más sentido cuando nos empecemos con el código.

### 👀 "¿Debería usar Solana o Ethereum?"
Hmmmm. Esta es una pregunta difícil. Y también puede ser una pregunta incorrecta. **La respuesta real es: depende**. Lo siento, sé que no es la respuesta que buscabas.
Por ejemplo, hoy en día, realmente no hablamos sobre qué **idioma de servidor de soporte**(backend) es el "mejor".

Simplemente elegimos el que nos resulte más cómodo o el que tenga más sentido dependiendo de nuestro proyecto. Por ejemplo, si su objetivo es la velocidad, desarrollar tu backend en Go puede que tenga sentido. Si solo deseas desarrollar algo que despegue rapido, utilizar algo como Node o Ruby podría ser mejor.

Así es como deberíamos ver las diferentes cadenas de bloques. Cada una tiene sus pros y sus contras, y debe elegir el que se adapte a tu caso de uso, o tu nivel de conocimiento. Solana es conocida como la cadena de bloques súper rápida y de bajo costo de gas, ¡y en este proyecto lo vamos a manipular para que puedas tener una idea de que tanto te gusta! **Forma tu propia opinión!!**

###⛓ Futuro de cadena transversal(cross-chain).
Cada blockchain tiene sus pros y sus contras. No creo que ninguna de las grandes cadenas de bloques sea **la mejor**. Y **no es necesario** que solo una sea la mejor. La competencia siemmpre es buena. Un mundo donde solo Apple fabrica teléfonos inteligentes sería una mierda. Un mundo donde solo Krispy Kreme hiciera donas sería una mierda. Necesitamos mucha gente que impulse la industria a su manera.

**Esta es solo una idea personal**,  pero creo que nos estamos moviendo rápidamente hacia un mundo en el que vamos a tener muchas cadenas de bloques diferentes (algo que ya está sucediendo).  Esto es algo bueno en realidad. En lugar de que una cadena de bloques sea un claro ganador, tenemos muchas cadenas diferentes, cada una con sus propias especialidades.

**Pero tendremos puentes (https://wiki.polkadot.network/docs/learn-bridges) que permitirán que diferentes cadenas se comuniquen entre sí.**

Eso significa que puedes desarrollar tu programa en Solana y hacer que se comunique con un contrato en una cadena de bloques diferente como Ethereum, Avalanche, Polygon, etc. Por ejemplo, puedes comprar un NFT en Ethereum y luego moverlo a Solana si lo deseas. O, tal vez, podrías tener un puente que te permita mover fácilmente tokens de la cadena Solana a la cadena Ethereum.

Lo que sería una **mierda** es si tuviéramos más de 100 cadenas diferentes y **ninguna** de ellas se pudieran comunicar entre sí. Luego, cada cadena se convertiría en un jardín amurallado donde la transferencia de datos entre cadenas seria casi imposible. Los usuarios perderían la libertad de elección.

Los puentes son cada vez más populares. ¡Siéntete libre de leer (https://medium.com/1kxnetwork/blockchain-bridges-5db6afac44f8) esta publicación cuando quieras! Pero por ahora, empecemos a desarrollar
