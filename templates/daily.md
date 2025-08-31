<% tp.file.rename("Daily Tasks "+ tp.date.now("YYYY-MM-DD")) %>
<% tp.file.move("todo/Daily Tasks "+ tp.date.now("YYYY-MM-DD")) %>
<%*
const today = tp.date.now("YYYY-MM-DD");
const dow   = tp.date.now("dddd"); // Monday, Tuesday...

// 파일을 지정 경로/이름으로 이동(=자동 파일명/폴더 설정)
await tp.file.move(`todo/Daily Tasks ${today}`);

// 월요일(안식일)은 체크리스트 생략하고 안내만 남기기
if (dow === "Monday") {
  tR += `# Daily Tasks - ${today}\n\n> 🛑 안식일입니다. 정리/휴식만 하고 체크리스트는 생성하지 않았습니다.\n\n## Notes\n- 오늘 느낀 점:\n\n## Tomorrow\n- 계획:\n`;
  return tR;
}
%>
## Warm-up
- [ ] Python 복습 📅 <% tp.date.now("YYYY-MM-DD") %>
- [ ] Kaggle 계정 📅 <% tp.date.now("YYYY-MM-DD") %>
- [ ] Kaggle 환경 세팅 📅 <% tp.date.now("YYYY-MM-DD") %>
- [ ] GitHub Repo 📅 <% tp.date.now("YYYY-MM-DD") %>
- [ ] README 📅 <% tp.date.now("YYYY-MM-DD") %>

## Python 복습
- [ ] 조건문 if/elif/else 실습 📅 <% tp.date.now("YYYY-MM-DD") %>
- [ ] 반복문 for/while 연습 📅 <% tp.date.now("YYYY-MM-DD") %>
- [ ] 리스트 컴프리헨션 예제 📅 <% tp.date.now("YYYY-MM-DD") %>

## Kaggle EDA (House Prices)
- [ ] `train.info()` 실행 📅 <% tp.date.now("YYYY-MM-DD") %>
- [ ] `train.describe()` 실행 📅 <% tp.date.now("YYYY-MM-DD") %>
- [ ] 결측치 확인 (`.isnull().sum()`) 📅 <% tp.date.now("YYYY-MM-DD") %>

## GitHub & README
- [ ] Repo pull 확인 📅 <% tp.date.now("YYYY-MM-DD") %>
- [ ] 커밋 & 푸시 확인 📅 <% tp.date.now("YYYY-MM-DD") %>
- [ ] README.md 업데이트 📅 <% tp.date.now("YYYY-MM-DD") %>

---

## Progress (자동 집계)
### 오늘 해야 할 일
```tasks
not done
due today
path includes todo
```

## Notes
- 오늘 배운 점:

## Tomorrow
- 계획: