[DP] RIGHT TO LEFT DEPENDENCY PARSER
======================

소속 : 서강대학교 자연어처리 연구실. 
작성자 : 정영훈<hoon2j@gmail.com>  
개발자  
	한장훈 <hanjh04@naver.com>  
	박영준 <yeongjoon1227@gmail.com>  
	정영훈 <hoon2j@gmail.com>  
	이인권 <md98765@naver.com>  
관리자 : 김주애 <jju75474@gmail.com>  
본 프로그램은 서강대학교 자연어처리 연구실의 소중한 자산입니다.  
본 프로그램을 이용한 모든 결과물은 본 프로그램의 주소가 참조되어야 합니다.  
참조 사이트 : <https://github.com/sgnlplabeling/nlp_labeling>  

# References
## 참고 코드
><https://github.com/XuezheMax/NeuroNLP2>
><https://github.com/danifg/Left2Right-Pointer-Parser>

## 참고 논문
>Left-to-Right Dependency Parsing with Pointer Networks - Daniel Fernández-González et al
>Stack-Pointer Networks for Dependency Parsing - Xuezhe Ma et al

## 개발 환경
>python == 3.6.9
>pytorch == 1.1.0
>cuda == 10.0

# 실행 방법

## Train
1. RIGHT-TO-LEFT Dependency Parser
./examples/run_RLParser.sh

2. Bi-Affine Dependency Parser
./examples/run_graphParser.sh

## Test
./examples/run_inference.sh

※ parameter 설정은 각각의 shell file의 option을 통해서 선택/수정 가능합니다. 
※ 현재 train, test 데이터는 예시 파일로, 일부만 업로드 되어있습니다. 
전체 데이터가 필요할 경우에는 작성자 및 관리자의 이메일로 요청바랍니다. 