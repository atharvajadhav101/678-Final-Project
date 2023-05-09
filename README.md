# 678-Final-Project
By Atharva Jadhav (G01336920), Prajwal Desai(G01326781) and Suzzana Rafi(G01269347).

Our project focuses on mitigating Gender Bias in Dataset across all languages. We have made use of Masking method and Counterfactual data augmentation.

We implement the Masking of Gender-associated words and pronouns and nouns to train our MLMs to perform unbiased learning. In simple terms, we try different combinations of masking Gender associated words like Mother, Father, Dad, Son, etc., and Personal and Professional Pronouns like he, his, her, she, himself, herself, etc., and also Singular Nouns and Plural Nouns like doctor/doctors etc.   

To complement this method and to cover another debiasing method, we manually perform counterfactual data augmentation for languages like Bengali and Portuguese.

# Executables
[requirements.txt](https://github.com/atharvajadhav101/678-Final-Project/blob/main/requirements.txt) file give all the necessary library and version to be installed before execution of our project.

# Recreating the Baseline
To recreate the [Gender Bias in Masked Language Models for Multiple Languages (Kaneko et al., NAACL 2022)](https://aclanthology.org/2022.naacl-main.197/), you can try and execute the [Baseline_All_Lang.py](https://github.com/atharvajadhav101/678-Final-Project/blob/main/Baseline_All_Lang.py) for all languages to run Parallel_multilingual_data files and [Baseline_MT.py](https://github.com/atharvajadhav101/678-Final-Project/blob/main/Baseline_MT.py) for Author_translated_data files. 

# Our Implementation

You can find all the executable files in Implementation folder to run our masking method implementation and [score_calculator.ipynb](https://github.com/atharvajadhav101/678-Final-Project/blob/main/Implementation/score_calculator.ipynb) for the manually annotated datasets of Bengali and Portuguese respectively.

Please run [masking.ipynb](https://github.com/atharvajadhav101/678-Final-Project/blob/main/Implementation/masking.ipynb) for customized masking of gender-associated words and pronouns and nouns.

You can execute [translator.ipynb](https://github.com/atharvajadhav101/678-Final-Project/blob/main/Implementation/translator.ipynb) to translate one's own dataset into any required language.
