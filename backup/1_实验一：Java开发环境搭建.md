[https://download.oracle.com/java/21/latest/jdk-21_windows-x64_bin.msi](url)

```java
public class People {
    int height;
    String ear;
    void speak(String s) {
        System.out.println(s);
    }
}

class A {
    public static void main(String[] args) {
        People zhubajie;
        zhubajie = new People();
        zhubajie.height = 170;
        zhubajie.ear = "两只大耳朵";
        System.out.println("身高：" + zhubajie.height);
        System.out.println(zhubajie.ear);
        zhubajie.speak("师傅，咱们别去西天了，改去月宫吧");
    }
}
```
> [!TIP]
> 自主练习

```java
public class Test_2505140400 {
    public static void main(String[] args) {
        System.out.println("我的学号是2505140400");
        Info aa =new Info();
        aa.print("我是辽宁警察学院学生");
    }
}
class Info {
    public void print(String s) {
        System.out.println(s);
    }
}
```