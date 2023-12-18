# MVC pattern  

### MVC là gì
-	Được đưa ra bởi Trygve Reenskaug năm 1979: Model – view – controller (MVC) pattern for graphical user interface (GUI) software design.
-	Chia logic làm 3 phần:
1.	**Model**: chứa data, content hay logic xử lý của application
2.	**View**: gồm logic present – interact và format data (DTO)
3.	**Controller**: quản lý giao tiếp giữa model và view, giống như chứa một kịch bản cụ thể cho model và view:
      a.Lấy request data trên view  
      b.Convert request data  
      c.Call Model (call use case) truyền vào request data  
      d.Nhận response từ model, convert response data  
      e.Return response data cho view

### MVC trong 3 tier architecture

#### 3 tier architecture: một chuẩn chia logic và sắp xếp code
1.	**Presentation layer**
2.	**Business layer**:
      a.	Application logic: use case
      b.	Domain logic: gồm những định nghĩa, đối tượng được trừu tượng hóa, có thể dùng chung cho nhiều use case, chứa những nguyên tắc (rules) không thay đổi giữa các application khác nhau, chứa business logic
3.	**Data access layer**


Ứng dụng MVC trong swing

Tổng kết và ứng dụng