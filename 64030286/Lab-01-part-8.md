# Lab-01  Part 8  การกำหนดรูปแบบพร้อมความกว้างของทศนิยมของอาร์กิวเมนต์

👉 แก้โปรแกรมตามรูปด้านล่างนี้
```csharp
const double i = 123.456789d;
Console.WriteLine("{0:F1}", i);
Console.WriteLine("{0:F2}", i);
Console.WriteLine("{0:F3}", i);
Console.WriteLine("{0:F4}", i);
Console.WriteLine("{0:F5}", i);
```
➢ รันโปรแกรมและบันทึกผล<br>
![](./Lab1-64030312/image/011.png)
![image](https://user-images.githubusercontent.com/115067018/233414223-303073d9-6846-4d45-a147-7453c8048a83.png)

## ❔ แบบฝึกหัด จงรันโปรแกรมและบันทึกภาพ output ของบรรทัดคำสั่งต่อไปนี้

``` csharp
1. string name = "Hello";
    Console.WriteLine(String.Format("{0} there. I said {0}! {0}???", name));
```
![image](https://user-images.githubusercontent.com/115067018/233414575-3938c70d-a4ee-4c90-8b1c-c52bb69c17f7.png)
``` csharp

2. Console.WriteLine("{2:d} {0:d} {1:d}", 1, 2, 3);
```
![image](https://user-images.githubusercontent.com/115067018/233414626-43f5c3a0-b996-4245-8fca-9e5db4445bf4.png)
``` csharp

3. Console.WriteLine("Hello " + "World");
```
![image](https://user-images.githubusercontent.com/115067018/233414684-de4ad5b8-f4b4-4c99-9126-3aafc8f9fd61.png)
``` csharp

4. Console.WriteLine("Here comes a slash \\");
```
![image](https://user-images.githubusercontent.com/115067018/233414725-f2d21e51-ee8e-4009-8877-14c76288cd52.png)
``` csharp

5. Console.WriteLine("|{0, 10}|", 999);
```
![image](https://user-images.githubusercontent.com/115067018/233414776-8e890a8c-70d0-42fb-b1a9-12c781134ed7.png)
``` csharp

6. Console.WriteLine("|{0,-10}|", 000);
```
![image](https://user-images.githubusercontent.com/115067018/233414836-22968a20-d2a5-41b6-b5bf-f3b9ad16a905.png)
``` csharp

7. Console.WriteLine("The value: {0}.", 500);
```
![image](https://user-images.githubusercontent.com/115067018/233414891-2c2719fc-a71d-41d2-a64c-8f65cefca23c.png)
``` csharp

8. Console.WriteLine("The value: {0:C}.", 500);
```
![image](https://user-images.githubusercontent.com/115067018/233415553-845ebd54-af87-48c3-a5c5-1a09804f76c2.png)
``` csharp

9. Console.WriteLine("{0,-10:F4}", 12.3456789);
```
![image](https://user-images.githubusercontent.com/115067018/233415602-d2e4ac8b-44e4-4abf-9c45-790707cca213.png)
``` csharp

10. Console.WriteLine("{0,-10:C}", 12.3456789);
```
![image](https://user-images.githubusercontent.com/115067018/233415635-a4948559-cdf1-4d26-8f9d-152a2ada8b79.png)
``` csharp

11. Console.WriteLine("{0,-10:E3}", 12.3456789);
```
![image](https://user-images.githubusercontent.com/115067018/233415716-14917ffb-aa14-48f7-8943-20e3a7d1220a.png)
``` csharp

12. Console.WriteLine("{0,-10:x}", 65535);  // (x = lower case)
```
![image](https://user-images.githubusercontent.com/115067018/233415760-25e1601c-697d-4d43-832f-fd27251f0d66.png)
``` csharp

13. Console.WriteLine("{0,-10:X}", 65535);  // (X = upper case)
```
![image](https://user-images.githubusercontent.com/115067018/233415826-005cae82-1f5d-489d-98c2-7018eefec862.png)
``` csharp

14. int i;
    Console.WriteLine("Value\tSquared\tCubed");
    for(i = 1; i < 10; i++)
        Console.WriteLine("{0}\t{1}\t{2}", i, i*i, i*i*i);
```
![image](https://user-images.githubusercontent.com/115067018/233415884-3d87c636-cc85-4deb-b301-36cae6d9316e.png)
``` csharp

15. Console.WriteLine("{0:#.###}.", 1234.56789);
```

![image](https://user-images.githubusercontent.com/115067018/233415941-bc044740-da40-459c-b8d0-1b87a3880b97.png)


## [การใช้งานคำสั่ง Console.Read() และ Console.ReadLine()](./Lab-01-part-9-12.md)
