# Frontend Coding Assignment Guide

Thank you for your interest in the Frontend team at Phnyx Lab. This assignment is designed to assess your frontend development skills and evaluate your problem-solving abilities in a real work environment.

## Assignment Overview
- Understanding the requirements: ~2 hours
- Implementation time: ~10 hours
- Total estimated time: ~12 hours (manageable over a weekend)
- AI usage: You may use AI tools (e.g., ChatGPT) during this assignment.

## Assignment Details

Create a project based on the scenario given, and proceed to develop the tasks below.

## Required Features
- Project Management
  - Create, update, and delete projects.
- Chatbot
  - Receive structured responses from the server via SSE (Server-Sent Events) in real time based on user input, render them as HTML, and display them on the page.
  - External libraries are allowed.
- RAG Query
  - Receive Markdown-formatted responses from the server via SSE in real time based on user input, render them as HTML, and display them on the page.
  - Allows the use of external libraries. If there is a quote ([#-#]) in the rendered content, develop it as a clickable UI as shown below.
    - Quotes consist of the structure [{docnum}-{index}].
    - Only {docnum} is displayed on the screen.
    - If there are multiple identical {docnum}s in the quotes, only one {docnum} is displayed.
    - When a quote is clicked, a list of quotes ({docnum}-{index}) for the corresponding docnum is displayed through a browser alert.
    - The entire paragraph before the quote must also be clickable, and when clicked, a list of all corresponding quotes is displayed through a browser alert.

## Technical Requirements (Common)
- React 18 or 19 (Next.js available), TypeScript, Tailwind
- Design Implementation: Match the Figma design exactly.
- API Communication: Support both standard HTTP responses and event streams like SSE.
- BFF (Backend For Frontend): Optional; implement if you find it necessary.

The assignment is to be completed in your own environment. You will receive detailed instructions by email once you start. Please submit your results within 24 hours of receiving the assignment. If you have any questions, feel free to ask to frontend@phnyx.ai. We look forward to your great work.

## Appendix
- Assignment page: https://github.com/Phnyx-Lab/hiring-assignments-fe-2507
- Figma: https://www.figma.com/design/EGRDusCmKGHq0zE5N6NO4B/Frontend-Assignment?node-id=0-1&t=JPyKrmzB3aOuTRha-1
- Swagger: https://phnyx-lab.github.io/hiring-assignments-fe-2507/

--

# 프론트엔드 코딩 과제 안내
피닉스랩 프론트엔드팀에 관심을 가져주셔서 감사합니다. 본 과제는 지원자님의 프론트엔드 개발 역량을 확인하고, 실제 업무 환경에서 마주할 수 있는 문제 해결 능력을 평가하기 위해 마련되었습니다.
## 과제 안내
- 문제 이해 시간: 2시간 내외
- 문제 해결 시간: 10시간. 내외
- 총 예상 시간: 12시간 내외 (주말 동안 충분히 해결 가능한 수준)
- AI 활용: 과제 수행 시 AI 도구(예: ChatGPT)의 활용을 허용합니다.
## 과제 내용
주어진 시나리오에 따라 프로젝트를 생성하고, 아래 과제 개발을 진행해 주십시오.
### 필수 구현 기능:
- 프로젝트 관리
  - 기능: 프로젝트 생성, 수정, 삭제
- 챗봇
  - 기능: 사용자 입력 시 서버로부터 SSE(Server-Sent Events)를 통해 구조화된 형식의 응답을 실시간으로 수신하고, 이를 HTML로 렌더링하여 화면에 출력합니다.
  - 기술 요구사항: 외부 라이브러리 사용을 허용합니다.
- RAG 질의
  - 기능: 사용자 입력 시 서버로부터 SSE(Server-Sent Events)를 통해 Markdown 형식의 응답을 실시간으로 수신하고, 이를 HTML로 렌더링하여 화면에 출력합니다.
  - 기술 요구사항: 외부 라이브러리 사용을 허용합니다. 렌더링된 내용 중 인용구([#-#])가 있을 경우 아래와 같이 클릭 가능한 UI로 개발합니다.
    - 인용구는 [{docnum}-{index}] 구조로 구성됩니다.
    - 화면에는 {docnum}만 노출됩니다.
    - 인용구에 동일한 {docnum}이 여럿일 경우 하나의 {docnum}만 노출합니다.
    - 인용구를 클릭하면 해당하는 docnum의 인용구({docnum}-{index}) 목록을 browser alert을 통해 보여줍니다.
    - 인용구 앞 문단 전체도 클릭 가능하도록 해야하며, 이를 클릭 시 해당하는 모든 인용구 목록을 browser alert을 통해 보여줍니다.
## 기술적 요구사항 (공통)
- 사용 언어 및 프레임워크: React 18 or 19 (Next.js 사용 가능), TypeScript, Tailwind
- 디자인 구현: Figma로 제공된 디자인과 동일하게 웹 페이지를 구현해야 합니다.
- API 통신: 일반적인 HTTP Response 뿐만 아니라, SSE(Server-Sent Events)와 같은 이벤트 스트림 방식의 통신에도 대응할 수 있어야 합니다.
- BFF(Backend For Frontend): BFF 구현은 선택 사항입니다. 필요하다고 판단될 경우 구현하셔도 좋습니다.
  
과제 수행 방식과제는 지원자님의 자율적인 환경에서 진행됩니다. 과제 시작 시 메일로 상세 과제 내용이 전달되며, 전달받은 시점으로부터 24시간 이내에 결과물을 회신해 주시면 됩니다. 궁금한 점이 있으시면 frontend@phnyx.ai로 언제든지 문의해 주십시오. 지원자님의 멋진 결과물을 기대합니다.

## Appendix
- 과제 안내 페이지 : https://github.com/Phnyx-Lab/hiring-assignments-fe-2507
- Figma : https://www.figma.com/design/EGRDusCmKGHq0zE5N6NO4B/Frontend-Assignment?node-id=0-1&t=JPyKrmzB3aOuTRha-1
- Swagger : https://phnyx-lab.github.io/hiring-assignments-fe-2507/
