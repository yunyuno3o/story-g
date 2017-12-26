# 맥북 cheat sheet

## 단축키

### 파인더에서 숨김폴더 보이기/감추기 `Cmd + Shift + .`

예전에 이 기능을 동작시키기 위해 아래 명령을 사용해 서비스를 만들어 사용했었다.

Finder에서 hidden folder & file 보기 : defaults write com.apple.finder AppleShowAllFiles YES

```
Onlydel-MacBook-Pro:apache2 gotodo$ defaults write com.apple.finder AppleShowAllFiles YES
Onlydel-MacBook-Pro:apache2 gotodo$ killall Finder
Onlydel-MacBook-Pro:apache2 gotodo$ defaults write com.apple.finder AppleShowAllFiles NO
Onlydel-MacBook-Pro:apache2 gotodo$ killall Finder
```
