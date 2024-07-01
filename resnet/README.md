🔑 **PRT(Peer Review Template)**
- 코더: 손영철
- 리뷰어: 최호재

- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요? (완성도)** (2/3)
    > 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
    > 문제를 해결하는 완성된 코드란 프로젝트 루브릭 3개 중 2개, (퀘스트 문제 요구조건 등을 지칭). 해당 조건을 만족하는 부분의 코드 및 결과물을 캡쳐하여 사진으로 첨부
    - [x] ResNet-34, ResNet-50 모델 구현이 정상적으로 진행되었는가?
        - 블록함수 구현이 제대로 진행되었으며 구현한 모델의 summary가 예상된 형태로 출력되었다.![image](https://github.com/ivvve/aiffel-repo/assets/98305832/8ff7d0d4-3c42-4f4c-8ef4-60e46d37b6f0)
    - [x] 구현한 ResNet 모델을 활용하여 Image Classification 모델 훈련이 가능한가?
        - tensorflow-datasets에서 제공하는 cats_vs_dogs 데이터셋으로 학습 진행 시 loss가 감소하는 것이 확인되었다.![image](https://github.com/ivvve/aiffel-repo/assets/98305832/bf1cf097-a830-4ec7-b82d-0dd61ec079f6)
    - [ ] Ablation Study 결과가 바른 포맷으로 제출되었는가?
        - ResNet-34, ResNet-50 각각 plain모델과 residual모델을 동일한 epoch만큼 학습시켰을 때의 validation accuracy 기준으로 Ablation Study 결과표가 작성되었다.![image](https://github.com/ivvve/aiffel-repo/assets/98305832/c121e8e9-b590-4ab0-9e33-e4a2b56ac0fe)

- [x]  **2. 프로젝트에서 핵심적인 부분에 대한 설명이 주석(닥스트링) 및 마크다운 형태로 잘 기록되어있나요? (설명)** (3/5)
    - 프로젝트에서 핵심적인 부분에 대한 설명이 작성된 부분을 리뷰했습니다.
    - [ ]  모델 선정 이유
    - [ ]  Metrics 선정 이유
    - [x]  Loss 선정 이유: binary classification 에 대해서 binary_cross_entropy 를 사용함.
    - [x]  모델 구현, 실험을 위한 구현해야 할 부분들이 간결한 코드로 구현되었다. ![image](https://github.com/ivvve/aiffel-repo/assets/98305832/7d219931-5a05-4038-9fc3-04276fd6b531)

    - [x]  Residual Net 구현시, shortcut connection의 dimension matching 부분에 대한 설명: ![image](https://github.com/ivvve/aiffel-repo/assets/98305832/6bae2bac-d3ca-49f1-a71a-f1ad71f3e9a1)
 

- [x]  **3. 체크리스트에 해당하는 항목들을 모두 수행하였나요? (문제 해결)** (2/4)
    - [x]  데이터를 분할하여 프로젝트를 진행했나요? (train, validation, test 데이터로 구분)![image](https://github.com/ivvve/aiffel-repo/assets/98305832/6b9a8392-8c2f-4d98-a0e4-347ae2e96253) ![image](https://github.com/ivvve/aiffel-repo/assets/98305832/c4ba7a79-4adf-4544-9d0f-348f460a10e0)

    - [x]  하이퍼파라미터를 변경해가며 여러 시도를 했나요? (learning rate, dropout rate, unit, batch size, epoch 등)
        - batch size, input shape 에 대해서 변경해 봄.
    - [ ]  각 실험을 시각화하여 비교하였나요?
        - 시각화 부분은 진행하지 못했다.
    - [ ]  모든 실험 결과가 기록되었나요?
        - 모델 학습이 완료되지 않아서 결과가 기록되지 못한것 같습니다. 코드는 있음 ![image](https://github.com/ivvve/aiffel-repo/assets/98305832/51b9d864-f0c7-45b3-9317-a6a0300f0900)

- [ ]  **4. 프로젝트에 대한 회고가 상세히 기록 되어 있나요? (회고, 정리)** (0/4)
    - 회고가 없었습니다.
    - [ ]  배운 점
    - [ ]  아쉬운 점
    - [ ]  느낀 점
    - [ ]  어려웠던 점
     
### 리뷰어 후기
- 협업하고 싶은 마음이 드는 코드였습니다.
