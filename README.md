# thesis_ads_llm_cultural_alignment
Codefiles and datasets for thesis 'Can Large Language Models Simulate Human Cultural Values?'

Contains the following codefiles:

1_WVS_Exploratory_Analysis
- Exploratory analysis of the World Values Survey Wave 7 version 6.0 dataset
- Uses the dataset: WVS_Cross-National_Wave_7_csv_v6_0
- This dataset can be downloaded on the official World Values Survey website

2_Full_Run_OpenAI_Reasoning, 2_Full_Run_Mistral_Reasoning, 2_Full_Run_GLM_Reasoning
- Contains the full API run for all three models
- API keys have to be entered before running the code

3_Analysis
- Contains the analysis for the thesis
- Code for all four sub-questions
- Uses the datasets resulting from the API runs: wvs_results_openai_keywords, wvs_results_mistral_keywords, wvs_results_glm_keywords
- Uses the normalized WVS human means dataset gotten from the exploratory analysis: wvs_normalized_means
