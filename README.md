# VISA-UI-CARD
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VISA Card</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    
    <div class="container">
        <div class="card">
            <div class="header">
                <div class="title">Payment Detail</div>
                <svg xmlns="http://www.w3.org/2000/svg" class="logo" width="140" height="43" viewBox="0 0 175.7 53.9">
                    <style>
                        .visa {
                            fill: #fff;
                        }
                    </style>
                    <path class="visa"
                        d="M61.9 53.1l8.9-52.2h14.2l-8.9 52.2zm65.8-50.9c-2.8-1.1-7.2-2.2-12.7-2.2-14.1 0-24 7.1-24 17.2-.1 7.5 7.1 11.7 12.5 14.2 5.5 2.6 7.4 4.2 7.4 6.5 0 3.5-4.4 5.1-8.5 5.1-5.7 0-8.7-.8-13.4-2.7l-2-.9-2 11.7c3.3 1.5 9.5 2.7 15.9 2.8 15 0 24.7-7 24.8-17.8.1-5.9-3.7-10.5-11.9-14.2-5-2.4-8-4-8-6.5 0-2.2 2.6-4.5 8.1-4.5 4.7-.1 8 .9 10.6 2l1.3.6 1.9-11.3M164.2 1h-11c-3.4 0-6 .9-7.5 4.3l-21.1 47.8h14.9s2.4-6.4 3-7.8h18.2c.4 1.8 1.7 7.8 1.7 7.8h13.2l-11.4-52.1m-17.5 33.6c1.2-3 5.7-14.6 5.7-14.6-.1.1 1.2-3 1.9-5l1 4.5s2.7 12.5 3.3 15.1h-11.9zm-96.7-33.7l-14 35.6-1.5-7.2c-2.5-8.3-10.6-17.4-19.6-21.9l12.7 45.7h15.1l22.4-52.2h-15.1" />
                    <path fill="#F7A600"
                        d="M23.1.9h-22.9l-.2 1.1c17.9 4.3 29.7 14.8 34.6 27.3l-5-24c-.9-3.3-3.4-4.3-6.5-4.4" />
                </svg>

            </div>
            <div class="content">
                <div class="row">
                    <label >Card Number</label>
                    <input type="text" class="card-number" placeholder="1234 1234 1234 1234">
                </div>
                <div class="row card-expire">
                    <div class="row card-expire-month">
                        <label >Month</label>
                        <input type="text" placeholder="April">
                    </div>
                    <div class="row card-expire-year">
                        <label >Year</label>
                        <input type="text" placeholder="2023">
                    </div>
                </div>
                <div class="row card-cvv">
                    <div class="row card-cvv">
                        <label >CVV</label>
                        <input type="text" placeholder="232">
                    </div>
                </div>
            </div>
        </div>
    </div>

</body>
</html>
