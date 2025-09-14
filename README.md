# Comparative-Analysis-of-Automatic-Neural-Metrics

*Aniruddha Mukherjee, Vikas Hassija, Vinay Chamola, and Karunesh Kumar Gupta*

**BLEURT** a recently introduced metric that employs **BERT**, a potent pre-trained language model to assess how well candidate translations compare to a reference translation in the context of machine translation outputs. While traditional metrics like **BLEU** rely on lexical similarities, **BLEURT** leverages **BERT**'s semantic and syntactic capabilities to provide more robust evaluation through complex text representations. However, studies have shown that **BERT**, despite its impressive performance in natural language processing tasks can sometimes deviate from human judgment, particularly in specific syntactic and semantic scenarios. Through systematic experimental analysis at the word level, including categorization of errors such as lexical mismatches, untranslated terms, and structural inconsistencies, we investigate how **BLEURT** handles various translation challenges. Our study addresses three central questions: What are the strengths and weaknesses of **BLEURT**, how do they align with BERT's known limitations, and how does it compare with the similar automatic neural metric for machine translation, BERTScore? Using manually annotated datasets that emphasize different error types and linguistic phenomena, we find that **BLEURT** excels at identifying nuanced differences between sentences with high overlap, an area where **BERTScore** shows limitations. Our systematic experiments, provide insights for their effective application in machine translation evaluation.



Please make sure that you clone the BELURT repository from the following link:
https://github.com/google-research/bleurt

<p style="text-align: center;">
  <img src="https://github.com/annimukherjee/Neural-Metric-Eval-Framework/assets/85307430/02f3e83b-2cd8-4ef5-88cf-6cdc90473cf4" width="500" alt="grab-emnlp-WMT - transaction - Online LaTeX Editor Overleaf-Overleaf Online LaTeX Editor-002397@2x">
<br>
  
  <img src="https://github.com/annimukherjee/Neural-Metric-Eval-Framework/assets/85307430/09355ecb-4bda-45e4-8111-31832aa7e7c1" width="500" alt="grab-emnlp-WMT - transaction - Online LaTeX Editor Overleaf-Overleaf Online LaTeX Editor-002399@2x">
</p>
