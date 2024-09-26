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

![image](https://user-images.githubusercontent.com/100436724/235927474-04777f67-846a-42be-8b30-88f6a05c3a9e.png)


## ❔ แบบฝึกหัด จงรันโปรแกรมและบันทึกภาพ output ของบรรทัดคำสั่งต่อไปนี้

``` csharp
1. string name = "Hello";
    Console.WriteLine(String.Format("{0} there. I said {0}! {0}???", name));
```
![image](https://user-images.githubusercontent.com/100436724/235927705-6c565d2d-e9f4-45ea-8bcc-338712b41080.png)

``` csharp
2. Console.WriteLine("{2:d} {0:d} {1:d}", 1, 2, 3);
```
![image](https://user-images.githubusercontent.com/100436724/235927911-daf1709c-2bba-42b2-822c-b52180c0bf5f.png)

``` csharp
3. Console.WriteLine("Hello " + "World");
```
![image](https://user-images.githubusercontent.com/100436724/235928122-ee622ab0-c03f-4b85-bc26-f0758bb92e51.png)

``` csharp
4. Console.WriteLine("Here comes a slash \\");
```
![image](https://user-images.githubusercontent.com/100436724/235928179-4207faed-5b43-4e93-9658-8cceace79f84.png)

``` csharp
5. Console.WriteLine("|{0, 10}|", 999);
```
![image](https://user-images.githubusercontent.com/100436724/235928273-769c7f0c-7234-448e-b001-b200818ae878.png)

``` csharp
6. Console.WriteLine("|{0,-10}|", 000);
```
![image](https://user-images.githubusercontent.com/100436724/235928351-2b925789-7b0f-4f95-aff9-3367e059503f.png)

``` csharp
7. Console.WriteLine("The value: {0}.", 500);
```
![image](https://user-images.githubusercontent.com/100436724/235928417-29523076-4182-4009-8f48-2771dbfd2db6.png)

``` csharp
8. Console.WriteLine("The value: {0:C}.", 500);
```
![image](https://user-images.githubusercontent.com/100436724/235928484-3d7ec20a-b21e-4912-9a9f-e9089a111df8.png)

``` csharp
9. Console.WriteLine("{0,-10:F4}", 12.3456789);
```
![image](https://user-images.githubusercontent.com/100436724/235928542-e3d94c14-4c31-40eb-af32-cedcbfbbf339.png)

``` csharp
10. Console.WriteLine("{0,-10:C}", 12.3456789);
```
![image](https://user-images.githubusercontent.com/100436724/235928616-2bb6dd49-57f9-44ce-90e2-a3c2e8fa5a6b.png)

``` csharp
11. Console.WriteLine("{0,-10:E3}", 12.3456789);
```
![image](https://user-images.githubusercontent.com/100436724/235928680-e548ac1f-bab0-4387-9385-b2ed33151f8b.png)

``` csharp
12. Console.WriteLine("{0,-10:x}", 65535);  // (x = lower case)
```
![image](https://user-images.githubusercontent.com/100436724/235928753-1b6eb2cd-21ab-41c5-9239-68a801abe8f1.png)

``` csharp
13. Console.WriteLine("{0,-10:X}", 65535);  // (X = upper case)
```
![image](https://user-images.githubusercontent.com/100436724/235928828-0e075085-a6bc-4511-97d2-e4957c32382d.png)

``` csharp
14. int i;
    Console.WriteLine("Value\tSquared\tCubed");
    for(i = 1; i < 10; i++)
        Console.WriteLine("{0}\t{1}\t{2}", i, i*i, i*i*i);
```
![image](https://user-images.githubusercontent.com/100436724/235928919-5c94706c-e92a-4919-8228-54598cac3841.png)

``` csharp
15. Console.WriteLine("{0:#.###}.", 1234.56789);
```
![image](https://user-images.githubusercontent.com/100436724/235928987-df1a0ad8-3fb0-4520-b15b-82e48551afc9.png)


## [การใช้งานคำสั่ง Console.Read() และ Console.ReadLine()](./Lab-01-part-9-12.md)
