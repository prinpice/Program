# Program install & setting

## jupyter notebook

### 1. 설치

* 기본 설치

  ```git
  git bash
  
  $ pip install jupyter
  ```

* 추가 확장 프로그램 설치

  * pip를 통한 패키지 설치

    ```git
    git bash
    
    $ pip install jupyter_contrib_nbextensions
    ```

  * JS, CSS 파일 설치

    ```git
    git bash
    
    $ jupyter contrib nbextension install --user
    ```

  * 확장 프로그램 목록 확인

    <http://localhost:8888/nbextensions>

    * 사용중인 확장 프로그램(필수) : Tanle of Contents



* 열기

  ```git
  git bash
  
  $ jupyter notebook
  ```

  