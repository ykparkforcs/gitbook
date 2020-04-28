# 컴포넌트 사용하기: 날짜

![](https://www.eformsign.com/kr/support/wp-content/uploads/sites/5/2020/02/sample-of-using-datetime-component.gif)날짜 컴포넌트 사용 예시

## 언제 사용하나요?

![](https://www.eformsign.com/kr/support/wp-content/uploads/sites/5/2020/02/form-builder-components_datetime.png)

날짜를 입력해야 할 때 사용합니다. 입력란을 클릭하면 날짜 선택창이 나타나며 원하는 날짜를 선택할 수 있습니다.

## 속성 알아보기

![](https://www.eformsign.com/kr/support/wp-content/uploads/sites/5/2020/02/datetime-component-properties_02.png)

### ① ID

날짜 컴포넌트의 ID를 입력합니다.  
\(예를 들어, 휴가 시작일을 선택하는 컴포넌트의 ID는 ‘휴가 시작일’로 합니다.\)

### ② 표시형식

날짜가 표시되는 형식을 지정합니다.

* yyyy: 년도
* MM: 월\(반드시 대문자로 표기\)
* dd: 일

‘2020년 2월 5일’처럼 나타나게 하려면, 표시형식에 ‘yyyy년 MM월 dd일’로 입력합니다.

### ③ 입력 가능 최소/최대 날짜

날짜 선택 시 선택할 수 있는 최소, 최대 날짜를 지정하여 입력 가능한 날짜의 범위를 설정합니다.

### ④ 빈 값일 때 오늘 날짜 표시

문서를 열었을 때 자동으로 오늘 날짜가 입력되도록 설정합니다. 날짜 컴포넌트 추가 시 기본으로 체크되어 있습니다. 오늘 날짜가 입력된 입력란을 다시 클릭하면 다른 날짜를 선택할 수 있습니다.

### ⑤ 입력 데이터 초기화 가능

입력 데이터 초기화 가능을 체크하면 선택한 날짜를 삭제할 수 있습니다.

날짜 컴포넌트는 한 번 날짜를 선택하면 다른 날짜로 변경할 수는 있으나 날짜 선택을 취소할 수는 없습니다. 그러나 입력 데이터 초기화 가능 속성을 체크하면 아무것도 선택되지 않은 상태로 변경할 수 있습니다. 단, 아무것도 선택되지 않은 상태일 때 빈 값일 때 오늘 날짜 표시 속성이 체크된 경우 오늘 날짜로 선택됩니다.

* PC 환경: 컴포넌트를 오른쪽 마우스로 클릭하면 나타나는 팝업 메뉴에서 ‘입력 데이터 초기화’를 선택합니다.
* 모바일 환경: 휴지통 아이콘을 클릭합니다.

### ⑥ 툴팁 텍스트

입력란에 마우스를 갖다 대면 툴팁 텍스트에 입력한 설명이 나타납니다.
