# 경로 이동

```
@app.route('/')
def home():
  return 'home'
```
'/' 경로 즉 홈에서 'home'이라는 문구가 나옴

```
@app.route('/user/<name>')
def user(name):
  return name+"님 안녕하세요"
```
/user/사용자 지정 경로로 갈 경우
**님 안녕하세요 라는 문구가 나옴.
