---
layout: post
title: 프로그레시브 웹 앱이란?
authors:
  - samrichard
  - petelepage
date: 2020-01-06
updated: 2020-02-24
description: 프로그레시브 웹 앱(PWA) 및 이를 다른 웹 앱과 차별화하는 세 가지 주요 개념에 대해 소개합니다.
tags:
  - progressive-web-apps
---

웹은 놀라운 플랫폼입니다. 장치와 운영 체제 전반에 걸친 넓은 저변, 사용자 중심의 보안 모델, 그리고 단일 회사에서 사양이나 구현을 제어하지 않는다는 사실 등이 웹을 소프트웨어 개발을 위한 고유한 플랫폼으로 만들어줍니다. 고유한 연결 가능성과 결합하면 검색하고 찾은 내용을 어디서나 누구와도 공유할 수 있습니다. 웹 사이트를 방문할 때마다 최신 정보가 제공되며 해당 사이트에 대한 경험은 원하는 만큼 일시적이거나 영구적일 수 있습니다. 웹 애플리케이션은 단일 코드베이스를 사용하여 *모든 장치에서 모든 사람에게* 연결될 수 있습니다.

플랫폼별 애플리케이션은 믿을 수 없을 정도로 풍부하고 안정적인 것으로 알려져 있습니다. 홈 화면, 도크 및 작업 표시줄에 항상 존재합니다. 네트워크 연결에 관계없이 작동하며 자체 독립 실행형 환경에서 실행됩니다. 로컬 파일 시스템에서 파일을 읽고 쓸 수 있고 USB, 직렬 또는 블루투스를 통해 연결된 하드웨어에 액세스할 수 있으며 연락처 및 일정 이벤트와 같이 장치에 저장된 데이터와 상호 작용할 수도 있습니다. 이러한 애플리케이션에서 사진을 찍거나 홈 화면에 나열된 노래 재생을 확인하거나 다른 앱에 있는 동안 노래 재생을 제어하는 등의 작업을 수행할 수 있습니다. 플랫폼별 애플리케이션은 기반이 되는 장치의 *일부*인 것처럼 느껴집니다.

<figure class="w-figure">{% Img src="image/tcFciHGuF3MxnTr1y5ue01OGLBn2/1DKtUFjXLJbiiruKA9P1.svg", alt="높은 기능성, 웹 앱, 넓은 도달 범위 및 프로그레시브 웹 앱을 포함하는 플랫폼별 앱의 상대적 기능과 도달 범위를 보여주는 그래프.", width="370", height="367" %}<figcaption class="w-figcaption w-figcaption--fullbleed"> 플랫폼별 앱, 웹 앱 및 프로그레시브 웹 앱의 기능과 도달 범위 비교.</figcaption></figure>

플랫폼별 앱과 웹 앱을 기능 및 도달 범위 측면에서 생각해 보면 플랫폼별 앱은 최고의 기능을 보여주는 반면, 웹 앱은 최고의 도달 범위를 보여줍니다. 그렇다면 프로그레시브 웹 앱은 어느 위치에 있을까요?

프로그레시브 웹 앱(PWA)은 최신 API로 구축 및 강화되어 뛰어난 기능, 신뢰성 및 설치 용이성을 제공하는 동시에 단일 코드베이스로 *누구에게나 어디서나 모든 장치에서* 도달할 수 있습니다.

## 앱의 세 가지 주요 개념

프로그레시브 웹 앱은 기능, 안정성 및 설치 용이성이 보장되도록 설계된 웹 애플리케이션입니다. 이 세 가지 주요 개념은 플랫폼별 애플리케이션처럼 느껴지는 경험을 만들어줍니다.

### 기능성

