# 🐼 모두가 참여할 수 있는 무선데이터 공유 플랫폼, DAPANDA

<img width="1920" height="1080" alt="readme-main" src="https://github.com/user-attachments/assets/6a41d719-2ad2-4bd3-af70-8654296c6d69" />

## 🧾 프로젝트 개요

- **프로젝트명**: **DaPanDa**
- **팀명**: 다판다
- **개발 기간**: 2025.06.30 (월) ~ 2025.08.07 (목)

## 💡 기획 배경

가족·지인 간 통신 데이터를 비공식적으로 나누는 현실은 번거롭고 불투명하며, 사용하지 못한 데이터는 소멸되기 쉽습니다.

**DaPanDa**는 이러한 문제를 해결하고 **데이터를 자산처럼 자유롭게 사고팔 수 있는 공식 거래 플랫폼**을 구축하고자 시작되었습니다.

단순한 거래를 넘어 **데이터, 핫스팟, 와이파이 등 다양한 네트워크 자산을 등록·판매**할 수 있도록 하여, **개인부터 소상공인까지 참여 가능한 디지털 공유 생태계**를
지향합니다.

## 🎯 문제 정의와 솔루션

### ❗ 문제 정의

1. **비공식적 데이터 공유의 불편함과 위험성**
    - 가족이나 지인끼리 데이터를 주고받는 과정은 번거롭고 제한적이며 통신사 정책과 충돌할 수 있습니다.
    - 명확한 중개 시스템 없이 이루어지는 거래는 **보안, 신뢰성, 거래 편의성 모두 부족**합니다.

2. **데이터 거래 플랫폼의 부재**
    - 사용하지 않은 데이터를 활용하거나 판매할 수 있는 **공식적인 플랫폼이 존재하지 않습니다.**

3. **단일 용도의 데이터 유통 구조**
    - 기존에는 통신 데이터만 공유·거래할 수 있고, **개인의 핫스팟이나 매장 와이파이 등의 네트워크 자산을 수익화할 수 있는 방법은 전무**했습니다.

### ✅ 솔루션

1. **공식적인 데이터 거래 생태계 제공**
    - DaPanDa는 **PG 연동 결제, 인증된 사용자 간의 거래, 채팅/알림 시스템**을 갖춘 **데이터 자산 거래의 공식 플랫폼**입니다.
    - **소셜 로그인과 마이페이지 기반 인증 시스템**으로 신뢰성을 확보하였고, **캐시 충전·환불 기능을 통한 안전한 거래**를 지원합니다.

2. **자투리 구매 & 분할 판매 기능 제공**
    - 구매자는 원하는 데이터 용량을 입력하면, **최저가로 여러 판매자의 자투리 데이터를 조합**해 **최적의 구매 조합**을 제안받습니다.
    - 판매자가 데이터를 등록하면 **알아서 자동 분할 판매**가 되어 효율적인 수익화를 기대할 수 있습니다.

3. **다양한 무선인터넷 용량 자산 거래 지원**
    - 단순한 데이터 거래를 넘어서, **개인의 핫스팟, 매장 단위 와이파이 등 네트워크 자산을 등록 및 판매 가능**하게 함으로써 **소상공인까지 아우르는 새로운 시장**을
      창출합니다.

### 🎯 주요 타겟

- **LG U+ 사용자 중** 요금제를 바꾸지 않고도 **소량 데이터를 사고 싶은 사용자**
- 남는 데이터를 **판매해 수익을 얻고자 하는 사용자**
- **합리적 소비**와 **가치 소비**에 민감한 **20~40대**
- 그리고 **빨래방, 편의점 등 매장 단위로 와이파이를 판매하려는 소상공인**

### 🧩 DaPanDa만의 차별점

#### ✅ 1. **자투리 구매 & 분할 판매** 지원

- 원하는 데이터 용량을 입력하면, **여러 판매자의 자투리 데이터를 조합**해 **가장 저렴한 가격의 최적 조합**으로 제공해줍니다.

- 판매자가 데이터를 등록하면 **구매자가 원하는 단위로 자동 분할 판매**되어 **신경 쓰지 않아도 되는 수익화가 가능**합니다.

#### ✅ 2. **와이파이 판매까지 지원하는 유일한 플랫폼**

