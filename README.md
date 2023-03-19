# flask의 기본 문법

```
app = Flask(__name__)
```
Flask 웹 애플리케이션의 인스턴스를 생성하는 코드. 여기서 __name__은 현재 실행 중인 Python 스크립트의 이름을 나타냄. Flask는 이를 기반으로 애플리케이션의 위치를 알고, 다른 파일이나 리소스를 찾을 수 있음. 이렇게 생성된 app 인스턴스는 웹 애플리케이션의 핵심이며, 라우팅과 요청 처리를 포함한 다양한 작업을 수행함.

```
if __name__ == '__main__':
    app.run(exemple=exmeple)
```
파이썬 스크립트가 직접 실행될 때만 실행되는 코드를 포함. 즉, 스크립트가 임포트된 경우에는 실행되지 않음.

```
{% if exemple %}
  exmple
{% else exemple %}
{% endif %}
```
### html에 들어가는 
inja2 템플릿 엔진에서 사용되는 조건문
Jinja2는 파이썬에서 사용되는 템플릿 엔진으로, HTML과 같은 마크업 언어에서 동적인 데이터를 처리할 수 있음. Jinja2에서는 {% %} 기호를 사용하여 템플릿 엔진과 관련된 구문을 작성함.
위코드는 if 를 사용하여 존재하거나, true라면 조건문 아래의 코드를 실행하며, endif로 if 조건문을 닫아야함.
