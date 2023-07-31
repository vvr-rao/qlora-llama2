# qlora-llama2

Writeup here: https://medium.com/@venkat.ramrao/fine-tuning-llama-2-using-qlora-and-a-cot-dataset-515f38b3972d

LLAMA-2 7B trained on a variety of datasets using QLORA. All datasets available on HuggingFace.
Conclusion: The 7B model seems to work well in extractive QA. It seems to not do so well in reasoning tasks. I'm planning to test out with a larger version of the model in the future.

1) kaist-ai/CoT-Collection.

Link to the github Repo and Paper tied to the dataset:
https://github.com/kaistAI/CoT-Collection
https://arxiv.org/abs/2305.14045

2) Pubmed-QA:
   https://pubmedqa.github.io/
   Link to Paper: https://arxiv.org/abs/1909.06146

3) DataBricks, Dolly
   databricks/databricks-dolly-15k

   
