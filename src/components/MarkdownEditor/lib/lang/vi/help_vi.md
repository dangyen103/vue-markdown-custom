@[toc](Mục lục)

Markdown Guide
===
> Chi tiết: [http://commonmark.org/help/](http://commonmark.org/help/)

## **In đậm**
```
**In đậm**
__In đậm__
```
## *In nghiêng*
```
*In nghiêng*
__In nghiêng__
```
## Tiêu đề
```
# h1 #
h1
====
## h2 ##
h2
----
### h3 ###
#### h4 ####
##### h5 #####
###### h6 ######
```
## Đường phân chia (Dividing line)
```
***
---
```
****
## ^Chỉ số^trên & ~Chỉ số~dưới
```
chỉ số trên x^2^
chỉ số dưới H~2~0
```
## ++Gạch chân++ & ~~Gạch ngang chữ~~
```
++gạch chân++
~~gạch ngang chữ~~
```
## ==Đánh dấu==
```
==đánh dấu==
```
## Trích dẫn

```
> trích dẫn 1
>> trích dẫn 2
>>> trích dẫn 3
...
```

## Danh sách
```
Danh sách được đánh số
1.
2.
3.
...

Danh sách có dấu đầu dòng
-
-
...
```

## Todo List

- [x] task 1
- [ ] task 2

```
- [x] task 1
- [ ] task 2
```

## Đường dẫn
```
Đường dẫn văn bản
[Văn bản](www.husmon.com)

Đường dẫn hình ảnh
![Văn bản](http://www.husmon.com/hinh-anh.png)
```
## Mã nguồn
\``` ngôn ngữ

code block

\```

\` code \`

```c++
int main()
{
    printf("hello world!");
}
```
`code`

## Bảng
```
| th1 | th2 | th3 |
| :--  | :--: | ----: |
| trái | giữa | phải |
```
| th1 | th2 | th3 |
| :--  | :--: | ----: |
| trái | giữa | phải |
| ---------------------- | ------------- | ----------------- |
## Footnote
```
hello[^hello]
```

Look at the bottom[^hello]

[^hello]: footnote

## Emojis
Chi tiết: [https://www.webpagefx.com/tools/emoji-cheat-sheet/](https://www.webpagefx.com/tools/emoji-cheat-sheet/)
```
:laughing:
:blush:
:smiley:
:)
...
```
:laughing::blush::smiley::)

## $\KaTeX$ Toán học

Chúng ta có thể render các công thức chẳng hạn：$x_i + y_i = z_i$ and $\sum_{i=1}^n a_i=0$
Chúng ta cũng có thể render chúng trên một dòng:
$$\sum_{i=1}^n a_i=0$$
Chi tiết: [katex](http://www.intmath.com/cg5/katex-mathjax-comparison.php) và [katex function](https://github.com/Khan/KaTeX/wiki/Function-Support-in-KaTeX) hay [latex](https://math.meta.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference)

## Bố cục

::: hljs-left
`::: hljs-left`
`căn trái`
`:::`
:::

::: hljs-center
`::: hljs-center`
`căn giữa`
`:::`
:::

::: hljs-right
`::: hljs-right`
`căn phải`
`:::`
:::

## deflist

Term 1

:   Definition 1

Term 2 with *inline markup*

:   Definition 2

        { some code, part of Definition 2 }

    Third paragraph of definition 2.

```
Term 1

:   Definition 1

Term 2 with *inline markup*

:   Definition 2

        { some code, part of Definition 2 }

    Third paragraph of definition 2.

```

## abbr
*[HTML]: Hyper Text Markup Language
*[W3C]:  World Wide Web Consortium
The HTML specification
is maintained by the W3C.
```
*[HTML]: Hyper Text Markup Language
*[W3C]:  World Wide Web Consortium
The HTML specification
is maintained by the W3C.
```
