# ucpc2020-solutions-theme

UCPC 2020 솔루션 및 beamer 테마

Based on:
- [Execushares](https://github.com/hamaluik/Beamer-Theme-Execushares)
- [Sogang ICPC Team](https://acm.sogang.ac.kr) 강의 자료

풀이의 저작권은 각 문제 작성자에게 있습니다.

## 테마 사용 예

- [UCPC 2020](main.pdf), [2021](https://2021.ucpc.me/assets/ucpc21-finals-solutions.pdf)
- [SUAPC 2020](https://upload.acmicpc.net/789ee426-cf86-40fa-aa64-733c50e96539/) (신촌 동아리 연합)

- [SNUPC 2020](https://snups.snucse.org/snupc2020/solution.pdf), [2021](https://snups.snucse.org/snupc2021/solution.pdf) (서울대학교)
- [SPC 2020](https://acm.sogang.ac.kr/spc/contest/2020/solutions.pdf), [2021](https://acm.sogang.ac.kr/spc/contest/2021/solutions.pdf) (서강대학교)
- [홍익대학교 2021](https://upload.acmicpc.net/2060837f-4598-4a67-909b-e3a75dba84c2/)

- [나는코더다 송년대회 2021](https://upload.acmicpc.net/8294438f-1337-4d1d-9105-4c8d0f4f45fb/) (경기과학고)
- [천하제일 코딩대회 2021](https://github.com/justiceHui/Sunrin-Contest/tree/main/Sunrin-OI-2021) (선린인터넷고)
- [Good Bye, BOJ 2021!](https://upload.acmicpc.net/d585ae16-b11e-4535-8974-ec9093885f9a/)
- [Semi-Game Cup 2021](https://upload.acmicpc.net/c6c814cb-c079-40e1-b2b1-6d21e99b3e9a/)

## 참고

- **X<sub>E</sub>L<sub>A</sub>T<sub>E</sub>X을 사용해 컴파일해야 합니다.**
- 원본 솔루션과 약간의 차이가 있습니다.
  - 원본 솔루션의 고정폭 폰트는 [PF Din Mono](https://www.myfonts.com/fonts/parachute/pf-din-mono/)라는 유료 폰트로 개인적으로 라이센스를 소유하고 있기 때문에, [DM Mono](https://fonts.google.com/specimen/DM+Mono)로 교체했습니다.
  - 기타 포매팅이 약간씩 다른 부분이 존재합니다.
- 커스텀 커맨드가 있습니다.
  - `\difficulty{n}`: [solved.ac](https://solved.ac) 난이도 아이콘, *n* = 0..30. 이 커맨드를 사용하려면 `/images/[0-30].svg.png`가 존재해야 합니다.
  - `\complexity{math}`: 복잡도 표기 (=`\mathcal{O}\left(math\right)`)
  - `\sectiontitle` 및 `\sectionmeta`: 슬라이드 참조
