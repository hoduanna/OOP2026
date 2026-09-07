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


