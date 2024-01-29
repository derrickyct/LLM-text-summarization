# text-summarization
## Dataset
This project uses hugging face dataset [Big Patent][1] snippest d: Textiles; Paper for training, testing and validating because of the limitations.

Data Fields
- description: detailed description of patent.
- abstract: Patent abastract.

Data Splits
| category | train | validation | test |
|:--------:|:-----:|:----------:|:----:|
|     d    | 10164 |     565    |  565 |

## Hugging Face Model
1. [t5-base][2]
2. [sshleifer/distilbart-cnn-12-6][3]

[1]: https://huggingface.co/datasets/big_patent            "Big Patent"
[2]: https://huggingface.co/t5-base                        "t5-base"
[3]: https://huggingface.co/sshleifer/distilbart-cnn-12-6  "sshleifer/distilbart-cnn-12-6"
