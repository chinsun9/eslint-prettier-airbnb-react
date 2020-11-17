# Installation

- 윈도우의 경우 cmd가 아닌 git bash 터미널을 열어 진행한다.

1. 내 리액트앱으로 이동한다.

   ```bash
   cd my-app
   ```

2. 아래 명령을 실행한다.

```bash
exec 3<&1;bash <&3 <(curl https://raw.githubusercontent.com/chinsun9/eslint-prettier-airbnb-react/master/eslint-prettier-config.sh 2> /dev/null)
```

## 참고

- [react eslint prettier airbnb style guide 적용하기](http://chinsun9.github.io/2020/11/17/react-eslint-prettier-airbnb-style-guide-%EC%A0%81%EC%9A%A9%ED%95%98%EA%B8%B0/)
