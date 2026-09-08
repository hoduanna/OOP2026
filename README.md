# OOP2026
### Homework1
```java
public class Homework1 {
    public static void main(String[] args) {
        int i, j;
        for(i=0; i<10; i++){
            for(j=0; j<=i; j++){
                System.out.print(" ");
            }
            for(; j<=10; j++){
                System.out.print("#");
            }
            System.out.println();
        }

        for(i=0; i<10; i++){
            for(j=0; j<=i; j++){
                System.out.print("#");
            }
            for(; j<=10; j++){
                System.out.print(" ");
            }
            System.out.println();
        }

        for(i=10; i>0; i--){
            for(j=0; j<i; j++){
                System.out.print("#");
            }
            for(; j<=10; j++){
                System.out.print(" ");
            }
            System.out.println();
        }

        for(i=10; i>0; i--){
            for(j=0; j<=i; j++){
                System.out.print(" ");
            }
            for(; j<=10; j++){
                System.out.print("#");
            }
            System.out.println();
        }
    }
}
```
![Alt homework1](./images/homework1.png)

### Homework2
```java
public class Homework2 {
    public static void main(String[] args) {
        int n = 20;
        int first = 1;
        int second = 1;

        System.out.print(first + " " + second + " ");

        for (int i = 3; i <= n; i++) {
            int next = first + second;
            System.out.print(next + " ");
            
            first = second;
            second = next;
        }
    }
}
```
![Alt homework2](./images/homework2.png)

### Homework3
```java
public class Homework3 {
    public static void main(String[] args) {
        double a = 1;
        double b = 2;

        for (int i = 1; i <= 20; i++) {
            double ratio = b / a;
            
            if (ratio == (int) ratio) {
                System.out.printf("%d/%.0f=%.1f\n", (int)b, a, ratio);
            } else {
                String ratioStr = String.format("%.3f", ratio).replaceAll("0+$", "");
                if (ratioStr.endsWith(".")) {
                    ratioStr += "0";
                }
                System.out.printf("%d/%.0f=%s\n", (int)b, a, ratioStr);
            }

            double next = a + b;
            a = b;
            b = next;
        }
    }
}

```
![Alt homework2](./images/homework3.png)

### Homework4
```java
public class MultiplicationTable {
    public static void main(String[] args) {
        for (int i = 1; i <= 9; i++) {
            for (int j = 1; j <= 9; j++) {
                System.out.printf("%d*%d=%d\t", j, i, j * i);
            }
            System.out.println();
        }
    }
}
```
![Alt homework2](./images/homework4.png)

