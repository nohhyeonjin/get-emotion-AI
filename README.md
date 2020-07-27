# getEmotionAI
얼굴 표정에서 감정을 인식함
## Dataset
- [dataset download link](https://www.kaggle.com/deadskull7/fer2013)
- data example

emotion|pixels|usage
---|---|---
2|231 212 156 164 174 138 161 173 182 200 106 38 39 74 138 161 164 179 190 201 210 216 220 224 222 218...|Training
- emotion

![주석 2020-07-27 152604](https://user-images.githubusercontent.com/47866105/88510271-a3dcb180-d01d-11ea-80e7-a6a4b334f528.jpg)

## CNN
- 데이터 전처리와 CNN 신경망의 구조는 논문을 참고하여 구현했으며 epoch은 14번 돌렸습니다.
- [참고 논문 (특징 연결과 깊이별 분리 컨볼루션을 이용한 효율적인 얼굴 감정인식 CNN)](https://github.com/nohhyeonjin/getEmotionAI/files/4980326/CNN.pdf)
## 결과
<img width="300" alt="acc loss" src="https://user-images.githubusercontent.com/47866105/88512528-ac36eb80-d021-11ea-9124-c8d854f2d4fa.png">


