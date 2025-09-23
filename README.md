# 컴퓨터 비전을 활용한 조류 분석 게임 개발

### 1. 프로젝트 소개
#### 1.1. 배경 및 필요성
>  전 지구적으로 조류 개체 수는 심각한 감소 추세, 조류 멸종 속도는 점차 가속화되어 현대에 이르러 심각한 수준

**멸종위기종 보호에 대한 정보 부족**
 우리나라 국민들은 멸종위기종 보호에 대한 높은 수준의 관심과 필요성을 인지하고 있으나, 구체적인 실천 방법에 대한 정보는 부족한 것으로 나타났다. 국립생태원 멸종위기종복원센터가 2021년 발표한 '멸종위기종 대국민 인식조사' 결과에 따르면, 국민 대다수는 멸종위기종 문제에 깊이 공감하고 있었다. 주요 결과는 다음과 같다.

 멸종위기종을 위협하는 가장 큰 요인으로 '불법 포획'(48.2%)을 꼽았으며, '도로 확장 등 서식지 파괴'(24.9%), '기후변화'(12.8%)가 그 뒤를 이었다. 이는 인간의 직접적인 활동이 멸종위기종의 생존에 가장 큰 위협이 된다는 점을 명확히 인지하고 있음을 보여준다.
 불법 포획 및 채취 행위를 목격했을 때 신고하겠다는 응답은 98.7%에 달했으나, '어디에 신고해야 하는지 모른다'는 응답이 82.5%에 달해, 높은 보호 의지에 비해 실질적인 행동으로 이어질 수 있는 정보가 부족한 현실을 드러냈다.

 이러한 결과는 멸종위기종 보호에 대한 국민적 공감대는 충분히 형성되어 있으나, 이를 효과적인 실천으로 유도할 수 있는 구체적인 정보 제공과 교육 및 홍보의 필요성이 시급함을 보여주고 있다.


#### 1.2. 목표 및 주요 내용
> 사회·생태학적 문제에 대한 혁신적인 해결책을 제시. 실시간 조류 식별 파이프라인을 핵심 기능으로 탑재한 모바일 애플리케이션을 개발하고, 그 교육적·환경적 효용성을 평가

**시민 과학의 대두와 생태 데이터 수집의 중요성**

 조류는 생태계의 건강 상태를 가늠하는 핵심적인 지표종(indicator species)이다. 조류의 개체 수, 종 다양성, 번식 성공률 등은 특정 지역의 환경 변화, 오염 수준, 서식지 안정성을 민감하게 반영한다. 따라서 조류에 대한 체계적인 모니터링은 생태계 보전 전략 수립에 필수적인 데이터를 제공한다. 그러나 전문 연구 인력만으로는 광범위한 지역에 걸쳐 장기적인 데이터를 수집하는 데 명백한 한계가 존재한다.

 이러한 한계를 극복하기 위한 대안으로 '시민 과학(Citizen Science)'이 전 세계적으로 주목받고 있다. 시민 과학은 일반 대중이 자발적으로 과학 데이터 수집 및 분석 과정에 참여하는 활동을 의미한다. 특히 스마트폰 기술의 발전은 시민 과학의 패러다임을 혁신적으로 바꾸었다. '버드고(GO)'는 이러한 흐름에 발맞추어 설계되었다. 사용자가 조류를 촬영하고 식별하는 행위 자체가 귀중한 생태 데이터가 되며, 특히 GPS 기반 관찰 기록 마커 기능은 모든 사용자의 데이터를 취합하여 특정 지역의 조류 출현 빈도 및 분포를 시각화하는 집단 데이터베이스 구축의 가능성을 열어준다. 이는 단순한 개인의 즐거움을 넘어, 학술적 가치를 지닌 생태 데이터 플랫폼으로 발전할 수 있는 잠재력을 시사한다.

**게이미피케이션: 환경 교육과 행동 유도의 새로운 패러다임**

멸종위기종을 보호하기 위해서는 사람들의 인식을 개선하기 위한 다양하고 적극적인 방법의 모색이 필요하다. 이러한 상황에서, 'Development of a Game to Improve Awareness of Endangered Species' 논문을 참고해보면, 멸종위기종에 대한 인식 개선을 위해 게임이라는 미디어를 활용하는 것이 효과적인 교육 방법이 될 수 있음을 알 수 있다. 논문에 따르면 게임을 활용한 교육은 다음과 같은 장점을 가진다.

