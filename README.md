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
