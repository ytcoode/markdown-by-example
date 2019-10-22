# 自动链接

我们可以将URL地址放入 `<` 和 `>` 之间，使其成为自动链接。

示例：

> `<https://commonmark.org>`

效果：

> <https://commonmark.org>

邮件地址也可以使用同样的方式成为自动链接。

示例：

> `<foo@bar.example.com>`

效果：

> <foo@bar.example.com>

自动链接的地址不能包含空格（下面之所以还是链接，是因为GitHub在CommonMark标准的基础上加了对自动链接的扩展，如果想看标准效果，可以点击 [这里](https://spec.commonmark.org/dingus/?text=<https://commonmark.org>%20<%20https://commonmark.org>)）。

示例：

> `< https://commonmark.org>`

效果：

> < https://commonmark.org>

转义字符在自动链接中不生效。

示例：

> `<https://commonmark\.org>`

效果：

> <https://commonmark\.org>
