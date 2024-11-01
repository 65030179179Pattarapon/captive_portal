# Example นี้มีชื่อว่า captive_portal
โดยการทำงานของ Example นี้คือทำให้ esp32 เป็น Captive Portal และเป็น Access Point โดยจะหน้าเข้าสู่ระบบกับอุปกรณ์ที่มาเชื่อมต่อ
# 
ขั้นตอนแรกเลือก Example
# ![image](https://github.com/user-attachments/assets/ef9952f9-8264-4747-895a-5cd63fbbac8f)
รันและbuildโปรแกรม
# ![Screenshot 2024-11-01 160935](https://github.com/user-attachments/assets/86154e97-9d77-4c8a-b232-842eea06e296)
เลือกเชื่อมกับ esp32_ssid
# ![image](https://github.com/user-attachments/assets/8cb62fec-5d28-471e-a42d-6df33a793878)
จะขึ้นหน้า root.html เมื่อนำอุปกรณ์เชื่อมต่อเข้าไปที่เครือข่าย
# ![image](https://github.com/user-attachments/assets/22d2d871-9952-4b70-acbf-cbfa8f44fe69)
# แก้ไขเพิ่มเติม
สามารถแก้ไขชื่อและรหัส Access Point โดยการกด menuconfig
# ![image](https://github.com/user-attachments/assets/85a7dce2-9d21-48d5-9068-396cffa7cb2b)
หา Example Configuration และเปลี่ยนตามต้องการแล้วกด save
# ![image](https://github.com/user-attachments/assets/e95b1b0e-55d7-4f5a-8084-1ddf0bbbb719)
และสามารถแก้ไขหน้า root.html ได้
# ![Screenshot 2024-11-01 164236](https://github.com/user-attachments/assets/d9060c90-73b4-4926-947b-9dc77eb4c90f)
รันและbuildโปรแกรม แล้วเชื่อมต่อจะได้หน้า root.html ที่แก้ใหม่
# ![image](https://github.com/user-attachments/assets/78d9adac-538c-4294-9576-a89728b31ed9)



