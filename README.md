# ⚽ goldenpass-platform

> 영상 기반 데이터 분석 플랫폼을 서비스하는 비프로 컴퍼니와 함께한 기업 협업 프로젝트 입니다. 2020년 11월, 실제 런칭 예정인 서비스를 직접 개발할 수 있는 기회를 갖게 되어 4명의 팀으로 참여하였고 그 중, 프론트엔드 개발을 맡았습니다.
기업협업 프로젝트인 관계로 코드 공개가 불가능한 점 양해 부탁드립니다.🤣

##  📌 프로젝트 소개
유망있는 어린 축구 선수들을 발굴해, 훌륭한 선수로 성장시키는 것은 우리나라 축구 발전을 도모하는데 빼놓을 수 없는 핵심 과제일 것입니다.

Goldenpass Platform은 유소년 축구선수를 대상으로 선수 개개인의 핵심 역량을 축적, 관리하여 **선수의 개인 발전을 도모**하기 위해 설계된 프로젝트 입니다.

한명의 선수에 대해 6개 영역, 19개 지표를 측정하여 측정값을 입력한 데이터를 해당 플랫폼에서 업로드하면, 개별 데이터를 조회할 수 있는 것은 물론, 선수간 데이터를 비교할 수 있는 등 유동적인 데이터 파악이 가능합니다.

## 🚀사용 스택 
![clientstack](https://user-images.githubusercontent.com/59456824/90146558-23a7a180-ddbc-11ea-8f1e-c6e560a2717e.png)
![otehrstack](https://user-images.githubusercontent.com/59456824/90146561-25716500-ddbc-11ea-9f8d-e32ad1f8485b.png)


##  💾 기능 Flow 
<img width="1000" alt="_2020-08-10__10 31 53 (1)" src="https://user-images.githubusercontent.com/59456824/90146986-aaf51500-ddbc-11ea-9126-2629998a0811.png">

##  💁 기여 작업 세부사항
**Front-end**
- [로그인]로그인, 로그아웃기능 구현 
- [선수 검색창] 검색 창 클릭 시 선수 검색 모달창 생성, 필터링 적용해 검색한 선수 출력, 검색 결과로 나온 선수 클릭 시 해당 선수의 개인 페이지로 이동하는 기능 구현 
- [선수리스트 페이지] 필터링(성별,연령그룹,차시,카테고리)에 따른 선수 리스트 출력기능, 출력된 선수 리스트 CSV 포맷으로 다운로드 기능
- [선수비교 페이지] 비교할 선수 선정 모달창, 2-5명의 선수 클릭 시 유저가 필터링한 대로 선수들의 측정 데이터를 비교하는 라인 그래프 출력
- [데이터 등록 페이지] CSV파일 등록 시 DB에 저장 및 선수 데이터 페이지에 출력


##  📊 구현 주요 기능별 시연 GIF
-**로그인, 로그아웃**
![login](https://user-images.githubusercontent.com/59456824/90150068-345a1680-ddc0-11ea-9297-9843d535c51a.gif)

- **선수 데이터 업로드 (2020_3차시 선수들의 파일을 업로드 한 예시입니다)**
![uploadData](https://user-images.githubusercontent.com/59456824/90150091-3c19bb00-ddc0-11ea-8f11-90f2890f2bad.gif)

- **선수 데이터 필터링(연령그룹,차시,성별,카테고리), CSV 다운로드 기능** 
![playerslist](https://user-images.githubusercontent.com/59456824/90151084-51431980-ddc1-11ea-8272-3edb84f04a06.gif)

- **선수 검색**
![searchData](https://user-images.githubusercontent.com/59456824/90150123-476ce680-ddc0-11ea-8eb3-bd0034664603.gif)

- **선수 비교(최대 5명의 선수 비교)**
![compareplayers gif](https://user-images.githubusercontent.com/59456824/90148099-ed6b2180-ddbd-11ea-86ba-a2841fa27ab3.gif)


