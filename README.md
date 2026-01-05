This is the code repository for the paper "Mapping the meaning of Human Dignity at the European Court of Human Rights: An Unsupervised Learning Approach".

Initial data downloaded from [https://echr-opendata.eu/download/](ECHR open data). 

* Notebook #1 (`1_echr_extraction.ipynb`) handles the initial extraction of data.
* Notebook #2 (`2_data_preprocessing_pipeline.ipynb`) handles the preprocessing of the data.
* Notebook #3 (`3_eda.ipynb`) covers exploratory data analysis.
* Notebook #4 (`4_lda_run.ipynb`) runs LDA topic modeling.
* Notebook #5 (`5_lsi_run.ipynb`) runs LSI topic modeling.
* Notebook #6 (`6_nmf_run.ipynb`) runs NMF topic modeling.
* Notebook #7 (`7_bertopic_chunks_run.ipynb`) runs BERTopic on chunked fact texts.
* Notebook #8 (`8_bertopic_summaries_run.ipynb`) runs BERTopic on BERT summaries.
* Notebook #9 (`9_evaluation_and_plots.ipynb`) aggregates evaluation metrics and generates plots.
* Notebook #10 (`10_preprocessing_tests.ipynb`) validates preprocessing outputs.
