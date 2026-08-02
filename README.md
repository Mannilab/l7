# L7 — Hell/Heaven

## Author's note — why light?

I'm convinced the true matrix of the universe isn't *data* — it's **functions**.

We're used to thinking of numbers as things, as finished data. But look closer. π and √2 aren't really numbers you can write down: they're **functions** — processes, rules that never end. You never actually hold √2 as a datum; you only ever hold *the operation that produces it*. An irrational number isn't a finished object sitting in memory, it's a machine that keeps generating itself. Behind every "thing" there is an operation that brings it into being.

So before the data, there are the functions.

And when I try to picture a function, my mind doesn't see an abstract formula — it sees a **filter**. Something that light passes through and comes out changed. A prism doesn't *store* a number; it *does* something to a ray. That's what every operation in this little app is: a function made visible as an optical filter.

---

A white beam on a black background passes through a prism. You choose *what happens to it* by pressing a button — and every button is a mathematical operation turned into an optical filter. The idea is simple: **make mathematics visible**. An operation is a function — it takes something in and gives something else out — exactly like a prism takes a white ray and turns it into a spectrum.

## Play it

👉 **https://mannilab.github.io/l7/**

No install, no server: it runs entirely in your browser.

## The 13 filters

| Symbol | Operation | Optical filter | Effect on the light |
|:------:|-----------|----------------|---------------------|
| `=` | Identity | Perfect glass | The light passes through unchanged. |
| `+` | Addition | Convergence | Beams merge — the light comes out **doubled**. |
| `−` | Subtraction | Absorption | Part of the light is removed — it comes out **dimmed**. |
| `×` | Multiplication | Amplifier | One input, **many coherent outputs** (a fan of rays). |
| `÷` | Division | Splitter | One beam is **split into several branches**. |
| `▲` | Prism | Prism | White light is **decomposed into the spectrum** (rainbow). |
| `±` | Reflection | Mirror | The light **reflects and reverses direction** (the inverse, ×−1). |
| `xⁿ` | Power | Resonator | Intensity grows **nonlinearly** — one huge, bright beam. |
| `log` | Logarithm | Compressor | **Reduces huge differences** in intensity (a tight, uniform fan). |
| `eˣ` | Exponential | Propagator | A small light **rapidly invades space** (a wide cone). |
| `\|x\|` | Absolute value | Rectifier | **Removes polarity**, keeps the magnitude (all rays folded to one side). |
| `∿` | Fourier | Harmonic prism | **Decomposes light into its frequencies** (discrete spectral lines). |
| `≷` | Chaos | Sensitive amplifier | **Tiny variations, completely different outcomes** (scattered, flickering rays). |

## A note on the metaphor

An arithmetic operation is a function: it maps an input to an output. Fix one of its two arguments — "double", "halve", "square" — and it becomes a filter that waits only for the light to transform. That is exactly what a prism does: you don't give it two things, you give it a ray and it gives you a spectrum. The visuals here are **metaphors** chosen to *feel* the meaning of each operation (adding, removing, amplifying, spreading), not exact physical simulations — but the intuition they carry is faithful.

## How it works

A single self-contained `index.html` — vanilla **JavaScript** drawing on a **canvas**, no libraries, no build step. The scene renders a light source, a glass prism, and the output beams with additive glow; each operation defines a set of rays (count, angle, colour, intensity) that are revealed from the prism outward.

## License

MIT — free to use, modify and share.

---

*Show it to your kids: mathematics isn't learned, it's seen.* 🌈
