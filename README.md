# L7 — Hell/Heaven

[English](#english) · [Español](#español) · [Italiano](#italiano)

---

## English

### Author's note — why light?

I'm convinced the true matrix of the universe isn't *data* — it's **functions**.

We're used to thinking of numbers as things, as finished data. But look closer. π and √2 aren't really numbers you can write down: they're **functions** — processes, rules that never end. You never actually hold √2 as a datum; you only ever hold *the operation that produces it*. An irrational number isn't a finished object sitting in memory, it's a machine that keeps generating itself. Behind every "thing" there is an operation that brings it into being.

So before the data, there are the functions.

And when I try to picture a function, my mind doesn't see an abstract formula — it sees a **filter**. Something that light passes through and comes out changed. A prism doesn't *store* a number; it *does* something to a ray. That's what every operation in this little app is: a function made visible as an optical filter.

### What it is

A white beam on a black background passes through a prism. You choose *what happens to it* by pressing a button — and every button is a mathematical operation turned into an optical filter. The idea is simple: **make mathematics visible**. An operation is a function — it takes something in and gives something else out — exactly like a prism takes a white ray and turns it into a spectrum.

### Play it

**https://mannilab.github.io/l7/**

No install, no server: it runs entirely in your browser.

### The 13 filters

| Symbol | Operation | Optical filter | Effect on the light |
|:------:|-----------|----------------|---------------------|
| `=` | Identity | Perfect glass | The light passes through unchanged. |
| `+` | Addition | Convergence | Beams merge — the light comes out **doubled**. |
| `−` | Subtraction | Absorption | Part of the light is removed — it comes out **dimmed**. |
| `×` | Multiplication | Amplifier | One input, **many coherent outputs**. |
| `÷` | Division | Splitter | One beam is **split into several branches**. |
| `▲` | Prism | Prism | White light is **decomposed into the spectrum**. |
| `±` | Reflection | Mirror | The light **reflects and reverses direction** (the inverse, ×−1). |
| `xⁿ` | Power | Resonator | Intensity grows **nonlinearly** — one huge, bright beam. |
| `log` | Logarithm | Compressor | **Reduces huge differences** in intensity. |
| `eˣ` | Exponential | Propagator | A small light **rapidly invades space**. |
| `\|x\|` | Absolute value | Rectifier | **Removes polarity**, keeps the magnitude. |
| `∿` | Fourier | Harmonic prism | **Decomposes light into its frequencies**. |
| `≷` | Chaos | Sensitive amplifier | **Tiny variations, completely different outcomes**. |

### A note on the metaphor

An arithmetic operation is a function: it maps an input to an output. Fix one of its two arguments — "double", "halve", "square" — and it becomes a filter that waits only for the light to transform. That is exactly what a prism does: you don't give it two things, you give it a ray and it gives you a spectrum. The visuals here are **metaphors** chosen to *feel* the meaning of each operation (adding, removing, amplifying, spreading), not exact physical simulations — but the intuition they carry is faithful.

### How it works

A single self-contained `index.html` — vanilla **JavaScript** drawing on a **canvas**, no libraries, no build step. The scene renders a light source, a glass prism, and the output beams with additive glow; each operation defines a set of rays (count, angle, colour, intensity) that are revealed from the prism outward.

### License

MIT — free to use, modify and share.

*Show it to your kids: mathematics isn't learned, it's seen.*

---

## Español

### Nota del autor — ¿por qué la luz?

Estoy convencido de que la verdadera matriz del universo no son los *datos*, sino las **funciones**.

Estamos acostumbrados a pensar los números como cosas, como datos terminados. Pero mira más de cerca. π y √2 no son en realidad números que puedas escribir: son **funciones** — procesos, reglas que no terminan nunca. Nunca posees √2 como un dato; solo posees *la operación que lo produce*. Un número irracional no es un objeto terminado guardado en la memoria, es una máquina que sigue generándose a sí misma. Detrás de cada "cosa" hay una operación que la hace existir.

Así que antes de los datos, están las funciones.

Y cuando intento imaginar una función, mi mente no ve una fórmula abstracta: ve un **filtro**. Algo que la luz atraviesa y de lo que sale transformada. Un prisma no *guarda* un número; le *hace* algo a un rayo. Eso es cada operación de esta pequeña app: una función hecha visible como filtro óptico.

### Qué es

Un haz de luz blanca sobre fondo negro atraviesa un prisma. Tú eliges *qué le sucede* pulsando un botón — y cada botón es una operación matemática convertida en filtro óptico. La idea es simple: **hacer visible la matemática**. Una operación es una función — toma algo a la entrada y devuelve algo distinto a la salida — igual que un prisma toma un rayo blanco y lo convierte en un espectro.

### Juégalo

**https://mannilab.github.io/l7/**

Sin instalación, sin servidor: funciona por completo en tu navegador.

### Los 13 filtros

| Símbolo | Operación | Filtro óptico | Efecto sobre la luz |
|:-------:|-----------|---------------|---------------------|
| `=` | Identidad | Vidrio perfecto | La luz pasa sin cambios. |
| `+` | Suma | Convergencia | Los haces se unen — la luz sale **duplicada**. |
| `−` | Resta | Absorción | Se elimina parte de la luz — sale **atenuada**. |
| `×` | Multiplicación | Amplificador | Una entrada, **muchas salidas coherentes**. |
| `÷` | División | Divisor | Un haz se **divide en varias ramas**. |
| `▲` | Prisma | Prisma | La luz blanca se **descompone en el espectro**. |
| `±` | Reflexión | Espejo | La luz **se refleja e invierte su dirección** (la inversa, ×−1). |
| `xⁿ` | Potencia | Resonador | La intensidad crece de forma **no lineal** — un único haz enorme. |
| `log` | Logaritmo | Compresor | **Reduce diferencias enormes** de intensidad. |
| `eˣ` | Exponencial | Propagador | Una pequeña luz **invade rápidamente el espacio**. |
| `\|x\|` | Valor absoluto | Rectificador | **Elimina la polaridad**, conserva la magnitud. |
| `∿` | Fourier | Prisma armónico | **Descompone la luz en sus frecuencias**. |
| `≷` | Caos | Amplificador sensible | **Variaciones mínimas, resultados completamente distintos**. |

### Una nota sobre la metáfora

Una operación aritmética es una función: asocia una entrada a una salida. Fija uno de sus dos argumentos — "duplicar", "partir por la mitad", "elevar al cuadrado" — y se convierte en un filtro que solo espera la luz para transformarla. Eso es exactamente lo que hace un prisma: no le das dos cosas, le das un rayo y te devuelve un espectro. Las imágenes aquí son **metáforas** elegidas para *sentir* el significado de cada operación (sumar, quitar, amplificar, repartir), no simulaciones físicas exactas — pero la intuición que transmiten es fiel.

### Cómo funciona

Un único archivo autónomo `index.html` — **JavaScript** puro dibujando sobre un **canvas**, sin librerías ni compilación. La escena dibuja una fuente de luz, un prisma de vidrio y los haces de salida con brillo aditivo; cada operación define un conjunto de rayos (número, ángulo, color, intensidad) que se revelan desde el prisma hacia fuera.

### Licencia

MIT — libre de usar, modificar y compartir.

*Muéstraselo a tus hijos: la matemática no se aprende, se ve.*

---

## Italiano

### Nota dell'autore — perché la luce?

Sono convinto che la vera matrice dell'universo non siano i *dati*, ma le **funzioni**.

Siamo abituati a pensare i numeri come cose, come dati finiti. Ma guarda più da vicino. π e √2 non sono davvero numeri che puoi scrivere: sono **funzioni** — processi, regole che non finiscono mai. Non possiedi mai √2 come un dato; possiedi soltanto *l'operazione che lo produce*. Un numero irrazionale non è un oggetto finito depositato in memoria, è una macchina che continua a generarsi. Dietro ogni "cosa" c'è un'operazione che la fa esistere.

Quindi prima dei dati, ci sono le funzioni.

E quando provo a immaginare una funzione, la mia mente non vede una formula astratta: vede un **filtro**. Qualcosa che la luce attraversa e da cui esce trasformata. Un prisma non *conserva* un numero; *fa* qualcosa a un raggio. È questo ogni operazione di questa piccola app: una funzione resa visibile come filtro ottico.

### Che cos'è

Un fascio di luce bianca su fondo nero attraversa un prisma. Tu scegli *cosa gli accade* premendo un pulsante — e ogni pulsante è un'operazione matematica trasformata in filtro ottico. L'idea è semplice: **rendere visibile la matematica**. Un'operazione è una funzione — prende qualcosa in entrata e restituisce qualcos'altro in uscita — esattamente come un prisma prende un raggio bianco e lo trasforma in uno spettro.

### Provalo

**https://mannilab.github.io/l7/**

Niente installazione, niente server: gira interamente nel browser.

### I 13 filtri

| Simbolo | Operazione | Filtro ottico | Effetto sulla luce |
|:-------:|------------|---------------|--------------------|
| `=` | Identità | Vetro perfetto | La luce passa invariata. |
| `+` | Somma | Convergenza | I fasci si uniscono — la luce esce **raddoppiata**. |
| `−` | Sottrazione | Assorbimento | Una parte della luce è rimossa — esce **attenuata**. |
| `×` | Moltiplicazione | Amplificatore | Un ingresso, **molte uscite coerenti**. |
| `÷` | Divisione | Ripartitore | Un fascio è **suddiviso in più rami**. |
| `▲` | Prisma | Prisma | La luce bianca si **scompone nello spettro**. |
| `±` | Riflessione | Specchio | La luce **si riflette e inverte la direzione** (l'inversa, ×−1). |
| `xⁿ` | Potenza | Risonatore | L'intensità cresce in modo **non lineare** — un unico fascio enorme. |
| `log` | Logaritmo | Compressore | **Riduce enormi differenze** di intensità. |
| `eˣ` | Esponenziale | Propagatore | Una piccola luce **invade rapidamente lo spazio**. |
| `\|x\|` | Valore assoluto | Raddrizzatore | **Elimina la polarità**, conserva la magnitudine. |
| `∿` | Fourier | Prisma armonico | **Scompone la luce nelle sue frequenze**. |
| `≷` | Caos | Amplificatore sensibile | **Variazioni minime, esiti completamente diversi**. |

### Una nota sulla metafora

Un'operazione aritmetica è una funzione: associa un ingresso a un'uscita. Fissa uno dei suoi due argomenti — "raddoppia", "dimezza", "eleva al quadrato" — e diventa un filtro che aspetta solo la luce da trasformare. È esattamente ciò che fa un prisma: non gli dai due cose, gli dai un raggio e ti restituisce uno spettro. Le immagini qui sono **metafore** scelte per *sentire* il significato di ogni operazione (aggiungere, togliere, amplificare, ripartire), non simulazioni fisiche esatte — ma l'intuizione che trasmettono è fedele.

### Come funziona

Un unico file autonomo `index.html` — **JavaScript** puro che disegna su un **canvas**, senza librerie né compilazione. La scena disegna una sorgente di luce, un prisma di vetro e i fasci in uscita con bagliore additivo; ogni operazione definisce un insieme di raggi (numero, angolo, colore, intensità) rivelati dal prisma verso l'esterno.

### Licenza

MIT — libero di usare, modificare e condividere.

*Mostratelo ai vostri bambini: la matematica non si impara, si vede.*
