countries to consider 
- irealand 
- austrailia 
- UK 
- netherland 


[[cyber security in austrailia]]




question to ask about coding challenge : 

As you complete each challenge, submit the source code for that challenge  
before continuing with the next one
You can submit results multiple times.
- theo ý này là em có thể submit nhiều lần dưới cái form mà để bài đưa phải không chị ? nếu có thì em submit mấy phần lý thuyết  để dưới định dạng  word được không chị ? 
- file của em có cần phải để ở định dạng gì như q1 hay q2 để người chấm dễ hiểu thêm không
Design a relational database to store all the information contained in the above  image  
- em có cần phải vẽ diagram không cho phần này hay mình chỉ cần ra ý tưởng và phần nộp chủ yếu là code với workflow diagram
Design the rest APIs to retrieve full of information in the image and store information  when the user makes the order and checkout.
- em có cần phải vẽ diagram không cho phần này hay mình chỉ cần ra ý tưởng và phần nộp chủ yếu là code với workflow diagram
Screenshots of running results must be attached in your email 
- cái này là em phải chạy code xong , screenshoot gắn reply vào email gửi TECHNICAL ASSESSMENT phải không ?  


database design  : 
Based on the information you provided, here are the entities and their relationships for the e-commerce site:

1. **User**: This entity represents the customers who use the e-commerce site. It can have attributes like `UserID`, `UserName`, `UserEmail`, etc.
    
2. **Product**: This entity represents the products available on the site. It can have attributes like `ProductID`, `ProductName`, `ProductCategory`, `ProductPrice`, etc.
    
3. **Category**: This entity represents the categories under which products are organized. It can have attributes like `CategoryID`, `CategoryName`, etc.
    
4. **Admin**: This entity represents the administrators who manage the site. It can have attributes like `AdminID`, `AdminName`, `AdminEmail`, etc.
    
5. **Store**: This entity represents other stores whose product numbers can be tracked. It can have attributes like `StoreID`, `StoreName`, `StoreLocation`, etc.
    
6. **Voucher**: This entity represents the vouchers that users can apply to reduce cost. It can have attributes like `VoucherID`, `VoucherDiscount`, `VoucherExpiryDate`, etc.
    
7. **Order**: This entity represents the orders placed by users. It can have attributes like `OrderID`, `UserID`, `OrderDate`, `TotalAmount`, etc.
    
8. **OrderDetail**: This entity represents the details of each order. It can have attributes like `OrderID`, `ProductID`, `Quantity`, `Price`, etc.


where does the relationship between admin and order should the admin have the ability to change the order but does it relate to erd ? 




Here are the relationships:

- **User** can place many **Orders**. Each **Order** is placed by one **User**.
- Each **Order** can have many **OrderDetails**. Each **OrderDetail** belongs to one **Order**.
- Each **OrderDetail** is associated with one **Product**. Each **Product** can be in many **OrderDetails**.
- Each **Product** belongs to one **Category**. Each **Category** can have many **Products**.
- Each **Product** can be in many **Stores**. Each **Store** can have many **Products**.
- Each **User** can apply many **Vouchers**. Each **Voucher** can be applied by many **Users**.
- Each **Admin** can customize the discount of many **Products**. Each **Product** can have its discount customized by one **Admin**.

Please note that this is a basic design and might need to be adjusted based on specific business rules and requirements. For example, if a product can belong to multiple categories or if a voucher can only be used once by a user, the design would need to be updated accordingly. Also, this design assumes that each store has all the products. If that’s not the case, a `ProductStore` table might be needed to keep track of which products are available in which stores.


# immigration 

# Canada 
What other countries are there that are somewhat lenient and not so popular to migrate to either via work or student?
With the many changes in Canada’s rules now, they are INDIRECTLY saying, “we’re done with immigrants.”
Does anyone know if there’s a particular country in Europe where you could still bring your spouse if you work or study and possibly get PR someday?
For context: My spouse and I are both in the engineering industry. We also do not want to ask for help or burden relatives when it comes to migrating. In terms of money, we can also pay placement agencies if it comes to that (any recommendations?)
Canada dream no more.


[[Australia]]