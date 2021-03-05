# How-to-use-Anaconda
아나콘다 사용하기
----------------

<h1>독립적인 개발환경 구성 및 각 환경 별 패키지의 의존성을 명확히 관리할 수 있다!</h1>

1. 아나콘다 : 파이썬 기반 데이터 분석에 필요한 오픈소스를 모아놓은 개발 플랫폼
2. 패키지 관리자 : 효율 올려줌
3. 가상환경 관리자 : 프로젝트 별 각각 필요한 것들로만 이루어진 개발환경을 통해 효율적인 프로젝트 관리


--------------------

<h2>0. 버전 확인 및 업데이트</h2>

- conda --version
- conda update conda

항상 최신버전으로 해야 패키지 설치 시 오류 발생 안함!

----------------------

<h2>1. 가상환경 생성</h2>

- conda create -n(--name) [가상환경 이름/프로젝트 명] python=[파이썬 버전]

- conda info -e(--envs) : 현재 설치 된(생성 된) 가상환경 <b>리스트</b> 확인
![image](https://user-images.githubusercontent.com/61974613/110137000-b1f47b00-7e13-11eb-9f98-e6c4c0efb4a2.png)

- activate [가상환경 이름] : 가상환경 활성화
- deactivate [가상환경 이름] : 가상환경 비활성화
![image](https://user-images.githubusercontent.com/61974613/110137044-c0429700-7e13-11eb-8e0f-ccc84b24ccd0.png)

-----------------------

<h2>2. 가상환경 관리</h2>

- conda install [패키지 이름] : 패키지 설치
- conda list : 설치된 패키지 확인
- conda remove -n(--name) [가상환경 이름/프로젝트 명] -all
- conda clean -a(--all)

-------------------------

<h3>3. 가상환경 - Jupyter Notebook</h2>

- 가상환경 활성화 후 pip install jupyter : 해당 가상환경의 주피터 노트북이 설치됨
![image](https://user-images.githubusercontent.com/61974613/110137918-ba998100-7e14-11eb-86b9-fd9229802214.png)

- 가상환경 활성화 후 jupyter notebook : 주피터 노트북 실행됨 (좀 걸림)


끗!
