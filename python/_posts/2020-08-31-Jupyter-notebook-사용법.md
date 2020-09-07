---
layout: post
title: Jupyter notebook 사용법
subtitle: 자주 사용하는 단축키 알아보기!
cover-img: /assets/img/jupyter-notebook-color.png
thumbnail-img: /assets/img/jupyter_notebook.png
tags: [Jupyter Notebook, 단축키]
---

## 1. Jupyter Notebook이란？

> Jupyter Notebook extends the console-based approach to interactive computing in a qualitatively new direction, providing a web-based application suitable for capturing the whole computation process: developing, documenting, and executing code, as well as communicating the results. ——[Jupyter Notebook](https://jupyter-notebook.readthedocs.io/en/stable/notebook.html)

간단하게 얘기하자면 Jupyter Notebook는 웹 페이지 형식으로 접근 가능하다. 브라우저를 통해 웹 페이지에서 노트북 문서를 편집하고 진행할 수 있으며 셀 아래 실행결과 표시되어 있어서 사용자가 그때그때 결과를 확인하면서 디버그 가능하다. 또한 코딩 과정중에서 코드에 대한 설명문은 같은 페이지에서 셀 모드만 바꾸면 바로 작성할 수 있어서 매우 편리하다.

## 2. Jupyter Notebook의 특징

- 코딩할 때 문법 하이라이트, 들어쓰기, tab자동완성 기능 가지고 있음

- 브라우저를 통해 코드를 실행 가능하며 셀 밑에 실행 결과를 바로 확인 가능

- 다양한 파일 형식으로 연산결과를 출력가능 (예: HTML, LaTeX, PNG, SVG등)

- 코드에 대한 설명문을 작성할 때 Markdown 기능 활용가능

- LaTeX를 이용해 수식 작성 가능

## 3. Jupyter Notebook 콘솔 모드
Jupyter Notebook은 아무 때나 `Esc` 키를 누르면 명령모드(command mode)로 들어가고 `Enter` 키나 셀을 클릭하면 편집모드(Edit mode)로 들어가게 됩니다.
- 명령모드
&nbsp;
![command-mode](https://i.pinimg.com/originals/55/9d/ea/559deabb0a77b9b0285d42d72a74a5f7.png){: .mx-auto.d-block :}
&nbsp;
- 입력모드
&nbsp;
![edit-mode](https://i.pinimg.com/originals/03/29/cc/0329cc1fa4ccafdb0323311d4b5ed580.png){: .mx-auto.d-block :}


## 4. 자주 사용하는 단축키 정리

| 단축키 | 동작 |
| :------ |:--- |
| `Cmd`(`Ctrl`) + `Enter` | 현재 셀을 수행 | 
| `Shift` + `Enter` | 현재 셀을 수행하고 아래 셀을 선택 (셀이 없을 경우 추가) | 
| `Opt`(`Alt`) + `Enter` | 현재 셀을 수행하고 아래에 새로운 셀을 추가 |    
| `Cmd`(`Ctrl`) + `S` | Jupyter notebook 저장 |
| `Enter` | 명령 모드에서 입력 모드로 전환 |
| `Esc` | 입력 모드에서 명령 모드로 전환 |
| `A` | 명령모드 상태 셀에서 위로 셀을 생성 |
| `B` | 명령모드 상태 셀에서 아래로 셀을 생성|
| `M` | 명령모드 상태 셀에서 셀 타입을 마크다운으로 전환 |
| `Y` | 명령모드 상태 셀에서 셀 타입을 코드로 전환 |
| `D` `D`|명령모드 상태 셀에서 해당 셀 삭제|
| `Z` | 명령모드 상태 셀에서 전 상태로 되돌린다|
| `Cmd`(`Ctrl`) + `/` | 셀 편집 영역에서 선택된 코드를 주석 / 비주석으로 |
| `↑` `↓` 방향키 | 명령 모드에서 셀 간의 이동 |
| `tab`| 코드 자동와성|
| `Shift` + `tab`| 함수에 대한 설명 조회|

----
# summary
- mode : 명령모드, 편집모드
- style : markdown, code
- 단축키
    - 실행 : shift + enter
    - 자동완성 : tab
    - docstring 보기 : Shift + tab
    - 주석설정 : Cmd(Ctrl) + /
    - 셀 생성 : (명령모드) A(위에), B(아래)
    
----