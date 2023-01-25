<!DOCTYPE html>
<html lang="en">
<head>
   
    <title>Payment Form</title> 
    <link rel="stylesheet" href="mypage.css">
</head>
<body>
    <div class="container">
        <form action="" method="">
            <h1 class="main_heading">Payment Form</h1>
            <hr>
            <h2>User Information</h2>
        
            <p>Name: 
                <input type="text" required name="name" placeholder="">
            </p>
            <p>
                 <fieldset>
                <legend>Gender</legend>
                Male <input type="radio" name="gender" id="male" value="M" required> Female<input type="radio" name="gender" id="Female" value="M" required> 
            </fieldset>
        </p>
        
            <p>
                Address:
                <textarea name="Enter your Address" id="address" cols="100" placeholder="address" rows="5"></textarea>
            </p>
            <p>
                Email :
                <input type="email" name="Email" id="email" placeholder="Enter your mail ">
            </p>
            <p>
                Pincode:
                <input type="number"  name="Pincode" id="Pincode" placeholder="">
            </p>
            <h2>Payment Information</h2>
            <p>Card Type:
                <select name="card_type" id="card_type" required>
                    <option value="">--Select Card Type--</option>
                    <option value="visa">visa</option>
                    <option value="Mastercard">Mastercard</option>
                    <option value="rupay">Rupay</option>
                    <option value="Debit">Debit</option>
                    <option value="Credit">Credit</option>
                    <option value="Paytm">Paytm</option>
                </select></p>
                <p4>
                    <img src="C:\Users\Uttam\Desktop\programming\Html,css\visa.jpg" alt="20" sizes="2px" >
                </p4>
                <p>
                    <p>Card Number : <input type="number" name="card_Number" id="card_Number" required> </p>
                    <p>Expiration Date :  <input type="date" name="Exp_date" id="Exp_date" required></p>
                    <p>CVV :  <input type="password" name="CVV" id="CVV" required></p>
                    <p><input type="submit" value="Pay Now"> <input type="reset" value="Reset"></p>

                </p>
        </form>
    </div>
</body>
</html>
