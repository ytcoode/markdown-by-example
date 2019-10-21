# 代码块

代码块可以用3个及其以上的反引号（`）或波浪号（~）表示。

示例写法：

> \`\`\`\
> #include <stdio.h>\
> \
> int main(int argc, char *argv[]) {\
> &ensp;printf("hello world\n");\
> }\
> \`\`\`

示例效果：

> ```
> #include <stdio.h>
>
> int main(int argc, char *argv[]) {
>   printf("hello world\n");
> }
> ```

代码块也可以指定语言类型。

示例写法：

> \`\`\`c\
> #include <stdio.h>\
> \
> int main(int argc, char *argv[]) {\
> &ensp;printf("hello world\n");\
> }\
> \`\`\`

示例效果：

> ```c
> #include <stdio.h>
>
> int main(int argc, char *argv[]) {
>   printf("hello world\n");
> }
> ```

代码块里的内容会原样显示。

示例写法：

> \`\`\`\
> \
> \
> \# 不会解析成标题\
> \
> \`\`\`

示例效果：

> ```
> 
> 
> # 不会解析成标题
> 
> ```

注意事项：

还可以用文本行行首空4个及其以上的空格的方式表示代码块，但个人感觉这种方式并不是非常好。