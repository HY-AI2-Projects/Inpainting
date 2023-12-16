# 논문소개

2016년 CVPR에 발표된 "Context Encoders: Feature Learning by Inpainting" 논문은 이미지 inpainting(이미지 복원)을 사용하여 특징 학습에 중점을 둔 연구입니다. 
이 논문은 컴퓨터 비전과 딥 러닝 분야에서 주목을 받았습니다.

논문의 핵심 아이디어는 이미지의 일부를 가려서 가려진 부분을 예측하는 네트워크를 훈련시켜 전체 이미지의 특징을 학습하는 것입니다. 
이를 통해 모델은 가려진 부분에서 누락된 정보를 예측하도록 강제되며, 결과적으로 전체 이미지의 의미 있는 특징을 학습할 수 있습니다.

주요 개념과 기술적인 세부 사항은 다음과 같습니다:

*Inpainting Network: 논문에서 제안된 모델은 inpainting network로 구성되어 있습니다. 이 네트워크는 주어진 이미지에서 일부 영역을 가려진 상태로 입력받고, 해당 영역을 예측하여 복원합니다.

*Context Encoders: 이 모델은 "Context Encoders"로 불리며, 가려진 영역 주변의 문맥을 이용하여 예측을 수행합니다. 이렇게 함으로써 모델은 더 넓은 이미지 문맥을 이해하고, 특징을 추출하는 데 도움을 받습니다.

*Self-Supervised Learning: 논문은 지도 학습 없이 자기 지도 학습(self-supervised learning)에 중점을 두고 있습니다. 가려진 영역을 원래 이미지로 복원하는 작업은 명시적인 레이블이 필요하지 않기 때문에 자기 지도 학습의 한 형태로 간주됩니다.

*Discriminative Feature Learning: 이 방법은 특히 이미지에서 의미 있는 특징을 학습하는 데 중점을 둡니다. 모델은 주어진 문맥에서 중요한 정보를 추출하여 누락된 부분을 최대한 정확하게 복원하도록 훈련됩니다.

이 논문은 이미지 inpainting을 통한 자기 지도 학습의 아이디어를 소개하고, 이를 통해 특징 학습에 성공적으로 활용하는 방법을 탐구하고 있습니다.

# 참고자료
Context Encoders: Feature Learning by Inpainting 논문

<https://github.com/HyungjoByun/Projects>
