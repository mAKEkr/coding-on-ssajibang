# Coding on Ssajibang(Cyber knowledge/infomation room)
### 싸지방(사이버지식정보방)에서 코딩을 해봅시다!
군대라는 환경안에서, 코딩을 하기는 매우 어렵습니다. 그렇지만 저도 그 고충을 알기에, "나는 아무것도 준비가 안되어있는데!", "어떻게 시작해야될지 막연해요!" 라고 말씀해주시는 분들을 위해서 준비했습니다.

해당 게시물은 Apache License 2.0 라이센스를 적용하였습니다.

## 주의점
- 싸지방에서 프록시 사용은 불법입니다. 프록시등을 이용하여 우회시도를 하지마세요.
- 싸지방에서 비인가 프로그램 설치도 불법입니다(컴파일러, 에디터등). 그렇기때문에 웹IDE 사용을 권장합니다!
- 게시물에서 적는 기준들은 2016년 기준입니다.
- AWS/Github등이 차단되어 접속이 안될경우 친구에게 요청하여 이 링크의 문서를 요청하세요! github.io의 접속이 가능한경우 Github Pages로 [생성된 페이지](https://makekr.github.io/coding-on-ssajibang)에서 접속이 가능합니다.

### 차단되어있는 사이트
- Github(방화벽단에서 차단됨, aws서버를 이용하기때문으로 판단됨. Github가 MS에 인수된 이후 변경되었을 수 있음)
  - 다른 Git 호스팅 서비스인 Bitbucket, GitLab등은 접속이 되는것으로 마지막으로 확인했음
- AWS 및 AWS 도메인을 이용하는 사이트들(aws 대시보드 및 여타 다른 서비스들)

## 준비물
- **신용카드**

나라사랑카드 말고 해외결제가 가능한 카드를 준비합니다. 비자, 마스터카드요. 설마 없겠어요?

- **웹브라우저**

크롬쓰시던가 파이어폭스 쓰시던가 오페라 쓰시던가 상관없지만 절대로 **`익스플로러`** 만 쓰지마세요.

- **가상머신(Virtual Machine)**

가상머신의 경우 컴퓨터에 직접 설치하는 방식보다는 가상서버(Virtual Privated Server)를 이용하시거나 클라우드를 이용하시는 편을 추천드립니다.

- **웹 IDE(Integrated Development Environment)**

웹 IDE는 컴퓨터에 설치하여 이용하는 에디터와 흡사합니다. 코드 하이라이팅(코드에 색을 주어 가독성을 높혀주는것)과 심지어 가상머신도 없는 여러분들에게 가상머신을 나누어주는 웹 IDE들도 많으니까요. 몇개 쓸만한것들만 소개해드릴게요.

### 가상머신
- [Vultr](http://www.vultr.com/)

단순 개발목적인데, ConoHa만큼의 사양이 필요없다면 Vultr도 좋은 대안입니다. 최저가격은 한달에 5달러. 역시 Paypal을 통한 결제가 가능합니다.
스냅샷기능을 지원하고 ConoHa처럼 번거롭기도 합니다. 스냅샷이 ConoHa보다는 느려서, 정말 돈이 없을때, 아니면 시험삼아 해보고싶을때 쓰니는걸 추천드립니다.

- [ConoHa](https://www.conoha.jp/)

단순 개발목적의 경우 백업한 뒤에 서버를 켜고/끄기만 하면 끝. 가격은 시간당 1.3엔이며 Paypal을 통한 결제가 가능합니다.
진짜 돈없는 군인들을 위한 완벽한 요금체계이지만, 번거롭다는 단점이 하나 있습니다.
API를 통하여 기본제공하는 OS 외의 다른 OS도 설치 가능합니다.(윈도우 설치를 통해 VNC 접속이 가능합니다!)

- [AWS(Amazon Web Services)](https://aws.amazon.com/ko/) **AWS 차단시 우회필요**

프리티어를 통해 최소규모의 가상서버를 1년간 무료로 사용할 수 있습니다. 개발규모로는 적합하죠.
최근에 한국 로케이션도 오픈되어서 속도도 해외보다 빠른편입니다.
대신 IP를 발급받거나, 네트워크 통신량이 많아진다면 요금폭탄이 나오는 편이니 주의합니다.

- [Microsoft Azure](https://azure.microsoft.com/ko-kr/)

한달간 무료로 사용할수 있는 크레딧을 발급해주기에 부담은 없지만, 한달이 지나면 가격부담은 꽤 되는 편입니다.
외출/외박/휴가시 마이크로소프트에서 "Azure 잘 사용하셨나요?" 전화가 올수도 있습니다.

- [Amazon Lightsail](https://aws.amazon.com/ko/lightsail/) **AWS 차단시 우회필요**

아마존 웹 서비스에서 직접 운영하는 아마존 버전의 VPS입니다. 입/출력이 느린것이 단점인데, 비교적 저렴한 서버 비용과 아마존 회선 사용등이 장점입니다. 해외 접속이 많다면 사용을 고려해보세요.


### 웹 IDE(개발용 VM 지원)
- [CodeAnywhere](http://codeanywhere.com)

제가 생각하기엔 얘가 퍼포먼스나 콘솔 반응속도나 최강인것같아요. 요즘들어 가끔 끊기는 일이 조금씩 생기긴 하는데, 그래도 이만한 에디터가 없어요. 밖에서도 집에서 쓰던 에디터(서브라임 텍스트 ㅠㅠ) 버리고 얠 쓰고있습니다. 포트 접속에 제한이 있는 싸지방을 위해서 VM에 접속할때 포트 프록시 기능도 있답니다. 강력추천.

- [AWS Cloud9](https://aws.amazon.com/ko/cloud9/) **AWS 차단시 우회필요**

해외에서 개발된 초기 웹 IDE인데 AWS에 인수된 뒤로 꾸준히 운영되고 있습니다. 퀄리티는 장담 못하는데 그래도 차차 개선되리라 보고있어요.


### 웹 IDE(개발용 VM 미지원)
- [Codepen.io](https://codepen.io)

웹개발자(프론트엔드)들의 놀이터입니다. 웹 디자이너나 웹 개발자들이 많이 자신의 예제를 올려둡니다. 메인에 있는 예제들을 보고 수정만 할 수 있어도 코딩 능력이 올라가는 느낌이 드실겁니다.

- [JSFiddle](https://jsfiddle.net/)

codepen과는 비슷한 서비스이지만, 파일들을 한데모아 관리할 수 있는 이점이 있는 IDE입니다. 공유하여 타인에게 링크를 보내줄수도 있어요.

- [IDEOne](https://ideone.com/)

거의 모든 언어에 대한 출력물을 확인 할 수 있습니다. 책의 예제들을 코딩해보거나, 간단한 Hello world 혹은 알고리즘에 대한 계산을 하기에는 가장 좋습니다.

## 본격적으로 코딩 시작하기

프로그래밍을 시작하시려는 분들이 대다수일겁니다. 이유가 많은텐데(예를들면 "이제라도 전공공부를 하고싶어!", "프로그래밍에 관심이 있는데 군대 안에서 뭐라도 배워가고싶어!" 등등..) 이유가 어찌되었던 옆에서 가르쳐줄 수 있는 선생님이 있지 않은 한 공부를 하기는 정말 막막합니다. 그렇기에, 여러분들에게 공부를 할 수 있는 좋은 방안들을 알려드리려고 합니다.

### 온라인으로 코딩 배우기

주의하실점은 제가 웹 프론트/백엔드 개발자라서 알려줄게 많이 없지만, 그래도 굳이 추천해주자면 이 사이트들 혹은 방법들을 추천해주고 싶네요.

- [생활코딩](https://opentutorials.org/course/1)
이전에는 생활코딩 사이트 자체였지만, 현재는 교육 오픈플랫폼으로 변화한 사이트입니다. 모든 강의가 무료이며, 강의 내용은 유튜브를 통하여 볼 수 있습니다.

- 각종 프로그래밍 언어들의 공식 사이트 문서
이게 도움이 안될거라고 생각하지 말고, 차근차근 문서를 번역하면서 읽어보길 바래요. 공식 스펙 문서가 없는 경우에는 epub혹은 pdf등으로 무료로 배포하는 ebook등을 이용한다면 도움이 된답니다.

### 알고리즘 풀어보기

알고리즘은 여러분이 프로그래밍을 할때 사고 대처력

- [백준온라인저지](https://www.acmicpc.net/)
알고리즘을 온라인으로 풀어본 사람들이라면 익숙한 사이트입니다.

- [프로그래머스](https://programmers.co.kr/)
실제 코딩테스트가 진행되는 사이트입니다. 카카오 블라인드채용등이 진행된곳으로 구글에 카카오 블라인드 채용으로 검색하시면 특정 년도의 문제들을 직접 풀어볼 수 있습니다

## 질문이 있으신가요?
질문이 있으시다면 해당 저장소 위편에 있는 Issues 버튼을 통하여 질문을 남겨주세요! :)
