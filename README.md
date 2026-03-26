# 🎮 Game Genre Analysis (비디오 게임 장르 및 시장 데이터 분석)

비디오 게임의 역대 판매 데이터를 활용하여 **지역별 선호 장르**, **연도별 출시 트렌드**, 그리고 **시장 성장을 주도한 주요 요인**을 분석한 프로젝트입니다.

---

## 📌 프로젝트 개요
본 프로젝트는 전 세계 비디오 게임 판매량 데이터셋을 바탕으로 데이터 전처리 및 탐색적 데이터 분석(EDA)을 수행합니다. 데이터에 숨겨진 패턴을 시각화하여 게임 산업의 흐름을 이해하는 데 목적이 있습니다.

## 🛠 기술 스택
- **Language**: `Python 3.x`
- **Libraries**: 
  - `Pandas`: 데이터 클렌징 및 조작
  - `Matplotlib` / `Seaborn`: 데이터 시각화
  - `Numpy`: 수치 계산

## 📊 주요 분석 단계
1. **데이터 전처리 (Data Cleaning)**
   - 결측치 처리 및 데이터 타입 변환 (Year, Sales 등)
   - 분석에 용이하도록 데이터 프레임 재구성

2. **지역별 선호도 분석 (Regional Analysis)**
   - 북미(NA), 유럽(EU), 일본(JP), 기타(Other) 지역별 판매량 비교
   - 각 지역에서 가장 인기 있는 게임 장르 도출

3. **연도별 트렌드 분석 (Yearly Trends)**
   - 연도별 게임 출시 건수 변화
   - 특정 시기에 급격히 성장하거나 쇠퇴한 장르 분석

4. **플랫폼 및 배급사 분석 (Platform & Publisher)**
   - 시장 점유율이 높은 주요 플랫폼과 배급사의 영향력 확인

## 📁 파일 구조
- `Game_Genre_Analysis.ipynb`: 데이터 분석 전체 과정이 담긴 Jupyter Notebook
- `vgsales.csv`: (데이터셋 파일이 있는 경우) 분석에 사용된 원본 데이터

## 🚀 시작하기
이 저장소를 클론한 후 필요한 라이브러리를 설치하여 분석 내용을 직접 확인할 수 있습니다.

```bash
# 저장소 클론
git clone [https://github.com/kimkihyun1/Game-Genre-Analysis.git](https://github.com/kimkihyun1/Game-Genre-Analysis.git)

# 필수 라이브러리 설치
pip install pandas matplotlib seaborn numpy
