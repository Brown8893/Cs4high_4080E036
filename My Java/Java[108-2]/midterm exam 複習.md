# Midterm exam 複習
```
package myPackage;

public class MyMath2 {

public static void main(String[] args) {
int x = 10;
System.out.println(x*x*x);
}
}
```
```
package myPackage;

public class MyMath3 {

public static void main(String[] args) {
int x = 10;
int y = 20;
int z = 30;
System.out.println(x+y+z);
}
}
```
```
package myPackage;

public class MyMath4 {

public static void main(String[] args) {
 int i,sum = 0;
 for (i = 1 ; i <= 100 ; i++)
 {
 sum += i;
 }
 System.out.println(sum); //輸出結果
}
}
```
```
package myPackage;

public class MyMath5 {

public static void main(String[] args) {
sum1to100();
}
public static void sum1to100() {
int i,sum = 0;

 for (i = 1 ; i <= 100 ; i++)
 {
 sum += i;
 }
 System.out.println(sum); //輸出結果
}
}
```
```
package myPackage;

import java.util.Scanner;

public class MyMath1 {

public static void main(String[] args) {
int N ;
Scanner scanner = new Scanner(System.in);
System.out.println("請輸入一個數字：");
N = scanner.nextInt();
sum1toN(N);
}

public static void sum1toN(int N) {
System.out.println(1+2+3+4+5+6+ N );
}
}
```
# -----------------------------------------------------------------------
```
package myPackage;

public class MyClass {
	
	public static void main (String[]args) {
		System.out.println("資工一A/4080E036/吳承翰");
		
	}
	
}
```
```
package myPackage;

public class MyMath {

	public static void main(String[] args) {
		int x = 10;
		//int result = x*x*x;
		System.out.println(x*x*x);
		//System.out.println(result);
		
	}

}

//長整數 long x =10;
//		 long result = x*x*x*x*x*x*x*x*x*x;

```
```
package myPackage;

public class MyMath1 {

	public static void main(String[] args) {
		int x = 10;
		int y = 20;
		int z = 30;
		System.out.println(x+y+z);

	}

}
```
```
package myPackage;

public class MyMath2 {

	public static void main(String[] args) {
		int i ;
		for(i=0;i<101;i++) {
			System.out.println(i);
		}

	}

}
```
# 中階考題 1
```
package myPackage;

public class MyMath3 {

	public static void main(String[] args) {
		Math();
	}
	public static void Math() {
		int i ;
		for(i=0;i<101;i++) {
			System.out.println(i);
		}
	}

}
```
# 中階考題 2
```
package myPackage;
import java.util.Scanner;

public class MyMath中階2 {

	public static void main(String[] args) {
		int N;
		Scanner scanner = new Scanner(System.in);
		System.out.println("請輸入一個數字：");
		N = scanner.nextInt();
		System.out.println(1+2+3+4+5+N);
	}

}
```
# 中階考題 3
```
package myPackage;

import java.io.BufferedReader;
import java.io.FileReader;
import java.io.IOException;


public class MyFileReader {

	public static void main(String[] args) throws IOException {
		readAndParseTxtFile();

	}
	public static void readAndParseTxtFile () throws IOException {

        FileReader fr 
            = new FileReader("./data/customer.txt");
        
        BufferedReader br
              = new BufferedReader(fr); 
        

        String temp = null; //準備一個字串變數temp
        while( (temp=br.readLine()) != null) {//從檔案中，一次讀取一行，每一行就是一筆顧客資料
            System.out.println(temp);

        }

        if(br != null) {
            br.close();
        }
	
	}
}

```
# 中階考題 3 輸出結果
```
c0002020-1	李麥克	崑大路195號	0919-058823	t097000085@g.ksu.edu.tw
c0002020-2	黃偉哲	台南縣七股鄉	06-6326303	mayor@mail.tainan.gov.tw
c0002020-3	柯文哲	臺北市信義區市府路1號	02-27208889	kowj@mail.taipei.gov.tw
c0002020-4	賴清德	臺北縣萬里鄉	02-2358-6931	semicontaiwan@semi.org
```
