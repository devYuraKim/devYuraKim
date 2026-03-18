
---

## 👩🏻‍💻 Polyglot turned developer

### Full-Stack Developer&ensp;—&ensp;React · Spring Boot

- 6개 국어를 통해 **패턴과 체계, 그리고 의미 구조**를 다루는 사고방식을 체득했습니다.  
 이 통찰을 활용하여 **소프트웨어 아키텍처와 데이터 모델**을 설계합니다.  
 **논리와 언어, 그리고 문학**의 교차점에서 필요한 도구를 만듭니다.

- Six languages trained me to think in **patterns, systems, and structures of meaning**  
 — an approach I apply to **software architecture and data modeling**.  
 I build tools at the intersection of **logic, language, and literature**.

---

## 👷🏻 Current projects

### 1.&ensp;*pensées-concordance*&ensp;—&ensp;**Data Pipeline & Cross-Reference Engine**
**[ Python · React · Spring Boot · PostgreSQL ]**

> 블레즈 파스칼의 『*팡세*』를 위한 상호 참조 엔진  
> A cross-reference engine for Blaise Pascal's *Pensées*

<details>
<summary><b> 문제, 해결, 성과 | Problem, Approach, Impact </b></summary>
  
#### 문제 | Problem
- 『팡세』의 4대 주요 판본(*브륑슈비크, 라퓌마, 르 게른, 셀리에*)은 서로 다른 단편(fragment) 번호 체계를 사용합니다.  
판본 간 대조를 위해서는 약 40페이지가 넘는 대조표(concordance table)를 일일이 찾아봐야 하는 번거로움이 있습니다.

- Four major editions (*Brunschvicg, Lafuma, Le Guern, and Sellier*) use different fragment numbering systems.  
Cross-referencing them requires consulting more than 40 pages of concordance tables.

#### 해결 | Approach   

- **서로 다른 형식의 CSV 소스 데이터를 정규화하여 구조화된 JSON 스키마로 변환**하는 데이터 파이프라인을 구축했습니다.  
이를 기반으로 판본 간 빠른 대조가 가능하도록 **쿼리에 최적화된 통합 데이터 모델**을 설계했습니다.  

- Built a data pipeline that **transforms and normalizes heterogeneous CSV source data into a structured, flattened JSON schema**.  
Implemented a **unified, query-optimized data model** to support fast cross-edition lookups.  

#### 성과 | Impact    

- **40페이지가 넘는 대조표를 단 하나의 쿼리로 대체합니다.**
- **Replaces a 40-page concordance table with a single query.**  
&nbsp;  
</details>

<details open>
<summary><b> 저장소 | Repository </b></summary>

#### [Data Tooling Repository](https://github.com/devYuraKim/pensees-concordance-datatooling)

- 데이터 정규화, 검증 및 스키마 변환을 위한 **Python ETL 스크립트**.
- **Python ETL scripts** for data normalization, validation, and schema transformation. 
  
#### [Frontend Repository](https://github.com/devYuraKim/pensees-concordance-frontend)

- 단편(fragment) 탐색 및 판본 비교를 위한 **React 인터페이스**.
- **React interface** for fragment exploration and comparison.
 
#### [Backend Repository](https://github.com/devYuraKim/pensees-concordance-backend) 

- 관계형 매핑 및 인덱스 쿼리를 처리하는 **Spring Boot API**.
- **Spring Boot API** handling relational mappings and indexed queries.  
</details>

---

### 2.&ensp;*readingtrace*&ensp;—&ensp;**Annotation Engine & Real-time Discussion Platform**
**[ WebSocket · WebRTC · React · Spring Boot · MySQL ]**

> 독서 중 떠오르는 생각들을 기록하고 공유하는 플랫폼  
> A platform for tracing and sharing thoughts while reading

<details>
<summary><b> 문제, 해결, 성과 | Problem, Approach, Impact</b></summary>

#### 문제 | Problem  

- 독서는 혼자하는 활동이지만, 사유는 대화를 통해 확장됩니다.  
기존 도구들은 무엇을 읽었는지는 기록하지만, 생각이 어떻게 변하는지는 포착하지 못합니다.

- Reading is solitary. But ideas evolve through reflection and conversation.  
Most tools capture what you read. Few capture how your thinking changes.

#### 해결 | Approach  

- 개인의 마지널리아(여백 메모) 및 AI 대화를 기록합니다.  
현재는 채팅과 화상 회의를 지원하는 공유 공간으로 확장 중입니다.

- Records personal marginalia and AI-assisted discussion.  
Now expanding into a shared space with chat and video conferencing support.

#### 성과 | Impact    

- **실시간 WebSocket과 P2P WebRTC를 통해 개인의 메모를 공유된 대화로 전환합니다.**  
- **Turns private marginalia into shared dialogue through real-time WebSockets and P2P WebRTC.** 
&nbsp;  
</details>

<details open>
<summary><b> 저장소 | Repository </b></summary>

#### [Front/Backend Repository](https://github.com/devYuraKim/readingtrace)

- 마지널리아 기록, AI 대화, 실시간 채팅 및 화상 회의를 위한 **React 및 Spring Boot 통합 저장소**.  
- **Integrated React and Spring Boot repository** for marginalia capture, AI-assisted discussion, real-time chat, and video conferencing.

</details>

---

**I don't vibe code. I *[vibe code](https://youtu.be/4c8O2n1Gfto?si=lzrIAurylKIVzRnE)*.**
