## 무엇을 구현했나
<!-- 바꾼 함수/구조체와 동작을 짧게. 예: thread_set_priority 에서 우선순위가 낮아지면 바로 양보 -->

## 왜 이렇게 했나
<!-- 설계 이유, 고민했던 다른 방법 -->

## 테스트 결과 (`make check`)
<!-- 컨테이너에서 cd pintos/threads && make && cd build && make check 실행 후 마지막 줄 붙여넣기 -->
- 이번 PR 전: PASS ? / ?
- 이번 PR 후: PASS ? / ?
- 새로 PASS 된 테스트:
- 새로 FAIL 된 테스트 (원래 되던 게 깨졌다면 꼭 적기):

## 체크리스트
- [ ] 합칠 곳(base)이 맞다 — `feature-*` → `dev`, `dev` → `main`
- [ ] `printf` 등 디버그 출력 제거 (남아 있으면 공식 테스트 출력 비교가 FAIL 남)
- [ ] 같은 함수를 고친 팀원과 미리 공유함
