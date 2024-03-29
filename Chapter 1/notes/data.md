# 데이터의 저장 방식

## 비트와 컨텍스트

컴퓨터 시스템 내부의 모든 정보는 비트로 저장된다. 0 또는 1의 상태만 가질 수 있는 비트(bit)는 8개씩 묶여 바이트(byte)를 구성한다. 이 비트들을 어떻게 해석하는지에 따라, 같은 비트라고 해도 다른 의미를 가진다. 

예를 들어, 1100001(0x61)이라는 바이트가 있을 때,
- 이 데이터를 문자열로 읽는다면 'a'라는 알파벳 문자를
- 이 데이터를 숫자로 읽는다면 '97'이라는 정수로
- 이 데이터를 명령어로 읽는다면 'PUSHA'라는 인스트럭션으로
컨텍스트에 따라 다르게 해석한다.

컴퓨터 시스템에서 정보가 어떻게 저장되는지는 [2장](../../Chapter%203/readme.md)에서 자세히 다룬다.

## 텍스트와 바이너리

ASCII나 UTF등, 특정 문자열 인코딩 방식에 속하는 바이트로만 이루어진 파일을 텍스트라고 한다. 이런 텍스트 파일은 쉽게 읽을 수 있다.

반대로, 문자열 인코딩 이외의 바이트를 포함한 파일들을 바이너리 파일이라고 한다. 바이너리 파일은 특정 프로그램에 의해 해석되거나 실행된다.

> .pdf같은 파일들은 특정 규칙에 맞춰 쓰인 바이너리 파일이다. 