- 단순한 데이터 공유를 넘어서 **빨래방, 카페, 편의점 등 매장 와이파이도 등록 및 거래**할 수 있는 구조를
  갖추었습니다.

- 이를 통해 실질적인 **오프라인 유휴 네트워크 자원도 수익화**할 수 있게 됩니다.

## ✨ 핵심 기능 요약

- **소셜 로그인 및 마이페이지 기반 인증/인가 시스템**
- **데이터 / 와이파이 상품 등록 및 실시간 거래**
- **실시간 채팅 기능 및 거래 알림**
- **PG 연동 결제 + 캐시 충전 및 환불**
- **리뷰 등록 / 신고 접수**
- **시스템 모니터링**

## ⚙️ 기술 스택

| Category           | Technologies   |
|--------------------|-----------------------|
| **Frontend**        | ![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white) ![Shadcn UI](https://img.shields.io/badge/Shadcn_UI-000000?style=for-the-badge&logo=radixui&logoColor=white) ![Framer Motion](https://img.shields.io/badge/Framer_Motion-EF4444?style=for-the-badge&logo=framer&logoColor=white) ![Lucide](https://img.shields.io/badge/Lucide-000000?style=for-the-badge&logo=lucide&logoColor=white) ![Zustand](https://img.shields.io/badge/Zustand-F59563?style=for-the-badge&logo=zoo&logoColor=white) ![React Query](https://img.shields.io/badge/React_Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white) ![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white) ![TanStack Virtual](https://img.shields.io/badge/@tanstack/react--virtual-3178C6?style=for-the-badge&logo=react&logoColor=white) ![Dynamic Import](https://img.shields.io/badge/Dynamic_Import-000000?style=for-the-badge&logo=javascript&logoColor=white) ![Code Splitting](https://img.shields.io/badge/Code_Splitting-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) ![Lucide](https://img.shields.io/badge/Lucide-000000?style=for-the-badge&logo=lucide&logoColor=white) ![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white) ![RTL](https://img.shields.io/badge/React_Testing_Library-E33332?style=for-the-badge&logo=testinglibrary&logoColor=white) ![MSW](https://img.shields.io/badge/MSW-FF6A33?style=for-the-badge&logo=msw&logoColor=white) ![Firebase Cloud Messaging](https://img.shields.io/badge/FCM-FFCA28?style=for-the-badge&logo=firebase&logoColor=black) ![Web Push API](https://img.shields.io/badge/Web_Push_API-2D9ED6?style=for-the-badge&logo=pushbullet&logoColor=white) |
| **Analytics**     | ![Hotjar](https://img.shields.io/badge/Hotjar-FF3C2E?style=for-the-badge&logo=hotjar&logoColor=white) ![Vercel Analytics](https://img.shields.io/badge/Vercel_Analytics-000000?style=for-the-badge&logo=vercel&logoColor=white) |
| **Backend**        | ![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white) ![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white) ![OAuth2](https://img.shields.io/badge/OAuth2-F26D00?style=for-the-badge&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white) ![QueryDSL](https://img.shields.io/badge/QueryDSL-009688?style=for-the-badge&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white) ![WebSocket](https://img.shields.io/badge/WebSocket-3C3C3C?style=for-the-badge&logo=websocket&logoColor=white) ![JUnit 5](https://img.shields.io/badge/JUnit_5-25A162?style=for-the-badge&logo=junit5&logoColor=white) ![Mockito](https://img.shields.io/badge/Mockito-FFCB2B?style=for-the-badge&logo=java&logoColor=white) ![Jacoco](https://img.shields.io/badge/Jacoco-B40000?style=for-the-badge&logoColor=white) ![Spring REST Docs](https://img.shields.io/badge/Spring_REST_Docs-6DB33F?style=for-the-badge&logo=spring&logoColor=white) ![JMeter](https://img.shields.io/badge/JMeter-D22128?style=for-the-badge&logo=apachejmeter&logoColor=white) |
| **Infra / DevOps** | ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)       |              
| **Monitoring**     | ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white) ![Loki](https://img.shields.io/badge/Loki-F46800?style=for-the-badge&logo=loki&logoColor=white)                                |
| **Collaboration** | ![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white) ![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white) ![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white) |

## 📱 기능 시연 영상


