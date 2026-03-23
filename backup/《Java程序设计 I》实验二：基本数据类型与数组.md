```java
public class test1_wyc {
	public static void main(String[] args) {
		int a = (int)'我';
		int b = (int)'爱';
		int c = (int)'辽';
		int d = (int)'警';
		System.out.println(a);
		System.out.println(b);
		System.out.println(c);
		System.out.println(d);
	}

}
```
```java
import java.util.Scanner;
public class test3_wyc {
	public static void main(String[] args) {
		System.out.println("请在键盘依次输入两个整数");
		Scanner zhengshu = new Scanner(System.in);
		
		int a = zhengshu.nextInt();
		int b = zhengshu.nextInt();
		
		System.out.printf("%d+%d=%d", a, b, a+b);
		System.out.println();
		System.out.printf("%d-%d=%d", a, b, a-b);
	}
}

```
```java
public class Example2_4 {
	public static void main(String[] args) {
		int a[] = {1,2,3,4};
		int b[] = {100,200,300};
		System.out.println("数组a的元素个数 = "+a.length);
		System.out.println("数组b的元素个数 = "+b.length);
		System.out.println("数组a的引用（带前缀信息）"+a);
		System.out.println("数组b的引用（带前缀信息）"+b);
		System.out.println(a == b);
		int address = System.identityHashCode(a);
		System.out.printf("数组a的引用 %x\n",address);
		address = System.identityHashCode(b);
		System.out.printf("数组b的引用 %x\n",address);
		System.out.println("将b的值赋值给a");
		a = b;                // 将b的值赋值给a
		address = System.identityHashCode(a);
		System.out.printf("数组a的引用 %x\n",address);
		address = System.identityHashCode(b);
		System.out.printf("数组b的引用 %x\n",address);
		System.out.println(a == b);
		System.out.println("数组a的元素个数 = "+a.length);
		System.out.println("数组b的元素个数 = "+b.length);
		System.out.println("a[0] = "+a[0]+",a[1]"+a[1]+",a[2]"+a[2]);
		System.out.println("b[0] = "+b[0]+",b[1]"+b[1]+",b[2]"+b[2]);
	}
}

```