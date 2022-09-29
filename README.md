# Markdown-Guide


### 1. 제목(Header)

```
# This is a H1
## This is a H2
### This is a H3
#### This is a H4
##### This is a H5
###### This is a H6
```

# This is a H1

## This is a H2

### This is a H3

#### This is a H4

##### This is a H5

###### This is a H6

### 2. 목록(List)

```
1. 첫번째
2. 두번째
3. 세번째
```

1. 첫번째
2. 두번째
3. 세번째

```
* 1단계
  - 2단계
    + 3단계
      + 4단계
```

- 1단계
  - 2단계
    - 3단계
      - 4단계

### 3. 강조(Emphasis)

```
*이텔릭체* _이텔릭체_

**두껍게** __두껍게__

***이텔릭체*와 두껍게**

~~취소선~~

<u>밑줄</u>
```

_이텔릭체_ _이텔릭체_

**두껍게** **두껍게**

***이텔릭체*와 두껍게**

~~취소선~~

<u>밑줄</u>

### 4. 인용문(BlockQuote)

```
인용문(blockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.
> _(네이버 국어 사전)_

BREAK

> 인용문을 작성하세요!
>> 중첩된 인용문(nested blockquote)을 만들 수 있습니다.
>>> 인용문 1
>>> 인용문 2
>>> 인용문 3
```

인용문(blockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.
> _(네이버 국어 사전)_

BREAK!

> 인용문을 작성하세요!
>
> > 중첩된 인용문(nested blockquote)을 만들 수 있습니다.
> >
> > > 인용문 1

### 5. 코드(Code)

````

```html
<a href="https://www.google.co.kr/" target="_blank">GOOGLE</a>
```

```css
.list > li {
  position: absolute;
  top: 40px;
}
```

```javascript
function func() {
  var a = 'AAA';
  return a;
}
```

```bash
$ vim ./~zshrc
```

```python
s = "Python syntax highlighting"
print s
```

```
No language indicated, so no syntax highlighting.
But let's throw in a tag.
```
<pre><code>
use pre & code
</code></pre>
````

```html
<a href="https://www.google.co.kr/" target="_blank">GOOGLE</a>
```

```css
.list > li {
  position: absolute;
  top: 40px;
}
```

```javascript
function func() {
  var a = 'AAA'
  return a
}
```

```bash
$ vim ./~zshrc
```

```python
s = "Python syntax highlighting"
print s
```

```
No language indicated, so no syntax highlighting.
But let's throw in a tag.
```

<pre><code>
use pre & code
</code></pre>

### 6. 수평선(Horizontal Rule)

```
수평선 1
---

수평선 2
***

수평선 3
___

수평선 4
<hr/>
```

---

---

---

<hr/>

### 7. HTML 코드

```
줄 <br/>바꿈
```

줄 <br/>바꿈

### 8. 표

헤더 셀을 구분할 때 3개 이상의 -(hyphen/dash) 기호가 필요합니다.

헤더 셀을 구분하면서 :(Colons) 기호로 셀(열/칸) 안에 내용을 정렬할 수 있습니다.

가장 좌측과 가장 우측에 있는 |(vertical bar) 기호는 생략 가능합니다.

```
| 값 | 의미 | 기본값 |
|---|:---:|---:|
| `static` | 유형(기준) 없음 / 배치 불가능 | `static` |
| `relative` | 요소 자신을 기준으로 배치 |  |
| `absolute` | 위치 상 부모(조상)요소를 기준으로 배치 |  |
| `fixed` | 브라우저 창을 기준으로 배치 |  |
```

| 값         |                     의미                     |   기본값 |
| ---------- | :------------------------------------------: | -------: |
| `static`   |        유형(기준) 없음 / 배치 불가능         | `static` |
| `relative` |        요소 **자신**을 기준으로 배치         |
| `absolute` | 위치 상 **_부모_(조상)요소**를 기준으로 배치 |
| `fixed`    |       **브라우저 창**을 기준으로 배치        |

### 9. 링크(Link)

```
[link keyword][id]

[id]: URL "Optional Title here"

Link: [Google][googlelink]

[googlelink]: https://google.com "Go google"
```

[link keyword][id]

[id]: URL 'Optional Title here'

Link: [Google][googlelink]

[googlelink]: https://google.com 'Go google'

### 10. 이미지

```
![Alt text](/path/to/img.jpg)
<img src="/path/to/img.jpg" width="450px" height="300px" title="px(픽셀) 크기 설정" alt="jabee"></img><br/>
```

![Alt text](/static/images/jabee.png)

<img src="/static/images/jabee.png" width="450px" height="300px" title="px(픽셀) 크기 설정" alt="jabee"></img>
