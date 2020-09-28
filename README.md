# ucpc2020-solutions-theme

UCPC 2020 솔루션 및 beamer 테마

Based on:
- [Execushares](https://github.com/hamaluik/Beamer-Theme-Execushares)
- [Sogang ICPC Team](https://acm.soagng.ac.kr) 강의 자료

## 테마 사용 예

- [UCPC 2020](main.pdf)
- [SUAPC 2020](https://upload.acmicpc.net/789ee426-cf86-40fa-aa64-733c50e96539/)
- [SNUPC 2020](https://snups.snucse.org/snupc2020/solution.pdf)

## 참고

- **X<sub>E</sub>L<sub>A</sub>T<sub>E</sub>X을 사용해 컴파일해야 합니다.**
- 원본 솔루션과 약간의 차이가 있습니다.
  - 원본 솔루션의 고정폭 폰트는 [PF Din Mono](https://www.myfonts.com/fonts/parachute/pf-din-mono/)라는 유료 폰트로 개인적으로 라이센스를 소유하고 있기 때문에, [DM Mono](https://fonts.google.com/specimen/DM+Mono)로 교체했습니다.
  - 기타 포매팅이 약간씩 다른 부분이 존재합니다.
- 커스텀 커맨드가 있습니다.
  - `\difficulty{n}`: [solved.ac](https://solved.ac) 난이도 아이콘, *n* = 0..30. 이 커맨드를 사용하려면 `/images/[0-30].svg.png`가 존재해야 합니다.
  - `\complexity{math}`: 복잡도 표기 (=`\mathcal{O}\left(math\right)`)
  - `\sectiontitle` 및 `\sectionmeta`: 슬라이드 참조
