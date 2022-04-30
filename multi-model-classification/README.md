# Multi-model-classification

* classification model 3개 사용

  - Mask classification model
  - Age classification model
  - Gender classification model

=> 3 model의 예측값을 합쳐서 최종 예측 클래스 결정

## train

* dataset.py에 3개의 classification을 위한 각각의 dataset이 정의되어 있음

```python
# mask classification
python train-mask.py
```

```python
# gender classification
python train-gender.py
```

```python
# age classification
python train-age.py
```

## inference

```python
python inference.py
```
