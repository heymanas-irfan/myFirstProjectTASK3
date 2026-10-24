# myFirstProjectTASK3
<!DOCTYPE html>
<html>
<head>
    <title>Hotel Reservation Form</title>
    <style>
        body 
        {
            font-family: "Times New Roman", serif;
        }
        .container
        {
            width: 420px;
            margin: 30px auto;
            padding: 15px;
            background-color: lightgrey;
        }
        h1 
        {
            text-align: center;
            color: red;
        }
        table 
        {
            width: 100%;
            background-color: skyblue;
            border: 1px solid black;
            border-spacing: 2px;
        }
        td 
        {
            border: 1px solid gray;
            padding: 5px;
        }
        .label 
        {
            text-align: right;
            font-weight: bold;
            width: 115px;
        }
        input[type="text"],
        input[type="email"]
        {
            width: 180px;
            box-sizing: border-box;
        }
        .submit 
        {
            text-align: center;
        }
    </style>
</head>
<body>
<div class="container">
    <h1>Continental Hotel Reservation Form</h1>
    <form>

        <table>

            <tr>

                <td class="label">Name</td>

                <td>

                    <input type="text" placeholder="Enter your name">

                </td>

            </tr>

            <tr>

                <td class="label">eMail</td>

                <td>

                    <input type="email" value="info@continental.pk">

                </td>

            </tr>

            <tr>

                <td class="label">Mobile No</td>

                <td>

                    <input type="text" placeholder="Enter your cell number">

                </td>

            </tr>

            <tr>

                <td class="label">Arrival Time</td>

                <td>

                    <input type="text" placeholder="Enter your arrival time">

                </td>

            </tr>

            <tr>

                <td class="label">Departure</td>

                <td>

                    <input type="date">

                    <input type="time">

                </td>

            </tr>

            <tr>

                <td class="label">Room Type</td>

                <td>

                    <input type="radio" name="room">Single

                    <input type="radio" name="room">Double

                    <br>

                    <input type="radio" name="room">Presidential Suite

                </td>

            </tr>

            <tr>

                <td class="label">Preferences</td>

                <td>

                    <input type="checkbox">Non-Smoking

                    <br>

                    <input type="checkbox">Internet

                    <br>

                    <input type="checkbox">Firm Mattress

                </td>

            </tr>

            <tr>

                <td class="label">Mode of Payment</td>

                <td>

                    <input type="checkbox">Cash

                    <input type="checkbox">Check

                    <br>

                    <input type="checkbox">Credit Card

                    <select>

                        <option>Select Card</option>

                        <option>Visa</option>

                        <option>Mastercard</option>

                    </select>

                </td>

            </tr>

            <tr>

                <td colspan="2" class="submit">

                    <input type="submit" value="Send Data">

                </td>

            </tr>

        </table>

    </form>

</div>

</body>

</html>


