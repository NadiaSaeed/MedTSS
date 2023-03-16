# MedTSS
MedTSS employs a sequence of components to process a journal article, with each component gradually contributing to information extraction for the summarizer 
to use. Figure 1 presents a high-level overview of the MedTSS module and its ability to address the challenges associated with PTMs generating abstractive summaries without additional training. The MedTSS accepts a
plain scientific journal article with its keywords and MeSH terms in either TXT or XML document. The current open-source release consists of the following
steps that process the source text for effective information extraction. 

• Pre-processor and sentences selector

• Multiple concepts reinforcer

• Preface entity hallucination detector and handler

• Sentence Ordering

• Lexical simplification of clinical and medical terms
## MedTSS Summarization
We provide MedTSS working on five samples of HTSS testing dataset. HTSS reported, there top-five generated summaries, that we used to compared with MedTSS(PTMs) generated summaries. Code avaliable in 'MedTSS-Summarization.ipynb' file.
## MedTSS Sentence Ordering
MedTSS ordered there generated summaries of k-conceptual groups based on cosine similarity computed between the sentences od the original text and generated summaries. Code avaliable in 'MedTSS-OrderedSummary.ipynb' file.
## MedTSS ESM metric
MedTSS introduced a new matric to compared the named entities similarity between the ground-truth summaries and the generated summaries using ESM. Code is avaliable in 'MedTSS-ESM.ipynb' file.
## MedTSS Lexical simplification of clinical and medical terms
MedTSS text simplification task code in 'MedTSS_Simplification.ipynb'.
