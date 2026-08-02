# L7 — Hell/Heaven

Un piccolo laboratorio visivo sulla luce. Una **luce bianca** su fondo nero attraversa un **filtro** (un prisma di vetro) e ne esce trasformata: ogni pulsante corrisponde a un'operazione matematica, e mostra cosa fa quel filtro alla luce.

## Come si gioca

Premi un pulsante in basso e osserva il fascio d'uscita cambiare:

| Pulsante | Operazione | Effetto sulla luce |
|----------|------------|--------------------|
| `=` | Identità | La luce esce invariata |
| `+` | Somma | La luce esce raddoppiata (due fasci) |
| `−` | Sottrazione | La luce esce dimezzata (fioca e sottile) |
| `×` | Moltiplicazione | Un ingresso, molte uscite (ventaglio di raggi) |
| `÷` | Divisione | Il flusso si divide in pochi rami |
| `▲` | Prisma | La luce bianca si scompone nello spettro |

Nessuna vittoria né sconfitta: solo il piacere di vedere la luce piegarsi.

## Come funziona

Un unico file HTML autonomo (`index.html`), scritto in **JavaScript vanilla** con disegno su **canvas**. Niente librerie, niente server: tutto gira nel browser. La scena disegna la sorgente luminosa, il prisma e i fasci d'uscita con bagliori additivi; ogni operazione definisce un insieme di raggi (numero, angolo, colore, intensità) che vengono "rivelati" dal prisma verso destra.

## Provalo online

👉 https://mannilab.github.io/l7/

## Licenza

MIT — libero di usarlo, modificarlo e condividerlo.
