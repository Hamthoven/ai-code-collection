# Projects

## 개요

GPT 2 (en) 기반으로 미세 조정을 통해 면접 대본을 짜도록 미세 조정하는 코드를 정리해두었습니다. (2024.02.01)


## 코드에서 참고할만한 요소
- Hugging Face 데이터 로드
- Pytorch로 NLP 미세 조정
- Tensorflow로 NLP 미세 조정
- Tensorflow에서 GPU를 사용하기 위한 코드

## 기본 정보

- 모델: GPT2
- 데이터셋: [HuggingFace/Glavin001/startup-interviews](https://huggingface.co/datasets/Glavin001/startup-interviews)


## 주의사항

- 데이터셋은 554개의 질의응답으로 구성되어 있으며 스타트업에 초점이 맞춰져 있습니다. 목적에 따라 더 나은 미세 조정을 위하여 다른 데이터셋을 사용하는 것을 고려해보시길 바랍니다.
- Tensorflow를 이용한 코드(Tensorflow-GPT2-interview-script-generator.ipynb)는 Google Colab 기본 사양에서 학습 도중 세션이 종료됩니다.