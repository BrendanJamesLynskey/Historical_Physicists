# Historical Physicists

Interactive presentations exploring the lives, discoveries, and lasting influence of history's greatest
physicists — from Galileo's telescopic revolution through Hawking's black hole thermodynamics. The series
traces the arc of physics from the birth of the scientific method through classical mechanics, electromagnetism,
thermodynamics, relativity, quantum mechanics, and modern cosmology.

**Live site:** [brendanjameslynskey.github.io/Historical_Physicists](https://brendanjameslynskey.github.io/Historical_Physicists)

## Presentations

### The Scientific Revolution

| # | Topic | Slides | Status |
|---|-------|--------|--------|
| 01 | [Galileo Galilei — The Father of Modern Science](Galileo/) | 17 | Complete |
| 02 | [Johannes Kepler — The Lawgiver of the Heavens](Kepler/) | 17 | Complete |
| 03 | [Christiaan Huygens — Waves, Clocks & the Rings of Saturn](Huygens/) | 17 | Complete |
| 04 | [Isaac Newton — The Principia & Universal Gravitation](Newton/) | 17 | Complete |

### 19th Century — Classical Physics

| # | Topic | Slides | Status |
|---|-------|--------|--------|
| 05 | [Michael Faraday — Fields, Induction & the Electric Age](Faraday/) | 17 | Complete |
| 06 | [James Clerk Maxwell — The Equations That Changed the World](Maxwell/) | 17 | Complete |
| 07 | [Ludwig Boltzmann — Entropy, Atoms & Statistical Mechanics](Boltzmann/) | 17 | Complete |

### Turn of the Century — The Old Quantum Theory

| # | Topic | Slides | Status |
|---|-------|--------|--------|
| 08 | [Marie Curie — Radioactivity & the Triumph of Persistence](Curie/) | 17 | Complete |
| 09 | [Max Planck — The Quantum Hypothesis & the Black-Body Revolution](Planck/) | 17 | Complete |
| 10 | [Ernest Rutherford — The Nuclear Atom & Transmutation](Rutherford/) | 17 | Complete |
| 11 | [Albert Einstein — Relativity, Quanta & the Geometry of Spacetime](Einstein/) | 17 | Complete |
| 12 | [Niels Bohr — The Atom, Complementarity & Copenhagen](Bohr/) | 17 | Complete |

### The Quantum Revolution

| # | Topic | Slides | Status |
|---|-------|--------|--------|
| 13 | [Erwin Schrödinger — Wave Mechanics, the Cat & What Is Life?](Schrodinger/) | 17 | Complete |
| 14 | [Werner Heisenberg — Uncertainty, Matrix Mechanics & the Quantum Leap](Heisenberg/) | 17 | Complete |
| 15 | [Paul Dirac — The Equation, Antimatter & Quantum Field Theory](Dirac/) | 17 | Complete |
| 16 | [Enrico Fermi — The Architect of the Nuclear Age](Fermi/) | 17 | Complete |

### Modern Physics

| # | Topic | Slides | Status |
|---|-------|--------|--------|
| 17 | [Richard Feynman — Diagrams, Path Integrals & the Joy of Finding Things Out](Feynman/) | 17 | Complete |
| 18 | [Stephen Hawking — Black Holes, Singularities & A Brief History](Hawking/) | 17 | Complete |

## Historical Lineages

The physicists in this collection form a deeply interconnected web of intellectual inheritance spanning four centuries. The landing page includes an SVG influence map tracing these connections.

### The Mechanical Universe

The story begins with Galileo's radical insistence that the book of nature is written in mathematics. His telescopic observations of Jupiter's moons, the phases of Venus, and sunspots demolished the Aristotelian cosmos, while his inclined-plane experiments established the mathematical laws of motion that would underpin all of classical physics. Kepler, working from Tycho Brahe's meticulous observations, discovered that planets move in ellipses — not circles — and that their motions obey precise mathematical laws. Huygens brought mathematical rigour to mechanics and optics, inventing the pendulum clock and proposing the wave theory of light. Newton unified the entire programme in the *Principia* (1687), showing that the same inverse-square law of gravitation governs the fall of an apple and the orbit of the Moon. His three laws of motion and the calculus he invented to express them became the foundation of physics for two centuries.

### The Electromagnetic Revolution

Faraday, the self-taught bookbinder's apprentice, discovered electromagnetic induction and introduced the concept of the field — arguably the most important conceptual shift in the history of physics. Where Newton saw forces acting at a distance, Faraday saw lines of force filling space. Maxwell translated Faraday's physical intuitions into precise mathematical equations, unifying electricity, magnetism, and optics into a single theory. His prediction that electromagnetic waves travel at the speed of light was confirmed by Hertz and led directly to radio, radar, and the modern telecommunications revolution. Boltzmann, meanwhile, showed that the laws of thermodynamics emerge from the statistical behaviour of vast numbers of atoms, establishing the bridge between the microscopic and macroscopic worlds — and fighting a bitter battle against those who denied the existence of atoms.

### The Quantum Revolution

The twentieth century opened with Planck's desperate hypothesis that energy comes in discrete quanta — a mathematical trick that inadvertently launched the quantum revolution. Curie's discovery of radioactivity revealed that atoms are not immutable, while Rutherford's gold foil experiment showed that the atom has a tiny, dense nucleus. Einstein's 1905 *annus mirabilis* produced special relativity, the photoelectric effect (confirming Planck's quanta), and Brownian motion (confirming atoms). His general relativity (1915) reimagined gravity as the curvature of spacetime. Bohr applied quantum ideas to atomic structure, explaining the hydrogen spectrum and establishing the Copenhagen institute that would train a generation of quantum physicists.

Heisenberg's matrix mechanics (1925) and Schrödinger's wave equation (1926) provided two equivalent formulations of quantum mechanics, while Heisenberg's uncertainty principle revealed a fundamental limit to what can be known simultaneously. Dirac unified quantum mechanics with special relativity, predicted the existence of antimatter, and laid the foundations of quantum field theory. Fermi, the last great physicist equally at home in theory and experiment, developed the statistics of half-integer spin particles, the theory of beta decay, and built the first self-sustaining nuclear reactor.

### The Modern Synthesis

Feynman reformulated quantum electrodynamics using path integrals and his celebrated diagrams, creating the most accurate theory in the history of science. His approach to physics — intuitive, visual, and fiercely independent — inspired generations. Hawking, working at the intersection of general relativity and quantum mechanics, showed that black holes are not entirely black: they emit thermal radiation and slowly evaporate, connecting gravity, quantum theory, and thermodynamics in a single result. His popular writings brought cosmology to millions.

## Source Texts

This series draws on the following canonical histories and biographies:

**Abraham Pais** — *Subtle is the Lord* (1982) and *Inward Bound* (1986). Pais's detailed
scientific biographies of Einstein and the development of particle physics set the standard
for historically rigorous physics writing.

**Richard Rhodes** — *The Making of the Atomic Bomb* (1986). Rhodes's Pulitzer-winning account
traces the physics and the human drama from Rutherford through Hiroshima.

**Helge Kragh** — *Quantum Generations* (1999). A comprehensive history of physics in the
twentieth century, balancing technical detail with institutional and social context.

**David Lindley** — *Boltzmann's Atom* (2001). The story of Boltzmann's fight for atomism
against the positivist establishment, and its tragic conclusion.

## Architecture

Each presentation is a single-file HTML deployment using [Reveal.js](https://revealjs.com/) loaded from CDN. No build step, no bundler, no local dependencies.

```
Historical_Physicists/
├── index.html              ← Landing page with influence map
├── README.md
│
│   ── THE SCIENTIFIC REVOLUTION ──
├── Galileo/index.html
├── Kepler/index.html
├── Huygens/index.html
├── Newton/index.html
│
│   ── 19TH CENTURY — CLASSICAL PHYSICS ──
├── Faraday/index.html
├── Maxwell/index.html
├── Boltzmann/index.html
│
│   ── TURN OF THE CENTURY ──
├── Curie/index.html
├── Planck/index.html
├── Rutherford/index.html
├── Einstein/index.html
├── Bohr/index.html
│
│   ── THE QUANTUM REVOLUTION ──
├── Schrodinger/index.html
├── Heisenberg/index.html
├── Dirac/index.html
├── Fermi/index.html
│
│   ── MODERN PHYSICS ──
├── Feynman/index.html
└── Hawking/index.html
```

## Design

Dark theme with consistent visual language across all 18 presentations:

- **Fonts:** Playfair Display (headings) · DM Sans (body) · JetBrains Mono (code/labels)
- **Background:** `#0a0a0f`
- **Accents:** Amber `#d4a053` · Green `#4ecca3` · Purple `#9b72cf` · Rose `#cf7272` · Blue `#5b8cd4` · Teal `#3ec9b0` · Gold `#e8b84b` · Copper `#c97b4b`
- **Diagrams:** Inline SVG with physical illustrations, concept maps, influence diagrams, and timelines
- **Slides:** 17 per presentation — title, biography, historical context, core contributions with diagrams, method, connections, controversy, legacy, applications, timeline, readings, closing quote
