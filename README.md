# captcha

验证码类库

## 安装
> composer require qiankuny/captcha



## 使用

### 在控制器中输出验证码

在控制器的操作方法中使用

~~~
$cap = new Captcha();
$res = $cap->create();
~~~
