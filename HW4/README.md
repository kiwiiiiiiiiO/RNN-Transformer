
## Open in Google Colab

Click the buttons below to open each homework notebook in Colab:

| Homework | Colab Link |
|----------|------------|
| **Test_4**  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kiwiiiiiiiiO/RNN-Transformer/blob/main/HW4/ViT_SWIN_test_4.ipynb) |
| **Test_5**  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kiwiiiiiiiiO/RNN-Transformer/blob/main/HW4/ViT_SWIN_test_5.ipynb) |
| **Test_6**  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kiwiiiiiiiiO/RNN-Transformer/blob/main/HW4/ViT_SWIN_test_6.ipynb) |
| **Test_7**  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kiwiiiiiiiiO/RNN-Transformer/blob/main/HW4/ViT_SWIN_test_7.ipynb) |
| **Test**  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kiwiiiiiiiiO/RNN-Transformer/blob/main/HW4/ViT_SWIN_test.ipynb) |


## Experiment Result


| Experiment | Model         | Params (M) | Finetune            | Accuracy |
|------------|---------------|------------|----------------------|----------|
| test_4     | ViT_base_p32  | 87.5M      | Partial Fine-tuning | 95.69%   |
|            | Swin_base     | 86.8M      |                      | 97.63%   |
| test_5     | ViT_tiny_p16  | 5.5M       | Partial Fine-tuning | 89.41%   |
|            | Swin_tiny     | 27.5M      |                      | 97.32%   |
| test_6     | ViT_large_p16 | 303.3M     | Partial Fine-tuning | 98.55%   |
|            | Swin_large    | 195.0M     |                      | 99.01%   |
| test_7     | ViT_base_p32  | 87.5M      | Full Fine-tuning    | 92.69%   |
|            | Swin_base     | 86.8M      |                      | 94.52%   |

