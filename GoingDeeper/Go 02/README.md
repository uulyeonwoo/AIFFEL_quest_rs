# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 성연우
- 리뷰어 : 김준석


# PRT(Peer Review Template)
- [O]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
      -> 루브릭1 : cutmix와 mixup기법을 Resnet50분류기에 성공적으로 적용하였는가? O  
      <img width="388" alt="image" src="https://github.com/user-attachments/assets/4f458fca-ebd4-44d6-b0e2-ead949c8186f" /><br>
      -> 루브릭2 : 다양한 실험을 통해 테스크에 최적인 Agu기법을 찾았는가? O  
      <img width="551" alt="image" src="https://github.com/user-attachments/assets/85e80b54-9c9b-4d2e-9670-69034a9a70d3" /><br>
      <img width="648" alt="image" src="https://github.com/user-attachments/assets/ee54fdd6-e6ce-4ba6-9f2a-2557fba87071" /><br>
      -> 루브릭3 : 여러가지 Aug기법을 적용한 결과를 체계적으로 비교분석 하였는가? O  
      <img width="656" alt="image" src="https://github.com/user-attachments/assets/f259678f-8712-4694-bde4-c012ef1197be" /><br>

- [O]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부  
    <img width="665" alt="image" src="https://github.com/user-attachments/assets/dbd10f54-be6d-4b24-9451-10b73fd2dc35" /><br>
    -> 조건에 맞게, 각 Augmentation 기법을 적용할 수 있도록 코드를 작성하셨습니다.  

- [O]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부  
        <img width="550" alt="image" src="https://github.com/user-attachments/assets/99075a90-8651-4b5e-a58a-e10e073a6308" /><br>
        -> mix_2_labels 함수에 image_a.shape이 필요한 부분을 찾아 잘 디버깅 하셨습니다.  
 
        
- [O]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
          <img width="658" alt="image" src="https://github.com/user-attachments/assets/1ed33e29-ed5d-4275-a7d0-509e0558857b" /><br>

        
- [O]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부  
        <img width="356" alt="image" src="https://github.com/user-attachments/assets/09b161c2-2f4b-459a-857b-a0513744f9eb" /><br>
        -> 모델이 어떻게 구현되어 있는지, 보기 쉽게 잘 작성하셨습니다.  


# 회고(참고 링크 및 코드 개선)
```
코드가 깔끔하고, 회고 및 설명이 잘 작성되어 있어 리뷰하기에 좋았습니다!
이번 프로젝트도 고생 많으셨습니다:)
```
