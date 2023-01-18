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

![Screenshot 2566-01-18 at 12 19 31](https://user-images.githubusercontent.com/115066261/213090550-a913e608-f566-4298-b24b-a52b07335556.png)

## ❔ แบบฝึกหัด จงรันโปรแกรมและบันทึกภาพ output ของบรรทัดคำสั่งต่อไปนี้

``` csharp
1. string name = "Hello";
    Console.WriteLine(String.Format("{0} there. I said {0}! {0}???", name));
```

![Screenshot 2566-01-18 at 12 23 23](https://user-images.githubusercontent.com/115066261/213091069-c039b901-ae50-4248-992a-92f2c09547f6.png)

``` csharp
2. Console.WriteLine("{2:d} {0:d} {1:d}", 1, 2, 3);
```

![Screenshot 2566-01-18 at 13 20 22](https://user-images.githubusercontent.com/115066261/213099076-e461d00e-b1ed-4645-b82e-320e438a68df.png)

``` csharp
3. Console.WriteLine("Hello " + "World");
```

![Screenshot 2566-01-18 at 13 21 01](https://user-images.githubusercontent.com/115066261/213099187-88d53d91-18c6-4b9a-9669-45b870d3c959.png)

``` csharp
4. Console.WriteLine("Here comes a slash \\");
```

![Screenshot 2566-01-18 at 13 23 04](https://user-images.githubusercontent.com/115066261/213099495-f254feab-3610-4e51-9cc0-0afe703c0fab.png)

``` csharp
5. Console.WriteLine("|{0, 10}|", 999);
```

![Screenshot 2566-01-18 at 13 24 09](https://user-images.githubusercontent.com/115066261/213099648-d13808ce-74f7-4288-b342-1a6f13760d81.png)

``` csharp
6. Console.WriteLine("|{0,-10}|", 000);
```

![Screenshot 2566-01-18 at 13 24 52](https://user-images.githubusercontent.com/115066261/213099753-22970168-b7f0-4461-98f2-52639f09e1fe.png)

``` csharp
7. Console.WriteLine("The value: {0}.", 500);
```

![Screenshot 2566-01-18 at 13 25 30](https://user-images.githubusercontent.com/115066261/213099862-3b908715-b751-427f-9b06-9a8b4ec1157b.png)

``` csharp
8. Console.WriteLine("The value: {0:C}.", 500);
```

![Screenshot 2566-01-18 at 13 26 23](https://user-images.githubusercontent.com/115066261/213099976-1e3557b2-04c1-4264-b53b-95587aaaba6c.png)

``` csharp
9. Console.WriteLine("{0,-10:F4}", 12.3456789);
```

![Screenshot 2566-01-18 at 13 27 10](https://user-images.githubusercontent.com/115066261/213100115-3c21990c-a899-4bc5-83a0-0dc20c41ed4b.png)

``` csharp
10. Console.WriteLine("{0,-10:C}", 12.3456789);
```

![Screenshot 2566-01-18 at 13 27 49](https://user-images.githubusercontent.com/115066261/213100198-f34131e9-d12a-4503-bbe3-1fa8be450fbe.png)

``` csharp
11. Console.WriteLine("{0,-10:E3}", 12.3456789);
```

![Screenshot 2566-01-18 at 13 28 57](https://user-images.githubusercontent.com/115066261/213100376-a584f72d-5d82-4940-b268-e4e4a8f0eaba.png)

``` csharp
12. Console.WriteLine("{0,-10:x}", 65535);  // (x = lower case)
```

![Screenshot 2566-01-18 at 13 29 54](https://user-images.githubusercontent.com/115066261/213100506-6bf66c12-f9f8-46e4-af0f-e2a65b4e9175.png)

``` csharp
13. Console.WriteLine("{0,-10:X}", 65535);  // (X = upper case)
```

![Screenshot 2566-01-18 at 13 30 23](https://user-images.githubusercontent.com/115066261/213100569-289cbe34-56c1-4979-9e1e-90456b65c44f.png)

``` csharp
14. int i;
    Console.WriteLine("Value\tSquared\tCubed");
    for(i = 1; i < 10; i++)
        Console.WriteLine("{0}\t{1}\t{2}", i, i*i, i*i*i);
```

![Screenshot 2566-01-18 at 13 32 16](https://user-images.githubusercontent.com/115066261/213100863-677c35e6-3625-489f-9c7e-83383d048897.png)

``` csharp
15. Console.WriteLine("{0:#.###}.", 1234.56789);
```

![Screenshot 2566-01-18 at 13 33 19](https://user-images.githubusercontent.com/115066261/213100985-90b0c22b-a5c9-4b18-92c2-17ac21ed42a2.png)


## [การใช้งานคำสั่ง Console.Read() และ Console.ReadLine()](./Lab-01-part-9-12.md)
