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
➢ รันโปรแกรมและบันทึกผล
![LAB8](./Images/Lab8.png)

## ❔ แบบฝึกหัด จงรันโปรแกรมและบันทึกภาพ output ของบรรทัดคำสั่งต่อไปนี้

``` csharp
1. string name = "Hello";
    Console.WriteLine(String.Format("{0} there. I said {0}! {0}???", name));
```
![LAB8.1](./Images/Lab8_1.png)
``` csharp
2. Console.WriteLine("{2:d} {0:d} {1:d}", 1, 2, 3);
```
![LAB8.2](./Images/Lab8_2.png)
``` csharp
3. Console.WriteLine("Hello " + "World");
```
![LAB8.3](./Images/Lab8_3.png)
``` csharp
4. Console.WriteLine("Here comes a slash \\");
```
![LAB8.4](./Images/Lab8_4.png)
``` csharp
5. Console.WriteLine("|{0, 10}|", 999);
```
![LAB8.5](./Images/Lab8_5.png)
``` csharp
6. Console.WriteLine("|{0,-10}|", 000);
```
![LAB8.6](./Images/Lab8_6.png)
``` csharp
7. Console.WriteLine("The value: {0}.", 500);
```
![LAB8.7](./Images/Lab8_7.png)
``` csharp
8. Console.WriteLine("The value: {0:C}.", 500);
```
![LAB8.8](./Images/Lab8_8.png)
``` csharp
9. Console.WriteLine("{0,-10:F4}", 12.3456789);
```
![LAB8.9](./Images/Lab8_9.png)
``` csharp
10. Console.WriteLine("{0,-10:C}", 12.3456789);
```
![LAB8.10](./Images/Lab8_10.png)
``` csharp
11. Console.WriteLine("{0,-10:E3}", 12.3456789);
```
![LAB8.11](./Images/Lab8_11.png)
``` csharp
12. Console.WriteLine("{0,-10:x}", 65535);  // (x = lower case)
```
![LAB8.12](./Images/Lab8_12.png)
``` csharp
13. Console.WriteLine("{0,-10:X}", 65535);  // (X = upper case)
```
![LAB8.13](./Images/Lab8_13.png)
``` csharp
14. int i;
    Console.WriteLine("Value\tSquared\tCubed");
    for(i = 1; i < 10; i++)
        Console.WriteLine("{0}\t{1}\t{2}", i, i*i, i*i*i);
```
![LAB8.14](./Images/Lab8_14.png)
``` csharp
15. Console.WriteLine("{0:#.###}.", 1234.56789);
```
![LAB8.15](./Images/Lab8_15.png)

## [การใช้งานคำสั่ง Console.Read() และ Console.ReadLine()](./Lab-01-part-9-12.md)