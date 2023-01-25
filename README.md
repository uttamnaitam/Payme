<!DOCTYPE html>
<html lang="en">
<head>
<style>
   
    <title>Payment Form</title> 
   *{
    box-sizing: bor;
}
body {
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    margin: 15px 30px;
    font-size: 17px;
    padding: 8px;
}
.main_heading {
    text-align: center;
}
.container {
    background-color: #fff;
    padding: 50px;
    border: 1px solid lightblue;
    border-radius: 5px;
}

input[type="text"],
input[type="Email"],
input[type="number"],
input[type="password"],
input[type="date"],
select,
textarea {
    width:50pc;
    padding: 12px;
    border: 1px solid rgb(110, 92, 92);
    border-radius:4px ;

}
fieldset {
    background-color: #fff;
    border: 1px 2px 2px 2px solid #ccc;
    
}

input[type="submit"] {
    background-color: rgb(93, 75, 75);
    color: white;
    padding: 12px 20px;
    border: none;
    box-sizing: 50px;
    border-radius: 4px;
    cursor: pointer;
    }
input:hover[type="submit"]{
    background-color: rgb(230, 39, 33);
    color: white;
    padding: 12px 20px;
    border: none;
    box-sizing: 50px;
    border-radius: 4px;
    cursor: pointer;

}
img {
    width: 100px;
    align-self: flex-start;
}
CVV {
    width: 50px;
    box-sizing: 20px;
}
</style>
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
