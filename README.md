# MedTSS
MedTSS employs a sequence of components to process a journal article, with each component gradually contributing to information extraction for the summarizer to use. The MedTSS accepts a plain scientific journal article with its keywords and MeSH terms in either TXT or XML document. The current open-source release consists of the following steps that process the source text for effective information extraction. 

• Pre-processor and sentences selector

• Multiple concepts reinforcer

• Preface entity hallucination detector and handler

• Sentence Ordering

• Lexical simplification of clinical and medical terms
## MedTSS Summarization
We provide MedTSS working on five samples of [HTSS testing dataset](https://github.com/slab-itu/HTSS/tree/master/data). [HTSS](https://www.sciencedirect.com/science/article/abs/pii/S0306457320308463?via%3Dihub) reported, there top-five generated summaries, that we used to compared with MedTSS(PTMs) generated summaries. Code avaliable in ['MedTSS-Summarization.ipynb'](https://github.com/NadiaSaeed/MedTSS/blob/main/MedTSS-Summarization.ipynb) file.
## MedTSS Sentence Ordering
MedTSS ordered there generated summaries of k-conceptual groups based on cosine similarity computed between the sentences od the original text and generated summaries. Code avaliable in ['MedTSS-OrderedSummary.ipynb'](https://github.com/NadiaSaeed/MedTSS/blob/main/MedTSS-OrderedSummary.ipynb) file.
## MedTSS ESM metric
MedTSS introduced a new matric to compared the named entities similarity between the ground-truth summaries and the generated summaries using ESM. Code is avaliable in ['MedTSS-ESM.ipynb'](https://github.com/NadiaSaeed/MedTSS/blob/main/MedTSS-ESM.ipynb) file.
## MedTSS Lexical simplification of clinical and medical terms
MedTSS text simplification task performed using [MedTCS module](https://github.com/NadiaSaeed/MedTCS). Code in ['MedTSS_Simplification.ipynb'](https://github.com/NadiaSaeed/MedTSS/blob/main/MedTSS_Simplification.ipynb).
