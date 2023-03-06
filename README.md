# Solo-java

### Конвектор из дней в секунды.
```
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.println("Введите колличество дней которые хотите перевести в секунды:");
        int days = scanner.nextInt();

        int second = ((days*24)*60)*60;
        System.out.println(second);
    }
}
```
### 2 Скидочные карты за двойную цену.
```
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner read = new Scanner(System.in);
        int purchases = read.nextInt();

        if(purchases > 15000){
            System.out.println("Gift card");
            //Завершите код
        } if (purchases > 30000){
            System.out.println("Gift card");
        }

    }
}

```

### 3 Switch (по цифре эмоции)     

```
import java.util.Scanner;

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int emotion = scanner.nextInt();
        switch (emotion) {
            case 1:
                System.out.println("You are happy!");
                break;
            case 2:
                System.out.println("You are sad!");
                break;
            case 3:
                System.out.println("You are angry!");
                break;
            case 4:
                System.out.println("You are surprised!");
                break;
            default:
                System.out.println("Unknown emotion.");


        }

    }
    }
```

### Факториал числа, по циклу while.     
```
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int number = scanner.nextInt();
        int fact = 1;
        //ваш код
        while (number > 0) {
            fact *= number --;
        }

        System.out.println(fact);
    }
}
```

### Welcome для студентов через for.
```
import java.util.Scanner;


public class Main
{
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int n = scanner.nextInt();
        for(int i = 0; i<n; i++ ){
            System.out.println("Welcome");
        }
    }
}
```

### ВВод пароля do while
```
import java.util.Scanner;
public class Main
{
    public static void main(String[] args) {
        Scanner read = new Scanner(System.in);
        int password;
        do {
            System.out.println("Введите правильный пароль");
            password= read.nextInt();
        } while (password!=8819);
        }

    }

```

### Калькулятор кредитов for.     
```
import java.util.Scanner;

public class Main
{
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int amount = scanner.nextInt();
        //your code goes here

        int persent;
        int payment;
        for (int i = 0 ; i < 3; i++) {
            persent = amount * 10 /100;
            payment = amount - persent;
            amount = payment;
        }
        System.out.println(amount);

    }
}

```