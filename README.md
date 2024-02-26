현존하는 대다수의 AI 서비스는 비장애인을 대상으로 만들어졌기에 신체적 제약이 존재하는 장애인은 서비스에 접근조차 어려운 경우가 대다수이다. 
특히, 최근 눈부신 기술 발전을 보이는 이미지 생성 AI 역시Text-to-Image 인공지능 모델을 기반으로 하여 텍스트의 입력이 필수적이다. 
때문에, 키보드나 마우스 같은 입력 장치를 사용하지 못하는 이들에게 있어 AI 활용의 장벽은 더욱 높아지고 있다.
본 애플리케이션은 이러한 문제를 해결하기 위해 마우스와 키보드 없이도 음성 인식을 통해 서비스를 자유롭게 이용할 수 있도록 하였다. 
또한 디지털 기술에 취약한 이들도 디지털 이미지를 만들수 있도록 인공지능을 활용한 이미지 생성 기술에 접근하는 방법을 설명한다.
본 애플리케이션은 음성 인식 기술인 STT(Speech To Text)의 개인별 활용과더불어 AI 이미지 생성 서비스가 겪고 있는 문제점인 예술 창의성 지표를 높이는 것을 목적으로 하였다. STT로 기록된 텍스트는 번역 API를 통해 한 번 더 가공된다. 
창작 이미지 생성에는 생성형 AI 모델 중스테이블 디퓨전 (Stable Diffusion)을 사용하였다. 
예술 창의성 지표를높이기 위한 방법으로 OpenCV를 이용해 이미지 수정 및 편집이 가능하도록 하였다. 
이 외에도 언리얼 엔진을 기반으로 한 메타버스 공간 구축및 콘텐츠 개발을 통해 대중의 접근성을 확장하고자 및 콘텐츠 개발을 통해 대중의 접근성을 확장하고자 한다.

![image](https://github.com/gahyeon11/AI_Image_with-voice/assets/117976216/e51e89d8-49e3-42dc-86de-554bc49317cc)

*모든 단계는 음성 및 마우스로 동
로그인
- 사용자 정보를 DB에 저장
이미지 생성
- 모든 과정은 키보드, 마우스 뿐만 아니라 음성으로도 동작 가능
- 사용자의 음성 값을 프롬프트로 받아 필터링하여 이미지 생성
- 초보자 단계의 경우, 모든 과정에서 선택지 부여
- 전문가 단계의 경우, 프롬프트를 직접 입력 받아 상세히 조정 가능, 배경과 오브젝트를 각각 생성 가능
이미지 편집
- 배경 이미지가 아닌 오브젝트 이미지들의 배경을 제거하여 투명 파일로 전환
- 사용자의 입력값을 데이터로 받아 OpenCV를 이용해 이미지의 위치값 조정
- 원하는 필터를 선택지를 통해 적용
이미지 저장
- 이미지를 지정 폴더에 저장
- DB 내에 이미지의 정보와 사용자의 아이디 저장
이미지 전시
- 생성 완료된 이미지를 DB에 저장한 뒤 전시 공간 내에 호출
전시 공간
- 언리얼로 제작된 공간 내에서 기본적인 이동 기능 구현
- 전시 공간 내에 사용자가 전시한 이미지 및 다른 사용자의 전시 이미지 게시
- 두 가지 컨셉의 테마로 제작하여 장애인과 비장애인의 구분 없이 동등한 경험을 제공

