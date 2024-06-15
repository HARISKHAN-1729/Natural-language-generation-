# Natural-language-generation-

**Project Description**

This project aims to fine-tune a T5 model for natural language generation tasks, using  data preprocessing, data augmentation, domain adaptation, and reranking approaches. The primary goal is to enhance model performance by integrating different techniques and loss functions to handle specific challenges like exposure bias during inference.

**Key Objectives:**

- Implement multiple data preprocessing variants to convert table data into string format.
- Fine-tune the T5 model using various configurations and test prefixes for handling different output types.
- Explore and implement data augmentation techniques to improve model robustness.
- Integrate a domain adaptation strategy using an additional Masked Language Modeling (MLM) loss term.
- Apply a reranking approach during inference to mitigate exposure bias by using contrastive loss.

**Installation**

To set up this project, clone the repository and install the required packages:

```bash
  git clone github.com/HARISKHAN-1729/Natural-language-generation-
  cd Natural-language-generation-
  pip install -r requirements.txt
```

