# pj_python_collection_news
- Streamlit, selenium, beautifulSoup4, requests, pymysql, apscheduler

### 1. 아나콘다 가상환경 사용법
- conda create -n collection python=3.12  # 가상환경 생성 (파이썬 기본 버전)
- conda env list                            # 가상환경 목록
- conda activate collection                 # 가상환경 접속 (or ### 2번으로)
- pip install [라이브러리]                   # 라이브러리 설치

### 2. VScode 가상환경 주입
- Ctrl + Shift + P
- "python select interpreter" 검색
- "collection" 가상환경 선택

### 3. VScode 라이브러리 설치
- Ctrl + ` : 터미널 켜기
- + 버튼(command prompt) -> Anaconda prompt와 똑같이 동작
- pip install -r requirements.txt
- pip list  # 설치된 라이브러리 목록