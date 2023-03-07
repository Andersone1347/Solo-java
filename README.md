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

### Вывод всего массива.for
```
public class Main {

    public static void main(String[] args) {

        String[] days = {"Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday", "Sunday"};

        for (int i = 0; i < 7; i++) {
            System.out.println(days[i]);
        }
    }
}
```

### Масив 
![alt](src/13478.jpg)
```
import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int length = scanner.nextInt();
        int[] array =  new int[length];
        for (int i = 0; i < length; i++) {
            array[i] = scanner.nextInt();
        }
        int sum = 0;
        for (int i=0;i<length;i++){
            if (array[i]%4==0){
                sum+=array[i];
            }
        }
        System.out.println(sum);
    }
}
```
### Геометрический код.
Пример вводных данных               
2          
3         
4       
        
Результат         
9          
16    
 
Пояснение            
В этом примере мы имеем 2 квадрата (первый ввод данных) и их стороны соответственно - 3 и 4 (второй и третий вводы данных). Площадь первого квадрата равна 9 (3*3), второго - 16 (4 *4).       
```
import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int length = scanner.nextInt();
        int[] sides =  new int[length];
        for (int i = 0; i < length; i++) {
            sides[i] = scanner.nextInt();
            System.out.println(sides[i]*sides[i]);
        }
        //введите код сюда

    }
}
```

### Массивы в масиве,c выводом всех объектов через for.
```
public class Main {
    public static void main(String[] args) {
        int[][] matrix = {
                {8, 1, 6},
                {3, 5, 7},
                {4, 9, 0},
        };
        //выведите числа
        for (int i=0; i<matrix.length; i++) {

            for(int j=0; j<matrix.length; j++ ) {

                System.out.println(matrix[i][j]);

            }
        }
    }
}
```

### Цикл for & if & else c результатом.
```
public class Main {
    public static void main(String[] args) {
        int result=0;
        for (int i=0;i<5;i++){
            if(i==3) {
                result += 10;
            } else{
                result+=i;
            }
        }
        
        System.out.println(result);
    }
}
```

### То что вводишь наоборот пишет, while 
```
import java.util.Scanner;

public class Main
{
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        String text = scanner.nextLine();
        char[] arr = text.toCharArray();
        int a = arr.length;
        while (a>0){
            int i= a - 1;
            System.out.print(arr[i]);
            a--;
        }
        //введите код сюда
        ;
    }
}
```