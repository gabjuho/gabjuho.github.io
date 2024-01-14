---
title: "첫 포스트 테스트"
excerpt: "마크다운으로 첫번째 Github blog 포스트를 게시하였습니다!"

categories:
    - Blog
tags:
    - [Blog, jekyll, MarkDown]

toc: true
toc_sticky: true

date: 2024-01-14
last_modified_at: 2024-01-14
---
마크다운도 익힐 겸 여러가지 시도를 해보고 블로그 포스팅 테스트를 마치려고 한다.

***

## 제목 (#제목)

# 제목1
## 제목2
### 제목3
#### 제목4
##### 제목5
###### 제목6

'#'은 6개까지 지원한다.

***

## 인용 (>인용)

>인용구
>>인용구2
>>>인용구3

***

## 리스트 (1. 요소 or * 요소)
1. 요소1
2. 요소2
3. 요소3

* 요소1
    * 요소2
        * 요소3

(탭으로 서브 요소 사용 가능)

***

## 코드 블럭 (한 줄 띄고 탭)

코드 블럭

    #include<iostream>
    using namespace std;
    int main()
    {
        cout<<"Hello World"<<endl;
    }

특정 언어 Snytax 강조

```c++
//사용법: ```c++ 코드```
#include<iostream>
using namespace std;
int main()
{
    cout<<"Hello World"<<endl;
}
```

***

## 수평선

    ***

***

## 링크

Link: [Google][googlelink]

[googlelink]: https://google.com "Go google"

    [링크 이름][링크 아이디]
    [링크 아이디]: URL "서브 타이틀 (Optional)"

혹은

    [link](URL)

로 외부 링크를 만들 수도 있다.

***

## 강조

    *강조1*
    **강조2**
    ~~강조3~~

*강조1*

**강조2**

~~강조3~~

***

## 이미지
이미지를 복사 후 Issue에 붙인 후 그 텍스트를 다시 복사하여 마크다운 파일에 붙이면 됨
![백준 골드2 달성](https://github.com/gabjuho/gabjuho.github.io/assets/42205951/3c42a029-88a3-416e-82f0-840767601f2c)

***

**이로써, 테스트를 종료한다!**

***

## 참조링크

[https://gist.github.com/ihoneymon/652be052a0727ad59601](https://gist.github.com/ihoneymon/652be052a0727ad59601)
