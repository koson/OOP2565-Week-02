# Lab-01 Part 4 จำนวนของอาร์กิวเมนต์ในคำสั่ง Console.WriteLine()

โดยทั่วไป การพิมพ์ข้อความออกทาง console สามารถพิมพ์ข้อความได้ทั้งแบบตายตัวและเปลี่ยนแปลงได้โดยโปรแกรม หากเราต้องการพิมพ์แบบตายตัวก็อาจใช้คำสั่ง `Console.WriteLine` เขียนเรียงกันไปเรื่อยๆ 

👉 แก้โปรแกรมตามรูปด้านล่างนี้

```csharp
Console.WriteLine("This is text 1.");
Console.WriteLine("This is text 2.");
Console.WriteLine("This is text 3.");
```

➢ รันโปรแกรมและบันทึกผล<br>
![](./Lab1-64030312/image/005.png)
![image](https://user-images.githubusercontent.com/115067018/233413164-d11ee234-8e9b-42df-a828-67a49bc5b35d.png)


ถ้าหากต้องการให้แก้ไขค่าตัวแปรที่จะแสดงออกทาง console เราก็อาจจะใช้ป้ายกำกับสำหรับรับค่าออกไปแสดงที่ output เรียกว่า place holder

การนับลำดับ place holder จะเริ่มจากตัวแรกที่มีค่าเป็น 0

👉 แก้โปรแกรมตามรูปด้านล่างนี้

```csharp
Console.WriteLine(" {0} and {1}", 3, 6);
```

➢ รันโปรแกรมและบันทึกผล<br>
![](./Lab1-64030312/image/006.png)
![image](https://user-images.githubusercontent.com/115067018/233413271-908cf867-02fc-4a9a-968f-67f994be3fe4.png)

❔ ถ้ามีการใช้ตัวเลขใน { } ที่กระโดด เช่น {0} {2} {3} จะใช้งานได้หรือไม่ อย่างไร จงอธิบาย


👉แก้โปรแกรมตามรูปด้านล่างนี้

```csharp
Console.WriteLine("{1}, {0} and {1}", 3, 6);
```

➢ รันโปรแกรมและบันทึกผล<br>
![](./Lab1-64030312/image/007.png)
 ![image](https://user-images.githubusercontent.com/115067018/233413366-b8cfd9f7-5307-4e2a-8863-36c0f10dc3f6.png)

## [5. การกำหนดความกว้างของอาร์กิวเมนต์](./Lab-01-part-5-7.md)
