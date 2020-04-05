#Lab 2 : การหาข้อมูล TAG

1. ค้นหาข้อมูลว่าแท็ก <!doctype> มีหน้าที่อะไร 
```
    <!doctype> คือประกาศว่าเอกสารเว็บนั้นสร้างขึ้นมา โดยยึดหลักตามมาตรใด 
    อย่างเช่น  - <!doctype html> เป็นมาตราฐานของ html
```

2. ถ้าอยากให้มี tooltip ใน Tag นั้นต้องใช้ Attribute ใด

```html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
    <title>lab2</title>
</head>
<body>
    <div>
        <h2>Tooltips</h2>
        <p class="w3-tooltip">โรคติดเชื้อไวรัสโคโรนาประเทศไทย(COVID-19) จำนวนผู้ติดเชื้อ<span class="w3-text w3-tag">(<em>2,169 คน update 06/04/2020</em>)</span></p>
    </div>
</body>
</html>

```

3. แท็ก <b>,<i> ต่างจาก <Strong>,<em> หรือไม่ อย่างไร
```
    แตกต่างกันในการใช้งานแต่ผลลัพธ์เหมือนกัน เช่น B ให้ผลลัพธ์เหมือนกับ Strong เราจะเลือกใช้แบบใดก็ได้ ให้ผลลัพท์เหมือนกันแต่อาจจะมีความหมายในการใช้งานที่ต่างกัน
    <b> = ตัวอักษรแบบตัวหนา (bold)
    <i> = ตัวอักษรแบบตัวเอน (italic)
    <em> = ใช้เน้นข้อความ คำพูดหรือวลี (emphasized)
    <Strong> = ใช้เน้นข้อความที่สำคัญมากๆ (strong)
```

4. หา Tag ที่สามารถแสดงข้อความกลับหลังได้

```html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
    <title>lab2</title>
</head>
<body>
    <div>
        <h2>Mr.Sapthawee Phetsai</h2>
        <p><bdo dir="rtl">Mr.Sapthawee Phetsai</bdo></p> 
    </div>
</body>
</html>

```