웹은 오늘날 그 자체로 매우 유능합니다. 예를 들어 WebRTC, 지리 위치 및 푸시 알림을 사용하여 하이퍼로컬 화상 채팅 앱을 구축할 수 있습니다. 해당 앱을 설치 가능한 형태로 만들고 WebGL 및 WebVR을 사용하여 이러한 대화를 가상으로 가져올 수 있습니다. 웹 어셈블리의 도입으로 개발자는 C, C++ 및 Rust와 같은 다른 에코시스템을 활용하고 수십 년의 작업 결과물과 기능을 웹에서도 구현할 수 있습니다. 예를 들어 [Squoosh.app](https://squoosh.app/)은 고급 이미지 압축에 이를 활용합니다.

최근까지 플랫폼별 앱만이 이러한 기능을 실제로 제공할 수 있었습니다. 일부 기능은 아직 웹에서 접근할 수 없지만 새로운 API와 향후 출시될 API에 힘 입어 파일 시스템 액세스, 미디어 제어, 앱 배지 및 완전한 클립보드 지원과 같은 기능을 웹에서도 이용할 수 있게 될 것입니다. 이러한 모든 기능은 웹의 안전한 사용자 중심 권한 모델로 구축되어 웹 사이트가 사용자에게 두려운 환경으로 제기되지 않을 것입니다.

최신 API, 웹 어셈블리, 새로운 API와 향후 출시될 API를 배경으로 웹 애플리케이션은 그 어느 때보다 많은 기능을 제공하며 이러한 기능은 계속해서 증가하고 있습니다.

### 신뢰성

안정적인 프로그레시브 웹 앱은 네트워크에 관계없이 빠르고 신뢰할 수 있습니다.

속도는 해당 환경으로 사용자를 *끌어들이기* 위해 매우 중요한 부분입니다. 실제로 페이지 로드 시간이 1초에서 10초로 늘어나면 사용자가 이탈할 확률은 [123% 증가합니다](https://www.thinkwithgoogle.com/marketing-resources/data-measurement/mobile-page-speed-new-industry-benchmarks/). `onload` 이벤트 후에도 성능의 중요성은 끝나지 않습니다. 사용자는 버튼 클릭과 같은 상호 작용이 등록되었는지 여부를 궁금해하지 않아야 합니다. 스크롤과 애니메이션은 부드럽게 느껴져야 합니다. 성능은 사용자가 애플리케이션을 인식하는 방식부터 실제 성능에 이르기까지 전체적인 경험에 영향을 줍니다.

마지막으로, 네트워크 연결에 관계없이 안정적인 애플리케이션을 사용할 수 있어야 합니다. 사용자는 앱이 느리거나 불안정한 네트워크 연결 또는 오프라인 상태에서도 시작되기를 기대합니다. 그들은 서버에서 요청을 받는 것이 어려운 경우에도 미디어 트랙, 티켓 및 여행 일정과 같이 최근에 상호 작용한 콘텐츠를 사용할 수 있기를 기대합니다. 요청이 불가능할 때라도 그저 장애를 일으키거나 충돌하는 대신 문제에 대해 안내를 받기를 기대합니다.

사용자들은 눈 깜짝할 사이에 요청에 반응하는 앱과 신뢰할 수 있는 경험을 좋아합니다.

### 설치 가능성

설치된 프로그레시브 웹 앱은 브라우저 탭 대신 독립 실행형 창에서 실행됩니다. 이러한 앱은 사용자의 홈 화면, 도크, 작업 표시줄 또는 쉘프에서 실행할 수 있습니다. 기기에서 검색하고 앱 전환기로 전환할 수 있어 앱이 설치된 기기의 일부처럼 느껴지도록 할 수 있습니다.

웹 앱을 설치하고 나면 새로운 기능이 열립니다. 일반적으로 브라우저에서 실행할 때 예약되어 있던 바로가기 키를 사용할 수 있게 됩니다. 프로그레시브 웹 앱은 다른 애플리케이션의 콘텐츠를 수락하도록 등록하거나 다른 유형의 파일을 처리하기 위한 기본 애플리케이션으로 등록할 수 있습니다.

프로그레시브 웹 앱이 탭을 벗어나 독립 실행형 앱 창으로 이동하면 사용자가 생각하고 상호 작용하는 방식 대로 환경이 바뀝니다.

## 두 세계의 장점만 결합

기본적으로 프로그레시브 웹 앱은 웹 애플리케이션에 불과합니다. 점진적 향상을 통해 최신 브라우저에서 새로운 기능을 사용할 수 있습니다. 서비스 워커와 웹 앱 매니페스트를 사용하면 웹 애플리케이션이 안정적이 되고 설치가 가능해집니다. 새 기능을 사용할 수 없는 경우에도 사용자는 핵심 환경을 계속 사용할 수 있습니다.

숫자는 거짓말을 하지 않습니다! 프로그레시브 웹 앱을 출시한 회사는 인상적인 결과를 얻게 됩니다. 예를 들어 Twitter는 세션당 페이지 수가 65% 증가하고 트윗이 75% 증가했으며 이탈률은 20% 감소하는 동시에 앱 크기는 97% 이상 줄었습니다. PWA로 전환한 후 Nikkei는 유기적 트래픽이 2.3배, 구독이 58%, 일일 활성 사용자가 49% 증가했습니다. Hulu는 플랫폼별 데스크톱 경험을 프로그레시브 웹 앱으로 교체한 후, 재방문 횟수가 27% 증가하는 결과를 거두었습니다.

프로그레시브 웹 앱은 사용자가 좋아할 웹 경험을 제공할 수 있는 독특한 기회를 제공합니다. 최신 웹 기능을 사용하여 향상된 기능과 안정성을 제공하는 프로그레시브 웹 앱을 사용하면 구축한 앱을 *단일 코드베이스*로 누구나, 어디서나, 모든 장치에 설치할 수 있습니다.