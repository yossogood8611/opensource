# Open Source

## 1. 프로젝트 설명
유기동물 이미지의 feature들과 pawpularity(입양확률 점수)의 연관성을 시각화 하는 프로젝트이다.
데이터 셋과 프로젝트 설명은 kaggle에서 가져왔다.
각각의 feature들에 대한 설명도 볼 수 있다. 
(near : 사진에서 유기 동물이 가까이 있는지 여부, face : 사진에서 얼굴이 나왔는지 여부 ...)
https://www.kaggle.com/c/petfinder-pawpularity-score/data

## 2. 데이터 정제
초기 데이터 셋은 0~100 사이의 점수가 한 쪽으로 편향되어져 있는 경향이 있고, 실제로 본 유기동물의 사진의 귀여움과 pawpularity 점수가 달라서 유미동물 이미지 약 6000개의 점수를 다시 저장하였다. 그리고 feature와 pawpularity의 연관성을 높이기 위해 breed라는 feature도 추가하여 저장하였다.

+pawpularity와 연관있다고 생각한 feature : near, face, eyes

## 3. 랜덤 포레스트 결과
랜덤 포레스트를 구글링 하여 어느 feature의 중요도가 높은지 확인하였고, 실제로 연관있다고 한 feature와 실제 중요하다고 판단한 feature가 동일하게 나옴을 볼 수 있었다.
￼
