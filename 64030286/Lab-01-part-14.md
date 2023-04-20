# Lab-01 การเขียนโปรแกรมด้วยตัวดำเนินการทางตรรกะ

ตัวแปรชนิด boolean มักจะถูกใช้เป็นที่เก็บผลที่เกิดจากการดำเนินการทางตรรกะ เช่น AND, OR, NOT เป็นต้น ซึ่งการดำเนินการทางตรรกะจะมีตารางความจริง เป็นตัวบอกผลในการดำเนินการของตัวดำเนินการต่างๆ ดังตัวย่าง

### ตัวดำเนินการ AND

Y = A AND B

| A | B | Y |
|---|---|---|
| 0 | 0 | 0 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 1 |

### ตัวดำเนินการ OR

Y = A OR B

| A | B | Y |
|---|---|---|
| 0 | 0 | 0 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 1 |

### ตัวดำเนินการ NOT

Y = NOT A

| A | Y |
|--|--|
| 0 | 1 |
| 1 | 0 |

ตัวดำเนินการในภาษา C#
ใช้เครื่องหมายต่างๆ ดังต่อไปนี้

| การดำเนินการ | เครื่องหมาย |
|------------|-----------|
| Logical AND | & |
| Logical XOR | ^ |
| Logical OR | \| |

## 14. การเขียนโปรแกรมด้วยตัวดำเนินการทางตรรกะ

ตัวอย่างภาษา C# ต่อไปนี้เป็นการพิมพ์ตารางความจริงออกทางหน้าจอ
👉 ให้เขียนโปรแกรมต่อไปนี้

```csharp
bool A, B,Y;
Console.WriteLine("      Y = A AND B");
Console.WriteLine("-----------------------");
Console.WriteLine("   A      B\t|  Y");
Console.WriteLine("-----------------------");
A = false; B = false; Y = A & B;
Console.WriteLine(" {0}\t{1}\t| {2}", A,B,Y);
A = false; B = true; Y = A & B;
Console.WriteLine(" {0}\t{1}\t| {2}", A, B, Y);
A = true; B = false; Y = A & B;
Console.WriteLine(" {0}\t{1}\t| {2}", A, B, Y);
A = true; B = true; Y = A & B;
Console.WriteLine(" {0}\t{1}\t| {2}", A, B, Y);
Console.WriteLine("-----------------------");
```

➢ รันโปรแกรมและบันทึกผล<br>
![image](https://user-images.githubusercontent.com/115067018/233424058-32743cbe-8464-468e-8142-ce6e3f6920f2.png)

 
👷 จากจ้อ 14 ให้เขียนโปรแกรมเพื่อสร้างตารางความจริงของลอจิกดังต่อไปนี้

1. `AND`<br>
![image](https://user-images.githubusercontent.com/115067018/233424148-8c5091f2-de82-44d5-b601-4461d7ec8a1f.png)

2. `OR`<br>
![image](https://user-images.githubusercontent.com/115067018/233424229-29dd1eb5-c832-430c-a73b-62775c8a7023.png)

3. `NOT`<br>
![image](https://user-images.githubusercontent.com/115067018/233424283-5995779d-b882-4b79-b5b3-c1acb410826e.png)

4. `NAND`<br>
![image](https://user-images.githubusercontent.com/115067018/233424364-95446824-a963-4eb3-b2aa-ed14d0a12021.png)

5. `NOR`<br>
![image](https://user-images.githubusercontent.com/115067018/233424425-8e25248a-6a88-42e1-90b4-5ca0eb27ba8e.png)
6. `Exclusive OR`<br>
![image](https://user-images.githubusercontent.com/115067018/233424507-5c80d53c-754b-4114-9563-4b0fae9a5ea1.png)


## [ชนิดข้อมูลตัวเลขจำนวนเต็ม (Integer Types)](./Lab-01-part-15.md)
