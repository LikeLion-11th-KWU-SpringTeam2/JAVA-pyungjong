# STUDY 02
* java

## 변수

데이터가 저장되는 공간

* 변수명은 소문자로 시작, 변수 앞 숫자 불가

## 기본형

### 정수형

#### **byte**
> 
* 8비트
* 네트워크 시스템
* 변수는 byte

#### **short**
> 
* 16비트
* 변수는 short

#### **int**
> 
* 32비트
* 정수형
* 변수는 int

#### **long**
> 
* 64비트
* 큰 숫자를 나타낼 때
* 변수는 long

### 실수형

#### **float**
> 
* 32비트
* 7자리
* 끝에 f를 붙임

#### **double**
> 
* 64비트
* 15자리

### 문자형

#### char
> 
* 16비트
* 작은 따옴표 사용
* 유니코드는 16진수

### 논리형

#### boolean
> 
* 1바이트
* true or false


### 참조형

* 참조형 값 == 힘 메모리 영역
* 변수 값   == 힙 메모리 영역의 주소값


## 상수

constants, final variables

* `final` 사용
* 재할당이 불가
* 전체를 대문자
* `_`로 구분

## 형변환

byte < short < int < long <<< float < double


### 문자열 병합

#### `+` 연산자


### 문자열 슬라이스

#### `index0f()`


### 문자열 대소문자 변환

* `.toUpperCase()`
* `.toLowerCase()`


### 공백제거

#### 양쪽 끝 공백
    `.trim()`

#### 문자열 중간 공백
    `.replace(targer:" ", replacement:"";)`