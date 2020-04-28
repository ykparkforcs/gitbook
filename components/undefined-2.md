# 컴포넌트 사용하기: 선택

![](https://www.eformsign.com/kr/support/wp-content/uploads/sites/5/2020/02/--------------------.gif)선택 컴포넌트 사용 예시

## 언제 사용하나요?

![](https://www.eformsign.com/kr/support/wp-content/uploads/sites/5/2020/02/form-builder-components.png)

선택 컴포넌트는 여러 항목 중 어떤 항목을 선택했는지 확인해야 할 때 사용합니다. 선택 컴포넌트의 선택값은 데이터 다운로드 시 여러 항목 중 선택한 항목명이 나타납니다.

예\) 위 예시에서 11~20세 선택 시, 데이터는 “11~20세”로 저장됩니다.

\* ‘체크’와 ‘선택’의 차이는 무엇인가요?  
[체크 컴포넌트](undefined-1.md)는 해당 항목의 체크 여부를 확인할 때, 선택 컴포넌트는 선택한 항목이 무엇인지 알아야 할 때 사용합니다.  
\[[체크 컴포넌트 사용법 보기](https://www.eformsign.com/kr/support/manual/check/)\]

**\[사용팁\] 컴포넌트 안에 항목 내용을 입력하기**  
워드, 파워포인트에서는 선택 컴포넌트가 직사각형 도형처럼 나타납니다. 항목의 내용을 컴포넌트 도형 **안에** 입력해 주세요.  
\(이미 입력된 텍스트 위에 컴포넌트를 그리면 선택된 항목의 내용이 함께 저장되지 않습니다.\)

## 속성 알아보기

![](https://www.eformsign.com/kr/support/wp-content/uploads/sites/5/2020/02/Radio-component-properties.png)

### ① ID

선택 컴포넌트의 선택 항목에는 선택 그룹마다 모두 같은 ID를 부여해야 합니다. 예를 들어, 1번 문제에 대해 1, 2, 3, 4, 5의 보기가 있는 경우 1, 2, 3, 4, 5 항목에 같은 ID ‘1번’을 부여합니다. 2번 문제의 1, 2, 3, 4, 5 보기에는 ‘2번’ ID를 부여합니다.![](https://www.eformsign.com/kr/support/wp-content/uploads/sites/5/2020/02/radio-items-should-have-same-ID.png) 예\) 위 예시 화면의 모든 선택 항목의 ID는 ‘나이 선택’으로 지정합니다.

### ② 선택 스타일

선택 컴포넌트는 속성에서 스타일을 지정할 수 있습니다. 빨간 동그라미가 나타나는 ‘원’이 기본으로 설정되어 있으며 이외에 체크박스, 라디오 버튼 표시를 선택할 수 있습니다.![](https://www.eformsign.com/kr/support/wp-content/uploads/sites/5/2020/01/check-component-style-settings.png) 왼쪽부터 체크 / 라디오 / 원 선택 시 다른 표시

### ③ 다중 선택 가능

다중 선택 가능을 체크하면 1개 이상의 항목을 선택할 수 있습니다. 1개 이상의 항목을 선택한 경우 데이터 저장 시 선택된 여러 개의 항목이 콤마\(,\)로 구분되어 저장됩니다.

### ④ 선택 안 함 가능

선택 안 함 가능을 체크하면 선택한 항목을 다시 클릭해 선택 해제를 할 수 있습니다.

### ⑤ 툴팁 텍스트

해당 입력란에 마우스를 갖다 대면 툴팁 텍스트에 입력한 설명이 나타납니다.

