# Website1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PAYMENT GATEWAY</title>
    <link rel="stylesheet" href="style_payment_gatway.CSS">
</head>
<body>
    
    
    <div class="container">
    <form action="" method="get"></form>
    <h1 class="heading">PAYMENT GATEWAY</h1>
    <div a href=
    "website.html">
    <svg  xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-home"><path  d="M3 9l9-7 9 7v11a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2z"></path><polyline points="9 22 9 12 15 12 15 22"></polyline></svg></div>
    <hr>
    <h2>CONTACT INFORMATION</h2>
    <p>NAME: <input type="text" name="Name" required placeholder="HENRY BERNALD"></p>
    
    <fieldset>
        <legend> Gender</legend>
        <p> 
        Male <input type="radio" name="gender" id="Male">
        Female <input type="radio" name="gender" id="Female">
        Other <input type="radio" name="gender" id="Other">
    </p></fieldset>
    <p>Address:<textarea name="address" id="address" cols="100" rows="6" required placeholder="enter your address"></textarea></p>
    <p>Email: <input type="email" name="email" id="Email" required placeholder="abcdefg@hotmail.com"></p>
    <p>Pincode: <input type="number" name="pincode" id="pincode" required placeholder="000000"></p>
    <hr>
    <h2>PAYMENT INFORMATION</h2>
    <p>Select a Card: 
        <select name="card_type" id="card_type" required>
            <option value="" >--select a card--</option>
            <option value="Debit Card" >Debit Card</option>
            <option value="Credit Card" >Credit Card</option>
        </select>
    </p>
    <p>Card Number:<input type="number" name="Card number" id="Card Number" required placeholder="xxxx yyyy zzzz"></p>
    <p>Card Expiry date:<input type="date" name="Exp date" id="Exp date" required ></p>
    <p>CVV Number:<input type="password" name="CVV" id="CVV" required placeholder="***"></p>
    <input type="submit" value="Pay Now">
    </div>
   
</body>
</html>
#css file
*{
    box-sizing: border-box;
   
    font-family: Verdana, Geneva, Tahoma, sans-serif;
} 
body {
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    margin: 15px 30px;
    font-size: 17px;
    padding: 8px;
}
.container {
    background-color:#f2f2f2;
    padding: 5px 20px 15px 20px;
    border:1px solid lightgray;
    border-radius: 4px;
}
input[type="number"],
input[type="email"],
input[type="password"],
input[type="date"],
input[type="text"],
select,textarea{
    width: 100%;
    padding: 1px;
    border:1px solid #ccc;
    border-radius: 5px;
}
fieldset{
    border: 1px solid #ccc;
    background-color: white;
    border-radius: 4px;

}
.heading{text-align: center;

}
input[type="submit"] {
    background-color: #4daea1;
    border: none;
    padding: 12px 20px;
    border-radius: 4x;
    cursor: pointer;
    width: 80%;
    align-content: center;
    
}
input[type="submit"]:hover
{
    background-color: green;
    animation: ease;
}
svg {
align top: 4px;


}
