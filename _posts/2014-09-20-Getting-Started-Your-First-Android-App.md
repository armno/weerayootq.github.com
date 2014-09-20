---
layout: post
title: "Getting Started Your First Android App"
modified: 2014-09-20 16:44:14 +0700
tags: [Andriod Development]
image:
  feature: 
  credit: 
  creditlink: 
comments: 
share: 
---

Getting Start
=========

Android Application development process

  - Programing in JAVA, Design / Layout in XML
  - หลังจากจากการเขียนโปรแกรมต่างๆ แล้ว เราก็จะใช้เครื่องมือเพื่อที่จะ Build/Compile files ต่างของแอพพลิเคชัน เพื่อเป็นการรวมไฟล์ทุกอย่างอยู่ใน Package เดียวกันซึ่งไฟล์ที่ได้นั้นจะมีนามสกุลของไฟล์คือ .apk หลังจากได้ไฟล์ .apk เราก็สามารถที่จะนำแอพที่เราพัฒนาไป install ยังมือถือได้หรือแม้กระทั่ง submit กับ Google Play ต่อไป
  - ไฟล์ทุกไฟล์ที่ใช้สำหรับการพํมนาแอพพลิเคชันถูกจัดการโดย Integrated Dvelopment Enviroment (IDE)
  - โดยทั่วไปแล้ว IDE ที่ใช้สำหรับการพัฒนา Android แอพพลิเคชันจะใช้ Eclipse แต่ตอนนี้กำลังจะถูกแทนที่โดย Android Studio ซึ่งเป็นการพัฒนาจาก Google โดยตรง

Task
=========

 - Download & Install Android Studio
 - Set up testing on devices and emulators.
 - สร้าง Android แอพพลิเคชัน เพื่อแสดงขอความ "Hello World" บนจอภาพ


Installing Android Studio
---------------------
สิ่งสำคัญสิ่งหนึ่งก่อนการติดตั้ง Android Studio นั่นก็คือ Java Development Kit หรือ JDK เราสามารถทำการตรวจสอบได้ว่าเครื่องคอมพิวเตอร์ของเรานี้ได้มีการติดตั้ง JDK แล้วหรือไม่ ผ่านทาง Terminal โดยใช้คำสั่งดังนี้

```
java -version
```

หลังจากการรันคำสั่งข้างต้นแล้วถ้าเครื่องคอมพิวเตอร์ของเรามีการติดตั้ง JDK เป็นที่เรียบร้อยแล้วจะมีผลลัพท์ดังรูปต่อไปนี้

![Alt text](../images/android_part1_1.png)

ในกรณีที่ Terminal แสดงผมลัพท์ออกมาว่า "Command not found" แสดงว่าเครื่องคอมพิวเตอร์ของเรายังไม่ได้ทำการติดตั้ง JDK ดังนั้นต้องทำการติดตั้ง JDK ก่อนโดยสารมารถเข้าไป download ได้ตามลิงค์ต่อไปนี้ : [download the JDK] จาก Page ของ Oracle 

หลังจากติดตั้ง JDK เป็นที่เรียบร้อยเราจะไปยัง Page : [Android Studio Page] เพื่อทำการ Download Android Studio ที่มีเวอร์ชั่นและ System ที่ตรงกับเครื่องคอมพิวเตอร์ของแต่ละคน

![Alt text](../images/android_part1_2.png)

เมื่อเปิด Android Studio ขึ้นมาเราจะพบได้กับ Loading screen ดังรูปต่อไปนี้

![Alt text](../images/android_part1_3.png)

หลังจากนั้นจะพบกับ Welcome screen ดังรูปต่อไปนี้

![Alt text](../images/android_part1_4.png)

Creating Hello Android
---------------------
ใน section นี้เราจะได้เริ่มลงสร้างแอพพลิเคชัน "Hello World" โดยที่ตัวแอพพลิเคชันจะมีการใช้ชื่อของ User(หรือตัวเราเอง) มาสร้างเป็นข้อความต้อนรับและจะแสดงทุกครั้งที่ User ได้เข้าใช้งานแอพพลิเคชัน

 - ขั้นตอนที่ 1 สร้าง Project โดยทำการเลือกเมนู "New Project..." ในหน้า Welcome screen ดังรูป

![Alt text](../images/android_part1_5.jpg)

```
Note : ในกรณีที่มีการเปิด Android Studio ไว้อยู่ก่อนแล้วหรือ Welcome Screen ไม่ปรากฎ ให้ไปทีเมนูบาร์เลือก File/New Project เพื่อสร้าง Project
```

หลังจากนั้นจะพบกับจอภาพดังรูปต่อไปนี้

![Alt text](../images/android_part1_5.jpg)



[download the JDK]:http://www.oracle.com/technetwork/java/javase/downloads/index.html
[Android Studio Page]:https://developer.android.com/sdk/installing/studio.html

