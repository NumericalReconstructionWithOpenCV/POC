### 20170217 박성진
>GrabCut 알고리즘을 사용하여 전경(전체배경)을 제거하고 축구선수 "메시"의 몸만 추출

### 20170217 박동원
> 모서리 좌표를 서클로 체크하기 다른사람과 다른 방식으로 구현 좌표값 추출 하는 방법 vstack이용 

### 20170217 강지성
> 도형 안쪽의 좌표를 구해 거리를 구하고 선의 거리를 무시하는 형식으로 하려했으나 실패. 이미지 벡터변환 실습

### 20170217 김소연
> 도형의 모서리를 찾아서 그림을 그린다. 두께에 따라서 인식되는 모서리 갯수가 다르다는 사실을 알았다.

### 20170217 안병문
> 도형의 외곽선을 찾고, 외곽선 정보로 그 도형이 어떤 모양인지 판단하는 솔루션
> 격자 안에 있는 사각형만을 찾아서 그림에 표시함
> 격자 안에 있는 사각형을 이용해 격자 사이의 거리(격자의 두께)를 측정하는데 쓰일 수 있음

### 20170217-김현우
> 모서리 좌표 추출 중 거리가 가까운 모서리를 하나의 모서리로 인지 못하는 이슈 발생
> 소스 주석은 여행 다녀와서 작성 예정

###20170217 박성진
>3*3 검정 바탕의 하얀색 격자선을 빨간색으로 입힘으로써 인식해봤음
 
###20170215 박성진
>opencv K-Nearest neighbour(kNN) 알고리즘(머신러닝) 예제 실습 / Feature Matching 소스로 스타벅스 로고 연결 / opencv python detect object 소스를 이용하여 뭉크의 "절규" 그림을 인식해봤음 / Face Detection using Haar Cascades 오픈 소스를 사용하여 축구 선수 "호날두" 전면 얼굴 인식과 눈 인식을 성공했음


###20170215 김소연
>인구수에 따른 소득 회귀분석. (인터넷에서 예제 찾아서 주석처리함)
 opject detect(동원오빠랑 같은 예제. 주석은 스스로 달았음)

### 20172015-박동원
>메시 얼굴을 이용하여 원본사진의 메시 얼굴객체를 찾는법 (주석설명 참조)

### 20170215-김현우
>회귀분석 알고리즘을 이용하여 사람의 무게를 입력받으면 그 사람의 키를 예측하는 프로그램 작성

### 20170215-강지성
>object detect소스, 회귀분석은 소연이꺼 따라함

### 20170213-박동원
>머신러닝 회귀분석 탠서플로우를 이용 코드설명 주석처리 

### 20170213-이정훈
>격자무늬 길이 측정 방식 예제 실습
처음에 실패해서 올렸었는데 안올라가져서 다시올림
그때 당시 체스보드 예제했던 것을 토대로 점을 다 찍고 한 점과 그 다음 점 사이의 길이만 주고 원하는 점과 점 사이에 길이를 측정하려고 했으나 실패
마지막 파일은 현우형꺼 보고 따라함

### 20170213-김현우
>특정 개체를 배경 영상에서 발견하는 예제 실습

### 20170212-김현우
>의사결정나무 분류 알고리즘에 붓꽃데이터를 적용시켜 예제 실행
>의사결정나무를 이용하여 군인들의 신체사이즈와 옷 사이즈를 분류하는 프로그램 제작

### 20170210-안병문
> 직선을 검출해서 격자 무늬만 따로 떼어놓는 방법을 생각하여 직선(Houghline)을 검출하는 기본 예제를 실행해보았음
예제하고 똑같이 짰는데 예제하고 다른 결과가 나옴
[기본 예제 주소](http://docs.opencv.org/2.4/modules/imgproc/doc/feature_detection.html)

###20170210-박동원
>여러시도를 해보았으나 안되어 접어두고 다시 기존에있는 격자무늬에서 모서리 인식한 부분을 가지고 길이를 측정하고자 했으나 
 미완성 

###20170210-김소연
>임의로 지정한 좌표와 좌표간 거리를 distance라고 설정한 후 한 변의 길이가 distance인 정사각형을 그려보고자
 했으나 아직 미완성

### 20170210-김현우
>특정좌표에서 또다른 특정좌표까지의 떨어진 거리를 구하는 솔루션

### 20170210-신상훈
>격자무늬의 교차점을 인식하고 그 교차점과 다음 교차점과의 픽셀값이 정해둔 픽셀값과 일치하는지 확인

### 20170208 안병문
> 따라하기 완료

### 20170208 김소연
>학원에서 따라해봄

###20170208-이정훈
>OpenCV 체스보드 좌표 인식 완료

### 20170208-박성진
>OpenCV Python 작업 환경 세팅 및 체스보드 좌표 인식 성공

### 20170208-박동원
>OpenCV 코너 좌표인식 그림 그리기 완료 

### 20170207-신상훈
>현우와는 다른 방식으로 체스 보드를 인식함

### 20170210-강지성
>격자무늬의 사각형을 쪼개서 함수를 이용해 그 길이 출력

### 20170207-김현우
>체스보드에서 각 코너들의 좌표를 인식하고 해당하는 위치에 그림을 그림
