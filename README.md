Deep Averaging Networks (DAN) for Sentiment Classification

Overview

This Assignment implements Deep Averaging Networks (DAN) for sentiment classification. The models are built and trained using Python 3 and PyTorch. This README provides instructions on how to run the code for different parts of the assignment, as well as how to install necessary dependencies.

PyTorch (latest version, CPU support is sufficient)

Run the following commands same directory as main.py, BOWmodel.py, sentiment_data.py, DANmodels.py, and bpe.py

## PART 1 A Commands

```bash
python main.py --model DAN --embedding_dim 50
python main.py --model DAN --embedding_dim 300

python main.py --model DAN1 --embedding_dim 50
python main.py --model DAN2 --embedding_dim 50

python main.py --model DAN1 --embedding_dim 300
python main.py --model DAN2 --embedding_dim 300

```
## PART 1 B Commands

```bash
python main.py --model DAN --random_init --embedding_dim 50
python main.py --model DAN --random_init --embedding_dim 300

python main.py --model DAN1 --random_init --embedding_dim 50
python main.py --model DAN2 --random_init --embedding_dim 50

python main.py --model DAN1 --random_init --embedding_dim 300
python main.py --model DAN2 --random_init --embedding_dim 300

```

## PART 2 A Commands

```bash

python main.py --model DAN --embedding_dim 50 --use_bpe --vocab_size 1000
python main.py --model DAN --embedding_dim 50 --use_bpe --vocab_size 2000
python main.py --model DAN --embedding_dim 50 --use_bpe --vocab_size 3000
python main.py --model DAN --embedding_dim 50 --use_bpe --vocab_size 5000
python main.py --model DAN --embedding_dim 50 --use_bpe --vocab_size 8000


python main.py --model DAN1 --embedding_dim 50 --use_bpe --vocab_size 1000
python main.py --model DAN1 --embedding_dim 50 --use_bpe --vocab_size 2000
python main.py --model DAN1 --embedding_dim 50 --use_bpe --vocab_size 3000
python main.py --model DAN1 --embedding_dim 50 --use_bpe --vocab_size 5000
python main.py --model DAN --embedding_dim 50 --use_bpe --vocab_size 8000


```



