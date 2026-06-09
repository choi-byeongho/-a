# ExecFurniture-Classifier (중역 가구 카테고리 분류기)

![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-in--development-orange)

## # 프로젝트 소개
이 프로젝트는 **중역 가구(Executive Furniture)의 이미지나 상품 정보를 분석하여 알맞은 카테고리로 자동 분류해 주는 딥러닝 기반의 분류 도구**입니다. 

가구 디자인 앱이나 커머스 플랫폼에서 대량의 중역 가구 데이터를 효율적으로 정렬하고, 중역 가구 특유의 고급스러운 재질 및 형태적 특징을 학습하여 정확한 카테고리(책상, 의자, 소파, 캐비닛 등)를 추천합니다.

---

## # 주요 기능
- **이미지 기반 자동 분류**: 가구 이미지를 입력받아 중역 가구 카테고리를 예측 및 분류합니다.
- **다중 카테고리 태깅**: 중역용 책상, 최고급 가죽 의자 등 세부 속성에 맞는 태그를 자동으로 생성합니다.
- **경량화된 모델**: 가구 디자인 앱 등 타 서비스나 API 서버에 쉽게 연동할 수 있도록 최적화되어 있습니다.
- **결과 시각화**: 분류 결과와 함께 모델이 이미지의 어느 부분을 보고 판단했는지(CAM) 시각화 자료를 제공합니다.

---

## # 사용 방법

### 1. 환경 설정 및 다운로드
먼저 저장소를 클론하고 필요한 라이브러리를 설치합니다.
```bash
# 저장소 클론
git clone [https://github.com/your-username/ExecFurniture-Classifier.git](https://github.com/your-username/ExecFurniture-Classifier.git)
cd ExecFurniture-Classifier

# 필수 패키지 설치
pip install -r requirements.txt
