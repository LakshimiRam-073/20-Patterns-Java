# 20-Patterns-Java
## Patterns

## Pattern 1

```
*****
*****
*****
*****
*****
```

### Code :

```java
// You are using Java
import java.util.*;
class Main{
    public static void main(String[] args)
    {
        Scanner scn = new Scanner(System.in);
        
        int n = scn.nextInt();
        pattern(n);
    }
    public static void pattern(int n)
    {
        for(int i=0;i<n;i++)
        {
            for(int j=0;j<n;j++)
            {
                System.out.print("*");
            }
            System.out.println();
        }
    }
}
```

## Pattern 2

```
*
**
***
****
*****
```

### Code :

```java
// You are using Java
import java.util.*;
class Main{
    public static void main(String[] args)
    {
        Scanner scn = new Scanner(System.in);
        
        int n = scn.nextInt();
        pattern(n);
    }
    public static void pattern(int n)
    {
        for(int i=1;i<=n;i++)
        {
            for(int j=1;j<=i;j++)
            {
                System.out.print("*");
            }
            System.out.println();
        }
    }
}
```

## Pattern 3

```
1
12
123
1234
12345
```

### Code :

```java
// You are using Java
import java.util.*;
class Main{
    public static void main(String[] args)
    {
        Scanner scn = new Scanner(System.in);
        
        int n = scn.nextInt();
        pattern(n);
    }
    public static void pattern(int n)
    {
        for(int i=1;i<=n;i++)
        {
            for(int j=1;j<=i;j++)
            {
                System.out.print(j);
            }
            System.out.println();
        }
    }
}
```

## Pattern 4

```
1
22
333
4444
55555
```

### Code :

```java
// You are using Java
import java.util.*;
class Main{
    public static void main(String[] args)
    {
        Scanner scn = new Scanner(System.in);
        
        int n = scn.nextInt();
        pattern(n);
    }
    public static void pattern(int n)
    {
        for(int i=1;i<=n;i++)
        {
            for(int j=1;j<=i;j++)
            {
                System.out.print(i);
            }
            System.out.println();
        }
    }
}
```

## Pattern 5

```
*****
****
***
**
*
```

### Code :

```java
// You are using Java
import java.util.*;
class Main{
    public static void main(String[] args)
    {
        Scanner scn = new Scanner(System.in);
        
        int n = scn.nextInt();
        pattern(n);
    }
    public static void pattern(int n)
    {
        for(int i=0;i<n;i++)
        {
            for(int j=n-1;j>=i;j--)
            {
                System.out.print("*");
            }
            System.out.println();
        }
    }
}
```

## Pattern 6

```
12345
1234
123
12
1
```

### Code :

```java
// You are using Java
import java.util.*;
class Main{
    public static void main(String[] args)
    {
        Scanner scn = new Scanner(System.in);
        
        int n = scn.nextInt();
        pattern(n);
    }
    public static void pattern(int n)
    {
        for(int i=0;i<n;i++)
        {
            for(int j=1;j<=n-i;j++)
            {
                System.out.print(j);
            }
            System.out.println();
        }
    }
}
```

## Pattern 7

```
    *
   * *
  * * *
 * * * *
* * * * *
```

### Code :

```java
// You are using Java
import java.util.*;
class Main{
    public static void main(String[] args)
    {
        Scanner scn = new Scanner(System.in);
        
        int n = scn.nextInt();
        pattern(n);
    }
    public static void pattern(int n)
    {
        for(int i=1;i<=n;i++)
        {
            int numSpace = n-i;
            
            for(int j= 0;j<numSpace ;j++)
            {
                System.out.print(" ");
            }
            for(int j=1;j<=i;j++)
            {
                System.out.print("* ");
            }
            System.out.println();
        }
    }
}
```

## Pattern 8

```
* * * * *
 * * * *
  * * *
   * *
    *
```

### Code :

```java
// You are using Java
import java.util.*;
class Main{
    public static void main(String[] args)
    {
        Scanner scn = new Scanner(System.in);
        
        int n = scn.nextInt();
        pattern(n);
    }
    public static void pattern(int n)
    {
        for(int i=0;i<n;i++)
        {
            int numSpace = i;
            
            for(int j= 0;j<numSpace ;j++)
            {
                System.out.print(" ");
            }
            for(int j=1;j<=n-i;j++)
            {
                System.out.print("* ");
            }
            System.out.println();
        }
    }
}
```

## Pattern 9

```
    *
   * *
  * * *
 * * * *
* * * * *
 * * * *
  * * *
   * *
    *

```

### Code :

```java
// You are using Java
import java.util.*;
class Main{
    public static void main(String[] args)
    {
        Scanner scn = new Scanner(System.in);
        
        int n = scn.nextInt();
        pattern(n);
    }
    public static void pattern(int n)
    {
        for(int i=1;i<=n*2;i++)
        {
            int numCol = i> n? 2*n-i : i;
            int numSpace = n - numCol;
            for(int j= 0;j<numSpace ;j++)
            {
                System.out.print(" ");
            }
            for(int j=1;j<=numCol;j++)
            {
                System.out.print("* ");
            }
            System.out.println();
        }
    }
}
```

