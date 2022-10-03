# paymentCustomize

1. 설정 해놓은 Payment methods 가 없을때 null값 대신 커스텀 버튼 삽입 하려고 코드 분석해봤지만 cannot find.

2. 기존 커스텀버튼은 로딩박스 밖에서 돌았으나 , 이번 수정건은 로딩이 끝나면 버튼이 show 되게끔 수정.

3. checkoutID props 는 Checkout.tsx 에서 -> Payment.tsx로 props 전달후 checkout아이디 값 넘겨 받아옴. props(type:stirng, customizeCheckoutId 입니다.)

4. Checkout.tsx , Payment.tsx 덮어쓰기 or replace 하시면 될것같습니다.
