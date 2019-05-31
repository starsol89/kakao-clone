# TAG NOT SUPPORTED IN HTML5

## HTML5의 New Semantic/Structural Elements

<article>
Ex)
  <article>
      <h1>Google Chrome</h1>
      <p>Google Chrome is a free, open-source web browser developed by Google, released in 2008.</p>
  </article>

이 태그는 독립적인 컨텐츠를 지정 합니다. 기사는 독자적으로 이해해야하며 나머지 사이트와 독립적으로 기사를 배포 할 수 있어야 합니다.
즉, 문서, 페이지, 애플리케이션, 또는 사이트 안에 독립적으로 구분되거나 재사용 가능한 영역을 구성 할 수 있습니다.
포럼의 글, 매거진/ 신문의 기사, 블로그 글 등이 여기에 포함됩니다.

<aside>
Ex)
    <p>영철이는 오늘 HTML5 태그를 정리하고 있다.<p>

    <aside>
        <p>보람이는 퇴근 이후에 쉬는 중이다.</p>
    </aside>

이 태그는 문서의 주요 컨텐츠에 별도로 이어진 컨텐츠가 있는 문서의 한 구획을 말한다. 주로 사이드바로 나타냅니다.

<bdi>
Ex) 예제와 내용이 있지만 영어를 해석해도 또 코드 결과를 봐도 이해하기 어렵다.. 좀 더 공부하면서 사용법을 알게 되면 다시 정리.

<details>
Ex)
    <details>
        <summary>details</summary>
        summary 요소를 사용하여 요약 또는 레이블을 제공 할 수 있습니다. 즉, 누르게 되면 이 글 내용이 그대로 들어남
    </details>

HTML 세부요소 (<details>)는 위젯이 "열린" 상태로 전환 될 때만 정보를 볼 수 있는 공개 위젯을 생성 합니다.

<dialog>
Ex)
    <table>
    <tr>
        <th>January <dialog open>This is an open dialog window 열려있는 대화 상자 창!!</dialog></th>
        <th>February</th>
    </tr>
    <tr>
        <td>31</td>
        <td>28</td>
    </tr>
    </table>

대화 상자 또는 창을 정의 합니다. 웹페이지에서 팝업 대화상자와 모달을 쉽게 만들 수 있게 해줍니다.
