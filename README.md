# skills

## Go 리팩토링

기존 Go 코드의 동작을 유지하면서 읽거나 변경하기 어려운 부분을 정리하는 Codex 스킬이다. 일곱 관점을 함께 적용하거나 필요한 관점만 골라 쓸 수 있다. 관점별 질문과 변경 기준은 [go-refactor/SKILL.md](skills/go-refactor/SKILL.md)에 있다.

### 사용 예

```text
$go-refactor ./internal/catalog를 일곱 관점으로 리팩토링하고 기존 응답이 유지되는지 검증해줘.
$go-refactor 현재 diff를 Tidy First?와 Clean Architecture 관점에서만 리뷰해줘.
```

### 설치

이 저장소를 클론하고 개인 스킬 디렉터리에 연결한 뒤 새 Codex 대화에서 호출한다.

```sh
git clone https://github.com/coding-convention/skills.git
mkdir -p ~/.agents/skills
ln -s "$(pwd)/skills/skills/go-refactor" ~/.agents/skills/go-refactor
```
