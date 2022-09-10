# Bill-Prototype
A basic Bill Manager like in malls that is made using ReactJs, Bootstrap with use of Redux

# How to run
  1. Unzip the file named Bill on your device
  2. Open the terminal at the path of the file
  3. Run the command *npm i* that will install the required dependencies
  4. Run the command npm start and the website will be running
  
# IMPORTANT
.env file might be missing. So for that you need to:
  1. Go to src folder in Bill
  2. Create a file named .env
  3. Add the following data:  
    a.REACT_APP_COMPANY_NAME = Brain Mentors Project <br> 
    b.REACT_APP_PAYMENT_TYPE="CASH,PAYTM,PAYPAL,CREDIT CARD,SODEXO" <br>
    c.REACT_APP_TAX={"SGST":"0.15","CGST":"0.18"} <br>
    d.REACT_APP_CUSTOMER="Order_ID,Name,Payment,Mobile_No,Date,Tax" <br>
    e.REACT_APP_ITEM_NAME={"ItemName":"Value of Item"} <br>
    f.REACT_APP_TABLEHEAD="ItemCode,ItemName,Quantity,Amount,Rate,Tax,Total" <br>
  4. The pointers a,b,c,e can have changed values keeping format same making the app dynamic
  
# Limitations
  1.Integrate backend using Node.Js