## Pattern 10:

```
*
* *
* * *
* * * *
* * * * *
* * * *
* * *
* *
*

```

### Code :

```java
// You are using Java
import java.util.*;
class Main{
    public static void main(String[] args)
    {
        Scanner scn = new Scanner(System.in);
        
        int n = scn.nextInt();
        pattern(n);
    }
    public static void pattern(int n)
    {
        for(int i=1;i<=n*2;i++)
        {
            int numCol = i> n? 2*n-i : i;
            
            for(int j=1;j<=numCol;j++)
            {
                System.out.print("* ");
            }
            System.out.println();
        }
    }
}
```

## Pattern 11

```
1
0 1
1 0 1
0 1 0 1
1 0 1 0 1
```

### Code :

```java
// You are using Java
import java.util.*;
class Main{
    public static void main(String[] args)
    {
        Scanner scn = new Scanner(System.in);
        
        int n = scn.nextInt();
        pattern(n);
    }
    public static void pattern(int n)
    {
        for(int i=1;i<=n;i++)
        {
            
            for(int j=1;j<=i;j++)
            {
                
                System.out.print((i+j)%2== 0?1:0);
                System.out.print(" ");
            }
            System.out.println();
        }
    }
}
```

## Pattern 12

```
1      1
12    21
123  321
12344321
```

### Code

```java
// You are using Java
import java.util.*;
class Main{
    public static void main(String[] args)
    {
        Scanner scn = new Scanner(System.in);
        
        int n = scn.nextInt();
        pattern(n);
    }
    public static void pattern(int n)
    {
            int numSpace = 2*(n-1);
        for(int i=1;i<=n;i++)
        {
            
            for(int j=1;j<=i;j++)
            {
               System.out.print(j);
            }
            for(int j=0;j<numSpace;j++)
            {
                System.out.print(" ");
            }
            
            for(int j=i;j>=1;j--)
            {
               System.out.print(j);
            }
            System.out.println();
            numSpace-=2;
        }
    }
}
```

## Pattern 13

```
1
2 3
4 5 6
7 8 9 10
11 12 13 14 15
```

### Code

```java
// You are using Java
import java.util.*;
class Main{
    public static void main(String[] args)
    {
        Scanner scn = new Scanner(System.in);
        
        int n = scn.nextInt();
        pattern(n);
    }
    public static void pattern(int n)
    {
            int count =1;
        for(int i=1;i<=n;i++)
        {

            
            for(int j=1;j<=i;j++)
            {
               System.out.print(count++ +" ");
            }
            System.out.println();
        }
    }
}
```

## Pattern 14

```
A
AB
ABC
ABCD
ABCDE
```

### Code

```java
// You are using Java
import java.util.*;
class Main{
    public static void main(String[] args)
    {
        Scanner scn = new Scanner(System.in);
        
        int n = scn.nextInt();
        pattern(n);
    }
    public static void pattern(int n)
    {
        for(int i=1;i<=n;i++)
        {

            
            for(int j=0;j<i;j++)
            {
               System.out.print((char)('A'+j));
            }
            System.out.println();
        }
    }
}
```

## Pattern 15

```
ABCDE
ABCD
ABC
AB
A
```

### Code

```java
// You are using Java
import java.util.*;
class Main{
    public static void main(String[] args)
    {
        Scanner scn = new Scanner(System.in);
        
        int n = scn.nextInt();
        pattern(n);
    }
    public static void pattern(int n)
    {
        for(int i=1;i<=n;i++)
        {

            
            for(int j=0;j<=n-i;j++)
            {
               System.out.print((char)('A'+j));
            }
            System.out.println();
        }
    }
}
```

## Pattern 16

```
A
BB
CCC
DDDD
EEEEE
```

### Code

```java
// You are using Java
import java.util.*;
class Main{
    public static void main(String[] args)
    {
        Scanner scn = new Scanner(System.in);
        
        int n = scn.nextInt();
        pattern(n);
    }
    public static void pattern(int n)
    {
        for(int i=0;i<n;i++)
        {

            
            for(int j=0;j<=i;j++)
            {
               System.out.print((char)('A'+i));
            }
            System.out.println();
        }
    }
}
```

## Pattern 17

```
		 A
    ABA
   ABCBA
  ABCDCBA
 ABCDEDCBA
```

### Code

