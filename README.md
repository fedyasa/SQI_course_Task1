# Практическое задание (1)

Описание архитектуры использованной нейронной сети:

Model(
  (L1): Linear(in_features=960, out_features=256, bias=True)
  (R1): ReLU()
  (L2): Linear(in_features=256, out_features=64, bias=True)
  (R2): ReLU()
  (L3): Linear(in_features=64, out_features=2, bias=True)
)

Описание действий, предпринятых для борьбы с переобучением:

Увеличение обучающей выборки за счет преобразований исходных изображений

