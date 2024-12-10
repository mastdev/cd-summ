# Cross Domain Adaptation for News Summarization
## NLP Project CS 7641
Collaborators - Sparsh Gupta, Saranya Kavileswarapu, Tanmay Chavan, Joel Jude

## File Descriptions

- `BART_Base_Evaluation.ipynb` - The Notebook sudies the performance of BART-Large pretrained model on the test dataset for all categories
- `BART_Training_Entertainment.ipynb` - BART-Large model trained on Entertainment category dataset from NEWSROOM and evalauted with ROUGE score across all target categories (Technology, Sports, Food, Architecture, Entertainment)
- `BART_Training_Technology.ipynb`- - BART-Large model trained on Technology category dataset from NEWSROOM and evalauted with ROUGE score across all categories (Technology, Sports, Food, Architecture, Entertainment)
- `BART_Training_Architecture.ipynb` - BART-Large model trained on Architecture category dataset from NEWSROOM and evalauted with ROUGE score across all target categories (Technology, Sports, Food, Architecture, Entertainment)
- `BART_Training_Sports.ipynb` - BART-Large model trained on Sports category dataset from NEWSROOM and evalauted with ROUGE score across all target categories (Technology, Sports, Food, Architecture, Entertainment)
- `BART_Training_Food.ipynb`- BART-Large model trained on Food category dataset from NEWSROOM and evalauted with ROUGE score across all target categories (Technology, Sports, Food, Architecture, Entertainment)
- `Injected_BART.ipynb` - BART-Large trained with Low Resource Cross Domain Adapation where training data consists of Technology samples as source domain and few gold-label samples from each of target domain. Performance is evalauted as ROUGE score on all categories (Technology, Sports, Food, Architecture, Entertainment)
- `Data_Injection_Preparation.ipynb` - Prepare data for Low Resource Cross Domain Adapation
- `newsroom_EDA.ipynb` - Exploration of NEWSROOM dataset and data preparation with URL Tagging with categories. Text and Summary statistics studies category wise.
- `bbcNewsSummary_EDA.ipynb` -  Exploration of BBC News Summary dataset. Text and Summary statistics studies category wise.
- `Newsroom_T5.ipynb` - Exploration of Summarization with T5 model
