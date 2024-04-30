# Super Market Sales - Dashboard

📊 Thrilled to unveil my latest endeavour: a comprehensive Super Market Sales project focused on product sold and gross income meticulously crafted using Power BI and Microsoft Excel! 🚀

 ## Here's what you can expect from this dashboard:

🛠️ Toolkit: Power BI, Microsoft Excel

📊 Datasets: Microsoft Excel

Project Overview:

Diving deep into super market sales, this project revolves around dissecting sales performance and gross income, branch details with precision.

Here's what you can expect from this dashboard:

• Sliced date time stamps scroll through select the date we can have sales data for the particular date. 

• Product line and average rating of the product keeps changing according to the date.

• We can see the percentage of the Gender customers 

• Sales date wise – we can see the number of products sold during the particular time. 

• Branches sold highest profit that kind of time and highest sales. 

• We can see which product costs most and average of rating customers given to the products.

• Product quantity which is sold least and highest. Average of gross income and average quantity.

• Credit card details at the top of the list 

DAX : 
Highest Sold Product Line = CALCULATE(MAX('1 1 supermarket_sales - Sheet1'[Product line]),'1 1 supermarket_sales - Sheet1'[Quantity]=MAX('1 1 supermarket_sales - Sheet1'[Quantity]))

![Screenshot (21)](https://github.com/Mohanasundaram-Mohi/Super-Market-Sales-/assets/168515064/48d88c0d-4e11-406f-989d-0f54e50eb52f)



 
