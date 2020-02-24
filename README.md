# WEB-study
HTML,  CSS, Javascript


정보기술은 역사가 길지 않다. 
좋게 말하면 최신이고,
않좋게 말하면 근본이 약하다. 
그 부족한 근본을 어디서 채웠는가?
많은것을 일상에 대한 비유와 은유이다. 
그런 점에서 컴퓨터는 하나의 거대한 <strong><u>시</u></strong>이다.
컴퓨터가 차갑게 느껴질 수 있지만,
컴퓨터 공학은 사실 낭만적인 것들로 가득 차 있다. 

HTML의 여러 태그 중에
무엇인가를 설명하지 않는 태그들은
감싸야하는 컨텐츠가 없기 때문에
태그를 닫지 않는다는 규칙이 있습니다.
img, input, br(줄바꿈), hr, meta 등이 
닫지 않는 태그의 사례입니다.


단락 표현에는 구간을 정할 수있는 p,/p 가 좋으나 단락과 단락을 띄울수 있는 거리가
정해져 있어 가독성이 떨어 질 수 있다. 
그러나 br 태그는 쓰는 만큼 간격을 벌릴 수 있다. 
웹에는 CSS 라는 기술이 있는데 이를 이용하면 이러한 한계를 극복할 수 있다. (11L) 참조

<img src = "이미지파일 경로 또는 웹페이지 주소" 이미지를 게시할 수 있다. 

<li></li> 를 사용한 내용에는 머리말이 붙는다  (2L 참조)

몇몇 태그들 중에는 부모자식 태그라고 해서 서로 같이 쓰이는 태그들이 있다. 
<ul></ul> unorderd 정렬 안함
<ol></ol> ordered 내림차순으로 정렬 해 줌

<a></a> 태그는 다른 웹페이지 링크를 걸어주는 태그이다. a는 anchor 의 약자이다. 
href 는  HyperText Reference 의 약자이다. 

<a href="https://www.w3.org/TR/html5/" target="_blank" title="html5 specification">
Hypertext Markup Language (HTML)</a>

여기서 <a> 태그 안에 링크를 넣어줄 주소, 정보, 텍스트를 지정한다. target="blank" 는 링크를 클릭했을 때
    새창으로 연다는 뜻이고 title 은 링크가 어떤 내용을 담고 있는지 툴팁으로 보여주는 기능이다.(커서를 갖다대면 
    내용이 보임)


웹과 인터넷의 관계는 웹이 인터넷의 부분집합과 같다.

인터넷이 도시라면 웹은 그 도시의 한 건물이라고 볼 수 있다. 
1960년대 인터넷이 탄생하는데 그 배경은 군사적 목적에 있다. 
핵공격의 여파가 통신시스템 마비를 초래할 수 있다는 것을 알게된 미국이 
중앙집중이 아니라 분산통신시스템을 만들게 되는데 이게 인터넷의 시초이다. 

웹은 1990년대 스위스의 유럽입자물리연구소에서 탄생했다. 팀 버너스 리 라는 사람이 
연구소 내 넘쳐흐르던 정보들의 접근성을 용이하게 만들기 위해 제작했다. 그러다 연구소에 인터넷이 도입되면서
최초의 웹페이지인 http://info.cern.ch 가 탄생한다. 

수학은 이해하는것이 아니라 익숙해지는 것이다. - 존 폰 노이만 - 

CSS 는 중복된 태그를 한번에 수정할 수 있어 생산성을 비약적으로 높여준다. 
디자인과 관련된 코드는 죄다 <style> 태그에 전부 넣는다. 
style 태그는 선택자를 사용해서 디자인을 변경할 수 있다. 선택자가 지정한 모든 태그안의 내용을 변경함

속성은 태그안에서 직접 지정해서 선택자가 필요없ㄱ음 

    <style>
        a/*태그선택자*/ {
            color:black; /*선언*/
            text-decoration:none; /*웹페이지에 대한 모든 a 태그에 대해 모든 디자인을 제거*/
        }
        .saw/*클래스 선택자*/ {
            color:black; /*선언*/
            text-decoration:none; /*웹페이지에 대한 모든 a 태그에 대해 모든 디자인을 제거*/
        }
        </style>

        #active/*id 선택자*/ {
            color:black; /*선언*/
            text-decoration:none; /*웹페이지에 대한 모든 a 태그에 대해 모든 디자인을 제거*/
        }
CSS 에서 display 속성은 해당요소를 어떻게 보여줄지 결정한다. 
주로 4가지 속성값이 쓰이는데 태그마다 기본값이 다르다. 

none 요소를 보이지 않도록 설정 블럭도 안잡아 먹음 
block
inline
inline-block

CSS 파일을 만들고html 에서 링크를 거는 방법이 생김으로 써 생산성이 더욱 높아졌다. 
효율적 측면에서 캐싱이라는 기술이 생기면서 네트워크 트래픽도 덜 잡아먹을 수 있다. 
웹페이지 디자인이 비슷하면 CSS 파일을 캐시에 저장하여 중복을 제거한다. 

정보기술에 있어서 중복을 줄여서 재사용성을 높이고 가독성을 높이고 유지보수를 편리하게 만드는 것이 얼마나
중요한 것인지 알아야 한다. 

