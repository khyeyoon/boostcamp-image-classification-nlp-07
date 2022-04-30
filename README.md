# [네이버 부스트캠프 AI Tech 3기] Mask Classification Competition

본 대회에 대한 세부적인 내용은 아래 링크를 통해 확인하실 수 있습니다.

https://guiltless-tiglon-d23.notion.site/Mask-Classification-Wrap-up-report-e571501616324083ae3aa79fa439234b

# Model

<img src="https://github.com/boostcampaitech3/level1-image-classification-level1-nlp-07/blob/main/hy_baseline/model.JPG">

그림과 같은 구조로 앞단의 레이어들은 동일한 네트워크를 사용하여 파라미터를 공유하도록 만들었고, 뒷단의 레이어들은 각각의 문제(나이, 성별, 마스크 착용 여부)를 풀기 위한 독립된 네트워크로 구현하였습니다.

아래 저장소에서 모델 코드를 자세히 확인하실 수 있습니다.

https://github.com/khyeyoon/Head-Sharing-Multi-Class-Classification

# Train

```python
cd src
python train.py
```
