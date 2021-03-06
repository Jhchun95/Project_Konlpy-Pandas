> ## 공훈록 사건정보 분석
> 1. 국가보훈처에서 팀원과 같이 제작한 프로젝트 소스코드 및 결과물
> 2. 공훈전자사료관에서 배포하고 있는 공훈록을 토대로 사건분석을 진행
> 3. 독립유공자 정보를 효과적으로 제공하기 위해 ‘공훈전자사료관 독립운동 정보 복합제공 서비스 구축
<br/>

> ### :heavy_check_mark: 분석 목적 및 방향
> 1. 독립유공자 정보 활용도를 높이기 위한 데이터 구축 방안 검토
> 2. 효율적인 데이터 전처리 및 분석 방안 검토
<br/>

> ### :heavy_check_mark: 본인이 맡은 역할
> 1. 주로 인적 정보와 공적 정보 등 활용할 데이터들을 파이썬으로 전처리 진행
> 2. 전처리한 데이터를 표, 그래프, 지도 등으로 수치화
<br/>

> ### :heavy_check_mark: 분석 데이터 내용
> 1. 관리번호, 성명, 한자, 성별, 생년월일 등 독립유공자 인적정보와 
> 2. 독립운동이 사실이 기재된 공적내용을 중심으로 분석 실시
<br/>

> ### :heavy_check_mark: 분석 방법
<img src="./img/Dataprocess.png" width="620" height="300"><br/>  
> 1. 데이터 수집 : 독립유공자 공훈록 DB에서 내려받아 엑셀 파일 형태로 수집
> 2. 전처리 : 정규식을 활용해서 문장 및 단어를 추출
> 3. 분석 : 단체, 지역, 옥고 등의 추출한 단어들을 연관된 주제로 묶어 분석 실시
<br/>

* 결과물  

<학생운동 참여 지역 현황 인포그래픽 예시>  
<img src="./img/1장.png" width="500" height="300"><br/>  
<주요 학생운동 발생 지역 현황 인포그래픽 예시>  
<img src="./img/2장.png" width="500" height="300"><br/>  
<학생 독립운동 단체 인포그래픽 예시>  
<img src="./img/3장.png" width="500" height="300"><br/>  
<광주학생운동 관련 단체 인포그래픽 예시>  
<img src="./img/4장.png" width="500" height="300"><br/>  
<독립운동 사건 죄명 관련 인포그래픽1 예시>  
<img src="./img/5장.png" width="500" height="300"><br/>  
<독립운동 사건 죄명 관련 인포그래픽2 예시>  
<img src="./img/6장.png" width="500" height="300"><br/>  
<독립운동 사건 죄명 관련 인포그래픽3 예시>  
<img src="./img/7장.png" width="500" height="300"><br/><br/>  

<학생운동 1920년대>  
<img src="./img/wc_1920.png" width="450" height="250"><br/>  
<학생운동 1930년대>  
<img src="./img/wc_1930.png" width="450" height="250"><br/>  
<학생운동 1940년대>  
<img src="./img/wc_1940.png" width="450" height="250"><br/><br/>  

> ### :heavy_check_mark: 한계점  
> 1. 공유받은 독립유공자의 내용 자료가 이미 한 번 가공된 비정형 데이터였기 때문에, 정확성이 많이 떨어짐  
> 2. 단어의 전처리에 있어 일반적인 데이터 전처리 과정 외에도, 역사 전문가의 검토를 데이터 정제가 필요함  
<br/>

> ### :heavy_check_mark: 기대효과  
> 1. 독립유공자 정보 중 활동 유형, 활동 시기, 소속 단체, 지역, 형명 등 통계를 도출할 수 있는 전처리 요소들이  
추후 구축 제공할 수 있는 신규 콘텐츠 유형에 검토될 수 있음  
<br/>

<br/>

> ### :heavy_check_mark: 프로젝트 개발환경  
> 1. Windows 10 Pro 64bit, x64 기반 프로세서, RAM 16GB  
> 2. Python 3.8.10  
> 3. wordcloud-1.8.1-cp38-cp38-win_amd64  
> 4. JPype1-1.1.2-cp38-cp38-win_amd64  
> 5. jdk-17_windows-x64_bin  
> 6. mariadb-10.6.4-winx64  
> 7. Anaconda3-2021.05-Windows-x86_64  
<br/>

> ### :heavy_check_mark: 개발언어  
> 1. Python
<br/>

> ### :heavy_check_mark: 개발도구 프로그램  
> 1. Jupyter Lab, Visual Studio Code  
> 2. HeidSql  
> 3. Qgis DeskTop 3.16.15 with grass 7.8.5  



