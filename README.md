# 음식 객체 인식 모델

### 프로젝트 기간
2021/12/10 ~ 2021/12/21

# 프로젝트 배경

- 사진으로 음식을 구분하고 체크할 수 있다면 건강한 식단을 관리할때  도움이 될 것이라고 생각
- 음식을 인식할 수 있게 된다면 음식 정보가 담긴 DB에 연결해 활용 할 수 있을 것이라고 생각했다

# 프로젝트 진행

### 프로젝트 발표 동영상  

[프로젝트 발표 영상](https://drive.google.com/file/d/1WvoXdaTTsPVa6b-lS1GW1rOyzZ4wfK33/view?usp=sharing)  

[프로젝트 모델 시연 영상](https://drive.google.com/file/d/1uxq52Dr76WTt0G1kHIRyPFXkRv4ao0Sz/view?usp=sharing)
- 첫 번째 영상에 포함되어있는 부분입니다

### 데이터

[AI 허브](https://aihub.or.kr/aidata/30747/download)

- AI 허브의 음식 이미지 데이터

### 결과

음식 객체 인식을 하는 객체인식 모델 구현

- 객체 인식을 할 수 있으나 정확도가 많이 떨어진다
    
    ![image](https://user-images.githubusercontent.com/86823305/171422034-b36ed335-95b9-4134-bb8c-43ed348282ba.png)
    
   
   - 30시간을 추가로 학습한 결과
    ![image](https://user-images.githubusercontent.com/86823305/171422115-bb36b7c0-d48d-4aa2-940a-7eeda52486ed.png)

    

### 프로젝트 한계 및 문제점
![image](https://user-images.githubusercontent.com/86823305/171422247-edd49f00-aa13-413f-8232-f6a2f99489b4.png)

- 스스로 할 수 있는지 없는지도 모르는걸 어떻게든 할 수 있을것같은 느낌으로 무작정 계획해버린것
- 그래픽카드의 낮은 성능으로 오히려 코랩이 더 빠른데도 로컬환경으로 학습 한것
- 안되는걸 빠르게 판단하고 다른방향으로 갔어야했는데 시간을 너무 허비한점
- 이전 프로젝트때 데이터가 부족했다고 무작정 큰데이터를 골라 코랩을 사용할 수 없게 되었고 로컬에서도 용량 확보와 라벨링부터 문제를 겪은것
