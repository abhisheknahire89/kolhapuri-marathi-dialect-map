# Kolhapuri–Marathi Dialect Map

This repository contains a dialect normalization mapping for Kolhapuri Marathi to Standard Marathi.

## Purpose
Marathi speech varies significantly across regions. Kolhapuri Marathi has distinct lexical and phonetic forms that may appear in conversational speech but differ from standard Marathi used in clinical documentation and NLP systems.

This mapping is designed to be used as a **post-processing layer** after Automatic Speech Recognition (ASR), converting regional dialectal forms into standardized Marathi.

## Source
The mappings are derived from published linguistic research:

Nawadkar, D. S., Hankare, V. K., & Patole, S. U.  
*Comparative Study of Marathi Dialects in Kolhapur and Satara Region*  
International Journal of Modern Developments in Engineering and Science, 2023.

## Usage (Conceptual)
Audio → ASR (e.g., Whisper) → Raw Marathi text  
→ Dialect normalization using `kolhapuri_mapping.json`  
→ Clean Standard Marathi for downstream processing

## Status
Initial version based on academic literature.  
Intended to be extended using real-world conversational data.
