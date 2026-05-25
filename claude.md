# Project Instruction

목표: Google Stitch 디자인을 Shopify Dawn 테마 구조에 맞게 Liquid로 변환.

환경: Shopify Dawn Theme, Shopify AI Toolkit 활용.

규칙:

Stitch의 HTML/CSS는 구조 참조용으로만 사용한다.

코드를 생성할 때 Dawn 테마의 표준 레이아웃(page-width, grid, section)을 우선한다.

모든 콘텐츠는 Shopify 변수(liquid object)를 사용하여 동적으로 처리한다.

수정이 완료되면 항상 Shopify AI Toolkit의 validate 명령으로 규격 확인을 한다.2

## 주의
- `shopify theme push`는 반드시 
  내 확인 후 실행할 것