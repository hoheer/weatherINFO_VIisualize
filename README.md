
## 스마트서울 도시데이터팀 분석과제 1 - <SDOT 데이터를 사용한 기상특보(폭염, 건조, 미세먼지)>
 - 진행기간 : 2021.06 ~ 2021.07 







## 사용한 시각화 종류들


### PLOTLY SLIDER를 활용한 시간별 미세먼지 현황
<img src="https://github.com/hoheer/weatherINFO_VIisualize/blob/main/image/%EC%8A%AC%EB%9D%BC%EC%9D%B4%EB%8D%94.PNG" width="50%" height="40%" title="px(200)" alt="RubberDuck"></img>


GIF 렌더링 시간이 너무 오래걸려 대안법을 찾아보던 중 PLOTLY 패키지를 알게되었다. 렌더링 방식에 비해 걸리는 시간은 1/10 수준이고 제어 바를 통해 원하는 시간에 멈추어 놓고 볼 수도 있다. 다만 HTML 보고서 형태로 뽑아내는게 아니라면 사진 한장에 불과하다는 단점이 있다. 


### 21년 5월 6,7,8,9일 자치구별 미세먼지

<img src="https://github.com/hoheer/weatherINFO_VIisualize/blob/main/image/2021%EB%85%84%20%EC%9D%BC%EB%B3%84%EB%AF%B8%EC%84%B8%EB%A8%BC%EC%A7%80.png" width="50%" height="40%" title="px(200)" alt="RubberDuck"></img>




### GGANIMATE GIF 
<img src="https://github.com/hoheer/weatherINFO_VIisualize/blob/main/image/2020%EB%AF%B8%EC%84%B8%EC%9B%80.gif" width="50%" height="40%" title="px(200)" alt="RubberDuck"></img>


렌더링 시간 빼고 완벽한 GIF. 호환성이 뛰어나 다른 문서에 삽입하기에도 너무 좋다. 




### 시간별 미세먼지 주의보/경보
<img src="https://github.com/hoheer/weatherINFO_VIisualize/blob/main/image/%E1%84%90%E1%85%B3%E1%86%A8%E1%84%87%E1%85%A9.png" width="50%" height="40%" title="px(200)" alt="RubberDuck"></img>


자치구 시간별로 환경부 기준에 따라 미세먼지 경보/주의보를 구분 



### 법정동별 미세먼지 현황
<img src="https://github.com/hoheer/weatherINFO_VIisualize/blob/main/image/%E1%84%92%E1%85%A2%E1%86%BC%E1%84%8C%E1%85%A5%E1%86%BC%E1%84%83%E1%85%A9%E1%86%BC.png" width="50%" height="40%" title="px(200)" alt="RubberDuck"></img>




현재 SDOT주소는 법정동을 기준으로 기재되어 있다. 따라서 이걸 법정동 SHP 파일과 연결하려면 법정동 코드를 사용해야 한다. 이 각종 코드를 구분하여 사용하는 것이 이렇게 어려울 줄은 몰랐다. 이번 프로젝트에서 가장 많은 시간과 노력을 가한 결과물이다. 


## 예정사항
 - PLOTLY 활용 INTERACTIVE MAP 구현(DROP BOX를 이용한 자치구 변경 등)
 - 시간단축을 위한 GIF -> SLIDER BAR 형식으로 변경 진행중

