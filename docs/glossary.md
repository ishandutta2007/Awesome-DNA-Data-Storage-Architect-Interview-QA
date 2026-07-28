# Glossary: DNA Data Storage Terminology

## Terms A–M

**Array-based synthesis** – Massively parallel DNA synthesis technology producing many distinct short sequences simultaneously on a chip/array substrate, typically using phosphoramidite chemistry.

**Coverage depth** – Average number of independent reads obtained per individual oligo during sequencing-based retrieval.

**Depurination** – Hydrolytic loss of a purine base from the DNA backbone, a primary long-term DNA degradation mechanism creating abasic sites prone to strand breakage.

**Encapsulation** – Physical/chemical protection strategy (e.g., silica matrix embedding) shielding stored DNA from environmental degradation (moisture, oxygen, radiation).

**Enzymatic DNA synthesis** – Emerging synthesis technology using engineered enzymes (rather than purely chemical coupling) to build DNA sequences.

**Fountain code** – Class of rateless erasure codes (e.g., Luby Transform, Raptor codes) generating an unlimited stream of encoded symbols recoverable from any sufficiently large subset; well-matched to DNA storage's oligo-loss failure mode.

**GC content** – Fraction of a DNA sequence composed of guanine/cytosine bases; extreme GC content affects synthesis yield and sequencing accuracy.

**Homopolymer run** – Contiguous repeat of the same DNA base (e.g., "AAAA"); associated with elevated synthesis and sequencing error rates.

**Indel** – Insertion or deletion error, the dominant error type in DNA synthesis and many sequencing technologies, distinct from substitution errors.

**Long-read sequencing** – Sequencing technology (e.g., nanopore) generating substantially longer reads than short-read sequencing-by-synthesis platforms.

---

## Terms N–Z

**Oligo (oligonucleotide)** – A short, single- or double-stranded DNA molecule; the basic unit in which DNA storage data is typically synthesized and stored.

**Phosphoramidite chemistry** – The dominant, long-established chemical DNA synthesis method used in array-based synthesis platforms.

**Random access** – Capability to selectively retrieve specific stored data without processing the entire storage pool, typically implemented via PCR-based primer selection in DNA storage.

**Reed-Solomon code** – Classical error-correcting code widely used in conventional storage media, primarily designed for substitution errors; requires adaptation or replacement for DNA storage's indel-dominant channel.

**Short-read sequencing** – Sequencing-by-synthesis technology (e.g., Illumina-style) generating large numbers of short, high-accuracy reads.

**Sequencing coverage distribution** – The realistic, non-uniform distribution of actual read counts across different oligos in a pool, arising from PCR bias and synthesis yield variability.

---

## Abbreviations Reference

| Abbr | Full Form |
|------|-----------|
| ECC | Error-Correcting Code |
| LIMS | Laboratory Information Management System |
| LT code | Luby Transform code |
| PCR | Polymerase Chain Reaction |

---

**Note:** This glossary is not exhaustive. Refer to topic files and primary sources (DNA storage research literature, information theory/coding theory references) for authoritative definitions.
