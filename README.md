# Project-SEE
SEE: Safety Equiptment Enforcement 안전장비 착용 감지 AI프로젝트


### ✨프로젝트 소개

- 건설현장 등에서 사람이 안전장비를 제대로 착용시에만 들어갈 수 있게 도와주는 서비스
- Ultralytics의 YOLOv5모델을 사용하여 AI로 안전장비 착용 상태를 확인하는 서비스
- 안전모와 하네스의 on off 를 구별하고, 둘 다 on인 경우에만 통과
- exe파일로 제작
- 사용 데이터셋

### ✨개발방법

- Visual Studio Code
- PyCharm
- DevOps: Slack

### ✨역할

- 총 6명으로 구성된 프로젝트 팀의 팀원 역할
- 기획서 및 발표자료 작성 총괄
- 이미지 데이터셋 전처리: 
할당받은 데이터셋에서 필요한 class번호만 남김
- 학습을 위한 이미지 데이터셋 추가 구축: 
헬멧을 착용하지 않은경우의 이미지를 찾고 머리 위치에 helmet-off 바운딩박스를 쳐서 이미지와 좌표 폴더를 추가로 생성함
- AI모델 적용: YOLOv5 모델로 학습시킴
