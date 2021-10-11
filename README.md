# AppleScript

For Save AppleScript What I Make
</br>
</br>

---

## dev: Todo Mate Opener (URI Page Opener)

- 해당 스크립트는 Todo mate라는 사이트를 기본으로 설정되어있다.
- 내부 스크립트에 Todo 대신 특정 사이트를 입력하면 정상적으로 작동할 것이다.

</br>

> ### ver 0.1

- feat:

1. 현재 열려있는 Safari Tab 중에 Todo mate 사이트아 없다면 새로운 Safari Window를 만들고 Todo mate 페이지를 연다.
2. 만약 현재 열려있는 Window에서 Todo mate Tab 이 존재한다면 해당 Window의 Activate Tab을 Todo mate Tab으로 바꾼다.
3. 존재하지만 최소화된 (Dock에 최소화된 상태)로 되어있다면 해당 Window의 최소화 상태를 풀고 2번과 동일하게 진행한다.

</br>

> ### ver 0.2

- update:

1. 여러 창이 열려있을 때 해당 Todomate Window가 가장 앞으로 오도록 변경했다.

</br>

> ### ver 0.3

- update:

1. 해당 창을 현재 Desktop으로 이동시키려고 했지만, AppleScript의 한계로 어려울 것 같아 방법을 바꿨다.
2. 변경 방법은 항상 현재 열려있던 해당 URL 탭을 모두 지우고, 새로운 창에서 만드는 방법이다.
