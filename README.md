1. `name: Build and Push Docker imag` : 이 GitHub 액션의 이름을 정의한다. 
2. `on: [push]` : 코드가 푸시될 때 이 GitHub 액션을 트리거한다.
3. `jobs` 섹션 아래에 `check-bats-version`이라는 작업이 정의 : 이 작업은 GitHub Action 섹션에서 모니터링된다.
4. `runs-on: ubuntu-latest` : 이 작업이 우분투 최신 버전에서 실행됨을 나타낸다.
6. `run: echo "${{ github.actor }}"` : GitHub 액터의 이름을 출력한다.
