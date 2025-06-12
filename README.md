**รหัสโครงงาน:** 67-1_29_wdp-r1

**ชื่อโครงงาน (ไทย):** การศึกษาอุปกรณ์บันทึกชีวิตและแพลตฟอร์มสำหรับจัดเก็บข้อมูลเวอร์ชัน 2

**Project Title (Eng):** Towards an Affordable Life Logging Device and Open Data Platform Version 2 

**อาจารย์ที่ปรึกษาโครงงาน:** ผู้ช่วยศาสตราจารย์ ดร.วนิดา พฤทธิวิทยา

**ผู้จัดทำโครงงาน:**
1. นายชญานนท์ ขันฤทธิ์  chayanon.kha@dome.tu.ac.th

Manual / Instructions
# โครงสร้างโฟลเดอร์ย่อย (directory tree)

**ใน Repository นี้มีโครงสร้างของโฟลเดอร์ดังนี้ :**

1. โฟลเดอร์ **final_reports** เป็นโฟลเดอร์รวบรวมเอกสารของโครงงาน ได้แก่
   * 67-2_CS403_67-1_29_wdp-r1.pdf
   * 67-2_CS403_67-1_29_wdp-r1_abstract_en.txt
   * 67-2_CS403_67-1_29_wdp-r1_abstract_th.txt
2. โฟลเดอร์ **[demo]()**  มีวีดีโอแสดงขั้นตอนการติดตั้งและใช้งานโปรแกรม
3. โฟลเดอร์ **[Arduino/reconnectiot](https://github.com/ComSciThammasatU/2567-2-cs403-final-submission-67-1_29_wdp-r1/tree/main/Arduino/reconnectiot)** เป็นโฟลเดอร์ที่บรรจุโค้ดของโปรแกรมสำหรับเบิร์นลงไปยังอุปกรณ์ IoT
4. โฟลเดอร์ **[AndroidApp/FaceRecognitionImages](https://github.com/ComSciThammasatU/2567-2-cs403-final-submission-67-1_29_wdp-r1/tree/main/AndroidApp/FaceRecognitionImages)** เป็นโฟลเดอร์ที่บรรจุโปรแกรม Android application สำหรับใช้งานในโทรศัพท์เคลื่อนที่
5. โฟลเดอร์ **[WebApp](https://github.com/ComSciThammasatU/2567-2-cs403-final-submission-67-1_29_wdp-r1/tree/main/WebApp)** เป็นโฟลเดอร์ที่บรรจุ Web application
6. ไฟล์ **[cloudformationTemplate.yml](https://github.com/ComSciThammasatU/2567-2-cs403-final-submission-67-1_29_wdp-r1/blob/main/cloudformationTemplate.yml)** เป็นไฟล์ yaml สำหรับสร้าง Template ใน Amazon Cloudformation

# ขั้นตอนการติดตั้งโปรแกรม
## จัดเตรียมโปรแกรมที่จำเป็น
1. ติดตั้งโปรแกรม **Arduino IDE เวอร์ชัน 2.0.2** สำหรับเบิร์นโค้ดลงไปยังอุปกรณ์ IoT
2. ติดตั้งโปรแกรม **Android Studio เวอร์ชัน Ladybug | 2024.2.1** สำหรับรันโค้ด Andriod application และใช้งาน Andriod Emulator
3. ติดตั้งโปรแกรม **Visual Studio Code** สำหรับรันโปรแกรม Web application
4. สมัครใช้งานและสร้างบัญชี AWS (Amazon Web Service) สำหรับสร้างเซอร์วิสต่าง ๆ
   * สร้าง Users ในเซอร์วิส Identity and Access Management (IAM)
   * สร้าง Access keys และกำหนด Permission ให้ Users ที่สร้าง จากนั้นบันทึก `accessKeyId` และ `secretAccessKey` ไว้

## ขั้นตอนการติดตั้งโปรแกรมของโครงงาน

# Topic 3