- 게임은 많은 사람에게 높은 접근성을 가지고 있다.
- 단순 이론 교육보다 미디어를 통한 교육이 수요가 더 높다.
- 온라인 콘텐츠 형태의 교육은 학습자의 스트레스 감소에 긍정적인 영향을 줄 수 있다.

 위와 같은 연구 배경을 바탕으로, 본 프로젝트는 게임이 가진 고유한 장점을 활용하여 멸종위기종에 대한 대중의 인식을 효과적으로 개선하고자 한다.
그래서 '게이미피케이션(Gamification)'을 핵심 전략으로 채택했다. 프로젝트 기획 단계에서 "포켓몬고"와 같은 성공적인 위치 기반 증강현실 게임을 벤치마킹했으며, 그 핵심 성공 요인을 분석하여 프로젝트에 적용했다.

### 2. 상세설계
#### 2.1. 시스템 구성도
<img width="1138" height="813" alt="System Archietecture" src="https://github.com/user-attachments/assets/52146211-9e43-4fea-bd35-f9a6fe0bb707" />

#### 2.1. 사용 기술
> Unity 6000.0.44f1 </br>
Rider 25.1 </br>
YOLOv8

### 3. 설치 및 사용 방법
> [안드로이드 설치 링크](https://drive.google.com/drive/folders/1vkZsNg34BzkPc6Y4NStwNXop-_dcwQ9F?usp=sharing)

### 4. 소개 및 시연 영상
> 새를 찾고 도감에 저장하세요! 다른 사람들의 수집 현황을 볼 수도 있어요

[Youtube 시연 영상]([https://youtube.com/shorts/NoIH8CoMS8M)
| ![BIRDGO_시연영상 - frame at 0m21s](https://github.com/user-attachments/assets/88c4d8cc-0083-4fdc-9241-3c0dd163ff37) | ![BIRDGO_시연영상 - frame at 0m43s](https://github.com/user-attachments/assets/0f394cb9-61a0-4eec-9037-4d6febc14970) | ![BIRDGO_시연영상 - frame at 0m49s](https://github.com/user-attachments/assets/b11d6760-3240-47c6-86e7-ebe890eb15b0) |
|---|---|---|
| 다른 사람 새들 확인 | 카메라 앱 | 로딩창... |
| ![BIRDGO_시연영상 - frame at 0m53s](https://github.com/user-attachments/assets/56668fa5-d536-4454-99e3-330b7d6d9eb2) | ![BIRDGO_시연영상 - frame at 1m23s](https://github.com/user-attachments/assets/0831c2bd-8d79-4292-aa73-6b740518eb10) | ![BIRDGO_시연영상 - frame at 1m32s](https://github.com/user-attachments/assets/ac32b25e-303f-4db1-96f1-6268a839780a) |
| 왜가리 수집 | 따오기 수집 | 도감 컬렉션 |




### 5. 팀 소개

<table>
      <tr>
    <td align="center">
        개발자
      </a>
    </td>
    <td align="center">
        개발자
      </a>
    </td>
    <td align="center">
        개발자
      </a>
    </td>
  </tr>
  <tr>
    <td align="center" width="200px">
      <a href="https://github.com/jungse8609" target="_blank">
        <img src="https://avatars.githubusercontent.com/u/69056797?v=4" alt="정국경 프로필" />
      </a>
    </td>
    <td align="center" width="200px">
      <a href="https://github.com/HOOGAEM" target="_blank">
        <img src="https://avatars.githubusercontent.com/u/126786781?v=4" alt="김후겸 프로필" />
      </a>
    </td>
    <td align="center" width="200px">
      <a href="https://github.com/Shim0Hwan" target="_blank">
        <img src="https://avatars.githubusercontent.com/u/73728119?v=4" alt="심영환 프로필" />
      </a>
    </td>
  </tr>
  <tr>
    <td align="center">
      <a href="https://github.com/jungse8609" target="_blank">
        정국경
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/HOOGAEM" target="_blank">
        김후겸
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/Shim0Hwan" target="_blank">
        심영환
      </a>
    </td>
  </tr>
  <tr>
    <td align="center">
      jungse8609@gmail.com
    </td>
    <td align="center">
      rlagnrua3@pusan.ac.kr
    </td>
    <td align="center">
      jpsl7202@pusan.ac.kr
    </td>
  </tr>
  <tr>
    <td align="center">
      Unity 게임 제작
    </td>
    <td align="center">
      AI 모델 학습 및 최적화
    </td>
    <td align="center">
      UI/UX 디자인, 문서 작업
    </td>
  </tr>
</table>
