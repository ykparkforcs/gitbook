# 컴포넌트 사용하기: 사용일

![](https://www.eformsign.com/kr/support/wp-content/uploads/sites/5/2020/02/sample-of-using-date-component.gif)사용일 컴포넌트 사용 예시 \(서명일 자동 입력\)

## 언제 사용하나요?

![](https://www.eformsign.com/kr/support/wp-content/uploads/sites/5/2020/02/form-builder-components_date.png)

문서를 작성 또는 수정한 날짜가 문서에 자동으로 입력되게 할 때 사용합니다.

설정에 따라 문서를 만든 날짜, 문서에 접근한 날짜, 또는 특정 컴포넌트를 입력한 날짜가 자동으로 입력됩니다.

## 속성 설정하기

![](https://www.eformsign.com/kr/support/wp-content/uploads/sites/5/2020/02/date-component-properties_.png)

### ① ID

사용일 컴포넌트의 ID를 입력합니다.  
\(예를 들어, 문서에 서명한 날짜를 표시하는 컴포넌트의 ID는 ‘서명일’로 합니다.\)

### ② 표시형식

연월일을 표기할 형식을 설정합니다.

* yyyy: ‘연도’를 표시합니다. \(yyyy년 = 2020년\)
* MM: ‘월’을 표시합니다. 반드시 대문자로 표기해야 합니다. \(MM월 = 8월\)
* dd: ‘일’을 표시합니다. \(dd일 = 10일\)

### ③ 사용일 표시 유형

* 만든 날짜: 문서를 최초 작성한 날짜를 표시합니다.
* 액세스한 날짜: 문서를 수정하거나 열람한 가장 최근의 날짜를 표시합니다.
* 입력 값을 수정한 날짜: 특정 컴포넌트에 내용을 입력한 날짜를 표시합니다.

  ![](https://www.eformsign.com/kr/support/wp-content/uploads/sites/5/2020/02/date-component-connecting-other-component.png)

  이 유형을 선택하는 경우 하단에 입력 컴포넌트 ID 입력란이 나타납니다. 여기에 연결할 컴포넌트 ID를 입력합니다.

  예\) 계약자 서명일이 자동으로 표시되게 할 경우

  1. 계약서 서명란 서명 컴포넌트의 ID를 ‘계약자 서명’으로 지정합니다.
  2. 서명일이 표시될 사용일 컴포넌트를 생성합니다.
  3. 사용일 컴포넌트의 사용일 표시 유형 속성을 ‘입력 값을 수정한 날짜’로 선택합니다.
  4. 입력 컴포넌트 ID 입력란에 ‘계약자 서명’을 입력합니다. \(자세한 사용 방법은 [전자 계약서에 서명일 자동으로 입력하기](https://www.eformsign.com/kr/support/manual/autofill-signed-date/)를 참고해 주시기 바랍니다.\)

