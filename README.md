# AI hashtag generation prompt engineering based on gpt-4-vision
**image + test 기반**으로 hashtag generation을 하기 위해 멀티모달인<br/>
**gpt-4-vision-preview model**을 사용하여<br/>
**맛표현, 상황, 비주얼**의 관점에서 hashtag를 생성하도록 prompt engineering 하였습니다<br/>
맛표현, 상황, 비주얼을 주요 요소로 삼은 이유는  <br/>
플레이팅의 기술의 3요소 + 사람이 음식을 먹을 때 영향을 많이 받는 3가지로 생각하면<br/>
정확도 측면이나 사용자 경험이 더욱 향상될 것이라 생각했기 때문입니다.  <br/>
BE logic: FE에서 image_url+text를 받고 fastapi 서버로 응답 결과를 서빙하는 로직<br/>
![image](https://github.com/9roomthon-sixpack/2024_BEOTKKOTTHON_TEAM_26_AI/assets/108683454/162f4df4-c778-4bb2-a7be-3e4d669ba0a6)

# AI search based on AI hashtags  
생성된 해시태그를 기반으로 AI 검색 기능을 구현<br/>
자연어를 받아서 그에 알맞는 해시태그 3개와 매칭하여<br/>
예를들어 **"맥주랑 먹기 좋은 음식"** 이라고 추상적으로 검색을 해도<br/>
그에 알맞는 검색 결과가 나오게 하기 위함입니다.<br/>
~~원래는 SQL 서버와 GPT를 연동하여 해보고싶었지만 시간관계상..~~ <br/>
BE logic: FE에서 text를 받고 fastapi 서버로 응답 결과를 서빙하는 로직<br/>
![image](https://github.com/9roomthon-sixpack/2024_BEOTKKOTTHON_TEAM_26_AI/assets/108683454/bb96f24b-4071-4fe5-a251-99e1699706c7)
