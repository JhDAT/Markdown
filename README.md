# markdown
깃허브 가이드를 참고하여 마크다운에 대해 알아봤습니다.

## Markdown 이란?
Markdown은 웹에서 텍스트의 스타일을 만드는 방법입니다. Markdown으로는 글자를 굵게하거나 기울이거나 이미지를 추가하거나 리스트를 만든것과 같은 작업을 할 수 있습니다. 대부분 Markdown은 알파벳이 아닌 #나 *과 같은 문자로 된 텍스트입니다.



## Syntax guide!!!

### Headers
```
#This is an <h1> tag
##This is an <h2> tag
#####This is an <H6> tag
```

### Emphasis
*This text will be italic*

_This will also be italic_

**This text will be bold**

__This will also bold__

_You **can** combine them_

```
*This text will be italic*
_This will also be italic_
**This text will be bold**
__This will also bold__

_You **can** combine them_
```

### Lists

#### Unordered
* Item 1
* Item 2
	* Item 2a
	* Item 2b
	
```
* Item 1
* Item 2
	* Item 2a
	* Item 2b
```

#### Ordered
1. Item 1
2. Item 2
3. Item 3
	1. Item 3a
	2. Item 3b

```
1. Item 1
2. Item 2
3. Item 3
	1. Item 3a
	2. Item 3b
```

### Images
```
![Github Logo](/images/logo.png)
Format: ![Alt Text](url)
```

### Links

https://bornteller.github.io - automatic!

[bornteller blog](https://bornteller.github.io)
```
https://bornteller.github.io - automatic!

[bornteller blog](https://bornteller.github.io)
```

### Blockquotes
As kanye West said:

> We're living the future so
> the present is our past.

```
As kanye West said:

> We're living the future so
> the present is our past.
```

### Inline code

I think you should use an

`<addr>` element here instead.
```
I think you should use an
`<addr>` element here instead.
```

### Task Lists
진행(o, x와 같은)을 표시 할수 있습니다.
```
- [x] task list 1
- [o] task list 2
- [ ] task list 3
```

### Tables

첫번째 행(row)는 `-`로 구분

각열은 `|`로 구분합니다.

| column | column2 |
|--------|--------|
|  1번입니다.   |  2번입니다      |

```
| column | column2 |
|--------|--------|
|  1번입니다.   |  2번입니다      |
```

### Automatic linking for URLs
임의의 URL을 적으면 자동으로 클릭 가능한 링크로 변환합니다.

IOS Study : https://github.com/JhDAT/iOS_Study

### Strikethrough
취소선 ~~this~~입니다.

```
취소선 ~~this~~입니다.

```

### Images

이미지를 임베디드 하려면 :

```
![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)
```

깃에 있는 폴더에 있는 이미지가져오기 :
프로젝트 작성시 img(다른 이름도 관계없다) 폴더를 만들어 이미지를 넣는다.
```
![alt text] (.img/imgName.png)
```

<br>
<br>
<br>

### Reference
1.  https://guides.github.com/features/mastering-markdown/

