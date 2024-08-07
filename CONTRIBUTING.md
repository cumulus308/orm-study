### 문제 추가로 Contribution 하는 방법

크게 신경써야 할 부분은 없고, 동시에 같은 문제 작업을 하지 않기 위해 아래와 같은 방식으로 프로세스를 진행합니다.
문제는 orm_study/quiz/python/ 경로에 txt 파일로 되어있습니다.

- 객관식 문제 파일명: multiple_choice.txt
- 주관식 문제 파일명: subjective.txt

0. 본인의 계정으로 `fork`를 먼저 실행합니다.
1. Github에 Issue를 남깁니다.
   1. 제목
      - 파이썬 문제추가 - 챕터명, 문제타입
      - `문제추가` 가 제목에 반드시 있어야 합니다.
   2. 내용
      - 내용에 대해서 정해진 템플릿은 없습니다.
      - 몇문제 추가할 지 내용에 적어주시고 하고싶은 말 적으시면 됩니다.
   3. Submit New Issue
2. fork된 Repository에 문제를 추가합니다.

   - 기존에 있는 챕터에 문제를 추가할 경우 해당 챕터의 multiple_choice.txt 또는 subjective.txt에 문제를 추가합니다.
   - 객관식 문제 추가 포맷
     1. 문제를 쓸 때는 `.`으로 시작합니다.
     2. 객관식 문제와 보기는 한 줄 띄워줍니다.
     3. 정답은 `답.`으로 시작합니다.
   - 예시 참고

     ```
     .다음 코드에서 변수 y의 타입은 무엇입니까?

     y = "Hello, World!"

     1. int
     2. str
     3. list
     4. bool
     답.2
     ```

   - **새로운 챕터를 추가한 경우**
     - `orm_study/quiz/constants.py` 안에 CHAPTER와 CHAPTER_CHOICE에 새 챕터를 추가해주세요.
     - 추가하지 않으면 테스트에 실패합니다.

3. Pull Request를 생성합니다.

### 이미지로 확인

- 이슈 작성
  다음과 같이 이슈를 작성하면 됩니다.
  <img width="977" alt="SCR-20240705-pscx" src="https://github.com/Jungminchae/orm-study/assets/60789129/d96b0e46-e213-42ad-b96e-6d342d9435da">
- `fork`한 레포에 문제추가
  **이미지에서 경로도 잘 확인해주세요**
  <div align="center">
    <img width="559" alt="SCR-20240705-puqz" src="https://github.com/Jungminchae/orm-study/assets/60789129/88de4317-7791-4389-a637-bd3d5e758952">
  </div>
- `pull request`하기
  PR적을 때 #하고 issue번호를 같이 적어주세요
  <div align="center">
    <img width="465" alt="SCR-20240705-pvat" src="https://github.com/Jungminchae/orm-study/assets/60789129/14c0810f-5897-4c94-b033-85c077ca1313">
    <img width="337" alt="SCR-20240705-pwzo" src="https://github.com/Jungminchae/orm-study/assets/60789129/ba237894-8334-42cd-a3ee-6ca8fdb3e340">
  </div>

### 기능 추가같이 코드로 Contribution 하는 방법

기능 추가, 버그 수정 등 코드와 관련해서도 기여하실 수 있습니다.

- Issue에 어떤 작업을 필요한지 혹은 하실 것인지 자유롭게 남겨주시고 작업을 진행해주시면 됩니다.
- 작업이 완료된 후에는 PR을 남겨주시면 됩니다. (문제로 기여하기처럼 fork를 먼저 실행해주세요)
- 새로운 기능을 추가했을 경우 `Test`코드도 함께 작성해주세요. (어렵다면 코멘트 남겨주세요)
- `TODO.md`에 몇가지 정리되어 있습니다. 참고하셔서 기여해주셔도 됩니다.
