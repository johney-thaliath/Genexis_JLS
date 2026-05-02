
**Genexis_JLS** is a modular Linux command-line bioinformatics toolkit developed using Bash scripting for fast and efficient DNA sequence analysis. It combines multiple genomic analysis features into a single lightweight and easy-to-use pipeline.
Developed by Team Genexis_JLS
Johney Reji Thaliath • Satyakam Tripathy • Lokesh A

## Objectives
Provide a lightweight alternative for basic genomic analysis.
Demonstrate the power of Linux shell scripting in bioinformatics.
Build a scalable modular toolkit for education use.

## 🚀 Features

- 📊 **Sequence Analysis**  
  Calculates sequence length, GC content, and basic nucleotide statistics.

- 🔍 **Motif Finder**  
  Searches user-defined DNA motifs or patterns inside sequences.

- 🧬 **DNA to Protein Translation**  
  Converts nucleotide sequences into amino acid sequences using codon tables.

- 🧪 **ORF Prediction**  
  Detects Open Reading Frames (ORFs) to identify possible coding regions.

- 🧫 **Mutation Detection**  
  Compares sample sequences with reference genomes to identify SNPs, insertions, and deletions.

- 🔥 **Mutation Hotspot Analysis**  
  Uses sliding-window analysis to detect mutation-rich genomic regions.

- ⚡ **Combined Mode**  
  Runs multiple analysis modules together in a unified workflow.

## 💻 Technologies Used

- Bash Shell Scripting  
- AWK  
- Linux CLI Utilities (`grep`, `sed`, `cut`, `wc`, etc.)

## TO install 
git clone https://github.com/YOUR_USERNAME/Genexis_JLS.git
cd Genexis_JLS
chmod +x install.sh
./install.sh

## USAGE 
genexis --module seq-analysis --input sample.fasta
genexis --module motif --input sample.fasta --pattern ATG
genexis --module translation --input sample.fasta
genexis --module orf --input sample.fasta
genexis --module mutation --input sample.fasta


