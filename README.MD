## 6位密码输入框
 https://github.com/Jungerr/GridPasswordView

#### 使用方法

 >1. clearPassword()：清除输入框中的东西

 >2. setPassword(String password)：和textview 的setText(String s)方法一样

 >3. togglePasswordVisibility()：此方法设置可见状态的切换

 >4. setPasswordVisibility(boolean visible)：设置密码是否可见

 >5. setOnPasswordChangedListener(OnPasswordChangedListener listener): 密码输入的监听，你懂得

 >6. setPasswordType(PasswordType passwordType)：设置密码的输入类型４种（numberPassword 、textPassword 、TEXtextVisiblePassword、textWebPassword）

 >7. getPassWord()：获取用户输入的密码

`

    String pwd = gpv_password.getPassWord();
    gpv_password = (GridPasswordView) findViewById(R.id.gpv_password);

`

    添加依赖
    dependencies {
        compile 'com.jungly:gridPasswordView:0.3'
    }
