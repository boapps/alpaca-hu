# alpaca-hu

Magyar nyelvű instruction-tuned modell, fordított alpaca adathalmazból.

## Adathalmaz fordítása

deepl segítségével fordítottam ~6500 mintát [egy tisztított alpaca adathalmazból](https://github.com/gururise/AlpacaDataCleaned).

Az adathalmaz a `datasetv2.csv`-ben található.

## Modell finomhangolása

LoRA finomhangolást csináltam a 8-bitre kvantált [PULI-GPT-3SX](https://huggingface.co/NYTK/PULI-GPT-3SX)-hez, így 12 GB VRAM elég volt a művelethez.
