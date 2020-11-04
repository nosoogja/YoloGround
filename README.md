# YoloGround
Labelling 


yolo 학습에 사용할 Object 좌표 등록 프로그램.

- Ctrl + Mouse Drag  : 좌표 등록
- Number key : Object Id 변경(1초 reset)
- 방향키 : 이미지 변경
- Object ID는 기본 20개가 추가됨. 



-- issue
- 이미지 meta 정보에 있는 방향이 있으면 어떤 기준으로 맞춰야 할지 모르겠다.
darknet 에서 방향을 틀어서 계산을 하는지 아님 어떤 기준으로 하는지 찾기 복잡다....
그래서 그냥 meta 정보를 삭제하고 하는게 .....알아서.....


