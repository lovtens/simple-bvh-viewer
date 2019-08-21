# simple-bvh-viewer
2019 Computer Graphics, simple bvh viewer


## Test Environment
- OS: windows 10
- language: python 3.7.3

## Requirements
- PyOpenGL 3.1.3
- glfw 1.8.0
- numpy 1.16.4

## How to run program
```python bvh_viewer.py```


## 구현된 기능

- Camera work
  - blender와 비슷한 방식으로 구현
  - 마우스 버튼과 휠로 동작
  - Orbit : 마우스 왼쪽 버튼 & 드래그
  - Panning : 마우스 오른쪽 버튼 & 드래그
  - Zooming : 마우스 휠
  
- Load bvh file
  - bvh 확장자 파일을 drag-and-drop
  - load된 bvh 파일 정보를 출력
    - Filename
    - Number of frames
    - FPS (rounded)
    - Number of joints
    - List of all joint names
- Animate motion
  - SPACEBAR 키로 motion을 재생/멈춤
  - frametime은 1ms로 고정
- Adjust model
  - Q,W 키로 model scale 조정
  - B 키로 box, line model toggle

## 결과
- sample-walk.bvh with box model

![sample1](https://github.com/lovtens/simple-bvh-viewer/blob/master/sample/sample1.gif)
