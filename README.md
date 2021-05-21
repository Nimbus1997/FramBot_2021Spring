# FramBot_2021Spring
KIST
기간: 2021.03.02 - 2021.06.30
토마토의 생장정도를 알아내기 위한 과정


데이터 구성
1. RGB이미지, Depth파일 (png, csv) - 파일명 : KIST_Tomato_Z200_[RGB or Depth]_2021-04-22(110149)_[동일한 장소 같은 시간대에 찍은 사진 번호 2].[png or csv]


코드 구성
1. 이미지들 보고 간단한 변경 (hsv), depth정보 이용해서 배경 제거하는 코드 "image_preprocessing20210423.ipynb"
2. 학습 가능한 이미지 뽑아내는 "Data Sorting 20210518.ipynb"
