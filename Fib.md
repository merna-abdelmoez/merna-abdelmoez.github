
# **Codes to calculate Fibonacci nth term**    
  ![alt text](http://t1.gstatic.com/licensed-image?q=tbn:ANd9GcRP5VHvglI8NXAt2RWH3Q2fxztPEOzs-w1ZETJQPZzwKyZLYj6ykVQStLJ7uwxnbaiV)
## *First code*


     #include <iostream>
      using namespace std;
      int fib(int n)
     {
	 if (n <= 1)	

		return n;
	 else

		return (fib(n - 1) + fib(n - 2));
        }
     int main()
     {
	 int n;

	 cout << "Enter the no of the term you want";

	 cin >> n;

	 cout << fib(n);
     } 

## *Second code*

      #include <iostream>
      #include<bits/stdc++.h>
        using namespace std;
      int F(int N) {
     int a = 0, b = 1, c, i;
        if(N==0)
        return a;
      for(i=2;i<=N;i++){
        c=a+b;
        a=b;
        b=c
       }
      return b;
      }
        int main()
       int N=5;
      cout<< F(N);
     return 0;
        }
            


## *Third code*
     #include<stdio.h>
     int fib(int n)
      {
       int f[n+1];
       int i; 
       f[0] = 0;
       f[1] = 1;
       for (i = 2; i <= n; i++)
      {
       f[i] = f[i-1] + f[i-2];
       }
        return f[n];
       }
        int main ()
       {
        int n = 9;
        printf("%d", fib(n));
        getchar();
        return 0;
       }

## *Fourth code*
      #include<stdio.h>
      int fib(int n)
     {
      int a = 0, b = 1, c, i;
      if( n == 0)
        return a;
        for (i = 2; i <= n; i++)
     {
        c = a + b;
      a = b;
       b = c;
      }
        return b;
       }
        int main ()
      {
       int n = 9;
      printf("%d", fib(n));
      getchar();
        return 0;
       }
## **Comparison Table**

| code | Time complexity | Auxlitary Space |
| ----------- | ----------- | ------------|
| 1 | O(2^n) |O(n) |
| 2 | O(n) | O(n)  |
| 3 |  O(n)    |O(n) |
| 4 | O(n)     |O(1) |

## **References**
[https://www.geeksforgeeks.org/c-program-for-n-th-fibonacci-number/](https://www.geeksforgeeks.org/c-program-for-n-th-fibonacci-number/)

## **Tasks**
- [x] picture
- [x] different font size and style
- [x] table
- [x] code block
- [x] list
- [x] link
 


