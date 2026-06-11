# 서울시 토지이용 및 도시숲 분포 분석 (Version 2)

## 프로젝트 개요

본 프로젝트는 OpenStreetMap(OSM) 기반 공간데이터를 활용하여 서울시의 토지이용 현황과 도시숲 분포를 시각화하고, 도시숲의 공간적 영향 범위를 분석하기 위한 인터랙티브 웹지도를 구축한 프로젝트이다.

Version 2에서는 기존 도시숲 분석에 더해 상업지역 및 산업지역의 영향권(Buffer)을 추가하여 도시숲과 다른 토지이용 유형의 공간적 분포를 비교·분석할 수 있도록 개선하였다.

---

## 주요 기능

- 서울시 토지이용 분포 시각화
  - 주거지역
  - 상업지역
  - 산업지역
  - 도시숲

- 도시숲 500m 버퍼 생성

- 상업지역 버퍼 분석

- 산업지역 버퍼 분석

- Layer Control

- 거리 측정 (Measure Control)

- 좌표 확인 (Mouse Position)

- MiniMap

- Fullscreen

- 사용자 정의 범례(Custom Legend)

---

## 사용 기술

- Python
- GeoPandas
- Shapely
- OSMnx
- Folium
- OpenStreetMap
- Google Colab
- GitHub Pages

---

## 프로젝트 결과물

### GitHub 코드 원본

https://github.com/yerin-0530/2026_Seoul_forest_map/blob/main/Version_2/seoul_forest_design_code_v2.ipynb

### Notebook 보기 전용

https://nbviewer.org/github/yerin-0530/2026_Seoul_forest_map/blob/main/Version_2/seoul_forest_design_code_v2.ipynb

### 인터랙티브 웹지도

https://yerin-0530.github.io/2026_Seoul_forest_map/Version_2/seoul_forest_map_v2.html

---

## 분석 내용

본 프로젝트는 OpenStreetMap의 Landuse 데이터를 활용하여 서울시의 토지이용 유형을 분류하였다.

분석 대상

- Residential
- Commercial
- Industrial
- Forest

도시숲(Forest) 데이터에 대해 500m 버퍼를 생성하여 시민의 녹지 접근성을 시각화하였으며, 상업지역과 산업지역의 영향권을 함께 비교함으로써 서울시 공간구조의 특성을 보다 직관적으로 분석할 수 있도록 하였다.

---

## 주요 개선 사항 (Version 2)

Version 1은 도시숲의 분포와 접근성 분석에 초점을 두었다.

Version 2에서는 다음 내용을 추가하였다.

- 상업지역 버퍼 추가
- 산업지역 버퍼 추가
- 도시숲 영향권과의 비교 분석
- 범례 및 시각화 개선
- 사용자 인터페이스 개선

이를 통해 도시숲의 공간적 분포를 다른 토지이용 유형과 함께 비교할 수 있는 분석 기반을 구축하였다.

---

## 프로젝트 의의

본 프로젝트는 공개 공간정보(OpenStreetMap)와 Python 기반 GIS 분석 도구를 활용하여 별도의 전문 GIS 소프트웨어 없이도 공간 분석과 웹지도 구축이 가능함을 보여준다.

또한 도시숲의 공간적 분포와 녹지 접근성을 시각적으로 분석함으로써 도시계획, 녹지정책, 환경분석 및 생활권 서비스 연구에 활용 가능한 GIS 사례를 제시한다.

---

## 라이선스

본 프로젝트는 학습 및 연구 목적으로 제작되었다.
