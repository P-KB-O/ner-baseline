# ner-baseline
some NER baseline

here, you can use three algorithms for NER TASK

1. hmm
2. crf
3. bilstm
4. bilstm+crf

## Usage

training:
``` shell
python main.py
```

testing:
``` shell
python test.py
```

you can get output information in the terminal, and see confusion matrix heatmap plot in `image` dir
