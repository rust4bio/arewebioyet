---
title: Are we bio yet?
layout: single
permalink: /
---

🎉 Yes! 🎉🎉🎉

(but many projects are still work-in-progress)

The Rust bioinformatics ecosystem contains general, easy-to-use crates like [bio](https://crates.io/crates/bio), along with a plethora of crates for specific tasks.

# Ecosystem

## Libraries

Here you can find all sorts of bioinformatics crates that were created by the Rust community:

* **bio** ([repo](https://github.com/rust-bio/rust-bio) \| [docs](https://docs.rs/bio) \| [crates.io](https://crates.io/crates/bio)) - Implementations of many useful bioinformatics data structures and algorithms, including pattern matching, alignment, suffix arrays, BWT, FM-Index, and parsers for common file types.

* **coitrees** ([repo](https://github.com/dcjones/coitrees) \| [docs](https://docs.rs/coitrees/) \| [crates.io](https://crates.io/crates/coitrees)) - Cache oblivious interval tree implementation for very fast overlap queries of a static set of integer intervals, with genomic intervals in mind.

* **debruijn** ([repo](https://github.com/10XGenomics/rust-debruijn) \| [docs](https://docs.rs/debruijn) \| [crates.io](https://crates.io/crates/debruijn) - De Bruijn graph construction & path compression libraries.

* **fastq-rs** ([repo](https://github.com/aseyboldt/fastq-rs) \| [docs]() \| [crates.io]()) - A fast parser for FASTQ.

* **htsget-rs** ([repo](https://github.com/umccr/htsget-rs) \| [docs]() \| [crates.io]()) - GA4GH's [htsget](https://samtools.github.io/hts-specs/htsget.html) implementation.

* **needletail** ([repo](https://github.com/onecodex/needletail) \| [docs](https://docs.rs/needletail) \| [crates.io](https://crates.io/crates/needletail)) - Fast FASTX parsing and k-mer methods in Rust.

* **niffler** ([repo](https://github.com/luizirber/niffler)) - Simple and transparent support for compressed files.

* **noodles** ([repo](https://github.com/zaeleus/noodles) \| [docs](https://docs.rs/noodles) \| [crates.io](https://crates.io/crates/noodles)) - Pure Rust bioinformatics I/O libraries.

* **rust-htslib** ([repo](https://github.com/rust-bio/rust-htslib) \| [docs](https://docs.rs/rust-htslib) \| [crates.io](https://crates.io/crates/rust-htslib)) - Provides HTSlib bindings and a high level Rust API for reading and writing BAM files.

* **seq_io** ([repo](https://github.com/markschl/seq_io)  \| [docs]() \| [crates.io]()) - FASTA and FASTQ parsing and writing in Rust.

* **tripe_accel** ([repo]() \| [docs]() \| [crates.io](https://crates.io/crates/triple_accel)) - Rust edit distance routines accelerated using SIMD. Supports fast Hamming, Levenshtein, restricted Damerau-Levenshtein, etc. distance calculations and string search.


## Tools

### (Meta) Genomic analysis

* **bamtofastq** ([repo](https://github.com/10XGenomics/bamtofastq)) - Tool for converting 10x BAMs produced back into to FASTQ files.

* **bcl2fastr** ([repo](https://github.com/czbiohub/bcl2fastr)) - Faster bcl2fastq implementation.

* **finch** ([repo](https://github.com/onecodex/finch-rs)) - A genomic MinHashing implementation.

* **fmlrc2** ([repo](https://crates.io/crates/fmlrc)) - A tool for correcting long, noisy reads from short reads.

* **hyperex** ([repo](https://github.com/Ebedthan/hyperex)) - Hypervariable region primer-based extractor for 16S rRNA and other SSU/LSU sequences.

* **noodles-squab** ([repo](https://github.com/zaeleus/noodles-squab)) - Noodles squab performs gene expression quantification by counting the number of aligned records that intersects a set of features. Output can be the raw counts or normalized counts in TPM (transcripts per million) or FPKM (fragments per kilobase per million mapped reads).

* **perbase** ([repo](https://crates.io/crates/perbase)) - A highly parallelized utility for generating per-base level metrics.

* **rasusa** ([repo](https://github.com/mbhall88/rasusa)) - **Ra**ndomly **su**b**sa**mple sequencing reads to a specified coverage.

* **sabreur** ([repo](https://github.com/Ebedthan/sabreur)) - Fast, reliable and handy demultiplexing tool for fastx files.

* **sourmash** ([repo](https://github.com/dib-lab/sourmash)) - Quickly search, compare, and analyze genomic and metagenomic data sets.

* **yacrd** ([repo](https://github.com/natir/yacrd)) - Yet Another Chimeric Read Detector for long reads.

### Assembly

* **rust-mdbg** ([repo](https://github.com/ekimb/rust-mdbg)) - Minimizer-space de Bruijn graphs (mdBG) implementation for whole-genome assembly.

### Transcriptomics analysis

* **alevin-fry** ([repo](https://github.com/COMBINE-lab/alevin-fry)) - An efficient and flexible tool for processing single-cell sequencing data, currently focused on single-cell transcriptomics and feature barcoding.



### Variant calling

* **prosolo** ([repo](https://github.com/ProSolo/prosolo)) - A variant caller for multiple displacement amplified DNA sequencing data from diploid single cells.

* **varlociraptor** ([repo](https://crates.io/crates/varlociraptor)) - Varlociraptor implements a novel, unified fully uncertainty-aware approach to genomic variant calling in arbitrary scenarios.



# Contributing

You can use the [editor on GitHub](https://github.com/rust4bio/arewebioyet/edit/main/_pages/home.md) to contribute to this page. Feel free to list new bioinformatics crates or CLI! Of course, you can also contribute to the ecosystem by writing a new Rust crate.