```java
// You are using Java
import java.util.*;
class Main{
    public static void main(String[] args)
    {
        Scanner scn = new Scanner(System.in);
        
        int n = scn.nextInt();
        pattern(n);
    }
    public static void pattern(int n)
    {
        for(int i=0;i<n;i++)
        {

            int numSpace =n-i;
            for(int j=0;j<numSpace ;j++)
                System.out.print(" ");
            for(int j=0;j<=i;j++)
           {
               System.out.print((char)('A'+j));
            }
            if(i>=1)
            {
                
                for(int j=i-1 ;j>=0 ;j--)
                {
                    System.out.print((char)('A' +j));
                }
            }
            System.out.println();
        }
    }
}
```

## Pattern 18

```
E
DE
CDE
BCDE
ABCDE
```

### Code :

```java
// You are using Java
import java.util.*;
class Main{
    public static void main(String[] args)
    {
        Scanner scn = new Scanner(System.in);
        
        int n = scn.nextInt();
        pattern(n);
    }
    public static void pattern(int n)
    {
        for(int i=0;i<n;i++)
        {
            
            for(char a =(char)(int)('A' +n-i-1); a<=(char)(int) ('A' +n-1) ;a++)
           {
               System.out.print(a);
            }
            System.out.println();
        }
    }
}
```

## Pattern 19

```
* * * * *
*       *
*       *
*       *
* * * * *
```

### Code :

```java
// You are using Java
import java.util.*;
class Main{
    public static void main(String[] args)
    {
        Scanner scn = new Scanner(System.in);
        
        int n = scn.nextInt();
        pattern(n);
    }
    public static void pattern(int n)
    {
        for(int i=0;i<n;i++)
        {
            
            for(int j =0;j<n;j++)
           {
               if(i ==0 || j ==0 || j ==n-1 || i== n-1)
               System.out.print("* ");
               else 
               System.out.print("  ");
            }
            System.out.println();
        }
    }
}
```

## Pattern 20

```
4 4 4 4 4 4 4
4 3 3 3 3 3 4
4 3 2 2 2 3 4
4 3 2 1 2 3 4
4 3 2 2 2 3 4
4 3 3 3 3 3 4
4 4 4 4 4 4 4
```

### Code

```java
// You are using Java
import java.util.*;
class Main{
    public static void main(String[] args)
    {
        Scanner scn = new Scanner(System.in);
        
        int n = scn.nextInt();
        pattern(n);
    }
    public static void pattern(int n)
    {
        for(int i=1;i<n*2;i++)
        {
            
            for(int j =1;j<n*2;j++)
           {
               int num =n- Math.min(Math.min(i ,j),Math.min(2*n-i ,2*n-j))+1;
               System.out.print(num +" ");
            }
            System.out.println();
        }
    }
}
```

## Pattern 21

```
**********
****  ****
***    ***
**      **
*        *
*        *
**      **
***    ***
****  ****
**********
```

### Code:

```java
// You are using Java
import java.util.*;
class Main{
    public static void main(String[] args)
    {
        Scanner scn = new Scanner(System.in);
        
        int n = scn.nextInt();
        pattern(n);
    }
    public static void pattern(int n)
    {
            int numSpace =0;
        for(int i=0;i<n;i++)
        {
            int totalCol = n -i;
            for(int j =0;j<totalCol;j++)
           {
               System.out.print("*");
            }
            for(int j=0;j< numSpace ;j++)
                System.out.print(" ");
            
            for(int j =0;j<totalCol;j++)
           {
               System.out.print("*");
            }
            numSpace+=2;
            System.out.println();
        }
        numSpace = 2*n - 2;
        for(int i=1;i<=n;i++)
        {
            int totalCol = i;
            for(int j =1;j<=totalCol;j++)
           {
               System.out.print("*");
            }
            for(int j=0;j<numSpace ;j++)
                System.out.print(" ");
            
            for(int j =1;j<=totalCol;j++)
           {
               System.out.print("*");
            }
            numSpace-=2;
            System.out.println();
        }
    }
}
```

## Pattern 22

```
*        *
**      **
***    ***
****  ****
**********
****  ****
***    ***
**      **
*        *
```

### Code

```java
// You are using Java
import java.util.*;
class Main{
    public static void main(String[] args)
    {
        Scanner scn = new Scanner(System.in);
        
        int n = scn.nextInt();
        pattern(n);
    }
    public static void pattern(int n)
    {
        
            int numSpace = 2*n -2 ;
        for(int i=1;i<=n;i++)
        {
            
            for(int j=1;j<=i;j++)
            {
                System.out.print("*");
            }
            for(int j=0;j<numSpace ;j++)
            {
                System.out.print(" "); 
            }
            for(int j=1;j<=i;j++)
            {
                System.out.print("*");
            }
            
            numSpace-=2;
            System.out.println();
        }
        numSpace =2;
        for(int i=1;i<n;i++)
        {
            
            for(int j=1;j<=n-i;j++)
            {
                System.out.print("*");
            }
            for(int j=0;j<numSpace ;j++)
            {
                System.out.print(" "); 
            }
            for(int j=1;j<=n-i;j++)
            {
                System.out.print("*");
            }
            
            numSpace+=2;
            System.out.println();
        }
    }
}
```
