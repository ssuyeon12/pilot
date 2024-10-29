# 포트폴리오 프로젝트 모음

이 저장소에는 다양한 YOLO 신경망 활용 파일럿 프로젝트가 포함되어 있습니다. 각 프로젝트는 실시간 객체 탐지, 추적, 분석 등을 목표로 합니다.

---

## 프로젝트 목록


### 1. 유동인구 카운트 YOLO 영상 파일럿 프로젝트
- **프로젝트 설명**: YOLO 모델을 사용하여 영상 속 유동인구를 실시간으로 감지하고, 입장 및 퇴장 수를 카운트하는 시스템.
- **주요 기능**: 사람 객체 탐지, 입장 및 퇴장 카운팅, 누적 인원 계산.
- **관련 링크**:
  - [YOLO 모델 다운로드](https://github.com/ultralytics/yolov5)
  - [OpenCV 공식 문서](https://docs.opencv.org/)
- **관련 주피터 노트북**:
  - [구글 코렙 주피터 노트북](https://colab.research.google.com/drive/13T0kutpXo5_PSfEt3GdIy2FI9nPdjvyx?usp=sharing)
- **시연 영상**:  
  [![유동인구 카운트 영상](https://github.com/ssuyeon12/pilot/blob/main/sjk.jpg)](https://github.com/ssuyeon12/pilot/blob/main/output3_with_counts.mp4)
---

### 2. 엑스레이 사진에서 폐결절을 찾는 신경망
- **프로젝트 설명**: 이 프로젝트는 X-ray 사진을 분석하여 폐결절을 자동으로 탐지하고, 의료진이 더 정확한 진단을 내리는 데 도움을 주기 위해 신경망 모델을 개발하는 것을 목표로 합니다. 주로 딥러닝 기반의 CNN(Convolutional Neural Network) 모델을 사용하여 엑스레이 이미지에서 폐결절을 분류하고, 위치를 표시합니다.
- **주요 기능**: 폐결절 자동 탐지
- **관련 링크**:
  - [YOLO 모델 다운로드](https://github.com/ultralytics/yolov5)
  - [알림 시스템 API 문서](https://your-api-link.com/)
  - **관련 주피터 노트북**:
    -  [구글 코렙 주피터 노트북](https://colab.research.google.com/drive/1W40Odsndj5EFLFEIJrUc_lXDWcvZmpUF?usp=sharing)
- **시연 이미지**:  
  [![폐결절 찾는 시연 이미지](https://github.com/ssuyeon12/pilot/blob/main/%ED%8F%90%EA%B2%B0%EC%A0%88.png)]

---





### 2. 도둑감지 YOLO 신경망 활용 파일럿 프로젝트
- **프로젝트 설명**: 무인 감시 시스템을 위한 도둑 감지 기능. YOLO 모델을 통해 특정 위치에서의 불법 침입자를 실시간으로 탐지.
- **주요 기능**: 실시간 침입자 감지, 위험 알림, 비상 조치 기능.
- **관련 링크**:
  - [YOLO 모델 다운로드](https://github.com/ultralytics/yolov5)
  - [알림 시스템 API 문서](https://your-api-link.com/)
- **시연 영상**:  
  ![도둑 감지 영상](https://user-images.githubusercontent.com/yourusername/your-video-file2.mp4)

---

### 3. 차량 흐름 분석 파일럿 프로젝트
- **프로젝트 설명**: 도로 영상에서 차량 객체를 감지하고, 차량 흐름을 분석하여 교통 밀집도를 예측.
- **주요 기능**: 차량 객체 탐지, 밀집도 분석, 실시간 데이터 시각화.
- **관련 링크**:
  - [교통 데이터 API](https://traffic-api.com/)
- **시연 영상**:  
  ![차량 흐름 분석 영상](https://user-images.githubusercontent.com/yourusername/your-video-file3.mp4)

---

### 4. 얼굴 인식 출입 시스템 파일럿 프로젝트
- **프로젝트 설명**: YOLO와 얼굴 인식 모델을 이용한 출입 관리 시스템.
- **주요 기능**: 얼굴 인식을 통한 출입 허가, 기록 관리, 출입 로그.
- **관련 링크**:
  - [얼굴 인식 모델 다운로드](https://facerecognition-model.com/)
- **시연 영상**:  
  ![얼굴 인식 시스템 영상](https://user-images.githubusercontent.com/yourusername/your-video-file4.mp4)

---

### 5. 안전 헬멧 착용 감지 파일럿 프로젝트
- **프로젝트 설명**: 작업 현장에서 안전 헬멧 착용 여부를 감지하여 안전 규정을 준수하는지 확인.
- **주요 기능**: 헬멧 착용 감지, 안전 경고, 실시간 알림.
- **관련 링크**:
  - [헬멧 감지 데이터셋](https://helmet-dataset.com/)
- **시연 영상**:  
  ![헬멧 착용 감지 영상](https://user-images.githubusercontent.com/yourusername/your-video-file5.mp4)

---

## 설치 및 실행 방법

1. 필요한 라이브러리 설치:
   ```bash
   pip install opencv-python-headless ultralytics numpy
