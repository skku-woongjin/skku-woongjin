2022 산학협력 프로젝트 웅진씽크빅
----------------------------
메타버스에서의 AI Agent 개발
=========================================================

> **웅진씽크빅**사와 함께 진행한 프로젝트입니다. <br> 현재 웅진 메타버스에서는 놀이와 학습의 균형이 이루어지지 못하고, 아이들을 욕설 및 비매너 환경에서 보호하기가 어렵습니다. <br> 따라서 저희는 새호운 컨텐츠들을 추천해주는 **Guide Agent**, 비매너 및 욕설을 탐지하는 **Guard Agent**, 아이들과 간단한 대화를 할 수 있는 **Talking Agent**를 개발하여서 이 문제를 해결하고자 하였습니다.

<br>

# Repository 설명
### WJ-combined
- 통합 데모 유니티 프로젝트
### RecommendAgent_Train
- 장소추천 모델 훈련 코드. ShaderLab, C#, HLSL 사용
### RecommendAgent_Demo
- 장소추천 모델 데모 코드. ShaderLab, C#, HLSL 사용
### comfort_chatbot
- 위로봇 데모 코드. Python, Html, Javascript 사용
### WikiChatbot
- 위키챗봇 데모 코드 및 데모 사이트. Python, HTML, JavaScript 사용
### HateSpeechAPI
- Guard Agent 데모 코드 및 데모 사이트. Python, HTML, Jupyter Notebook(for train) 사용

<br>

# 개발 과정
### 4 ~ 5월: 선행 학습
- 강화학습 구현 및 개념 학습
    - OpenAI를 활용해 Atari 게임 구현
    - Reward, State, Action 개념 학습
- 아이디어 회의
### 6 ~ 8월: 하계 집중학습
- 사용할 platform 선정 및 개발 환경 구축
- Agent별 구현 기술 스터디
- 각 Agent별로 구현<br>
    -Guide/Guard Pet Agent <br>
    -Quest Auto Generator <br>
    -Visual Game(영어 QA게임) <br>
- Unity 기반 메타버스 World 제작/통합 시연
### 9월 ~ 12월: 각 Agent 구체화
- Guide Agent
    - 아이들의 발자취를 기반으로 한 장소 추천 시스템 구체화
    - Quest 데이터 수집 및 구체화
- Talking Agent
    - WikiQA봇
        -아이들이 궁금한 것을 대답해주는 질의응답 NPC
        -BERT와 Wikipedia 이용
    - 위로봇
        -아이들을 위로해주는 대화NPC
        -검색기반과 문장생성(GPT)를 이용
# 메타버스 AI Agent
### Guide Agent
<img src="https://user-images.githubusercontent.com/103883786/209500789-7a737a43-4d66-4209-ae41-d177ba5f93c9.png" height="400"/>

### Guard Agent
<img src="https://user-images.githubusercontent.com/103883786/209500114-f872557d-7f12-4494-9b7b-fe0676a99860.png" height="400"/>

- 월드에 있는 대화 그룹에 들어가면 다른 친구들과 자유롭게 대화할 수 있음.
- 대화 내용중에 욕설이 감지되면 왼쪽 상단의 Hate 게이지 바가 올라감.
- Hate 게이지 바가 올라 일정 비율(현재는 40%)이상이 되면 대화 그룹에 우당당탕한 이미지를 띈 막이 형성됨.
- 생성된 막은 그룹에서 욕설이 많이 발생하고 있으니 위험하다는 것을 외부에 알려줌.

### Talking Agent
<img src="https://user-images.githubusercontent.com/103883786/209500541-51981fe0-ad05-4fdd-9b66-81a1ea5e4224.png" height="400"/>
<img src="https://user-images.githubusercontent.com/103883786/209500583-0458829d-5a05-4768-9627-d619746f0a43.png" height="400"/>

# 성과
- 메타버스 교육 플랫폼에 아이들의 발자취를 기록하여, 한쪽에 치우치지 않고 다양한 활동을 탐험할 수 있는 AI Agent 모델 제시
- 다양한 Talking NPC를 두고 대화 


