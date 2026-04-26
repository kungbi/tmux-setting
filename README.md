# tmux-setting

개인 tmux 설정 파일 모음.

## 설정 내용

- passthrough 허용 (`allow-passthrough on`)
- `TERM`, `TERM_PROGRAM` 환경변수 전달
- 패인 크기 조절 단축키: `+` (위로 5), `-` (아래로 5)

## 적용 방법

```bash
cp .tmux.conf ~/.tmux.conf
tmux source-file ~/.tmux.conf
```
