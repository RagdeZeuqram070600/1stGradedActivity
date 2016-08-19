# <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Shopping Calculator</title>
<!-- Edgar Marquez -->
</head>
<body>

    <form method="get" id="shoppingForm">



        <fieldset>
            <table border="1">

                <tr>
                    <td><label for="quantity"> Quantity</label></td>
                    <td><input type="number" name="quantity" id="quantity" value="1" min="1" required></td>
                </tr>

                <tr>
                    <td><label for="price">Price Per Unit</label></td>
                    <td><input type="text" name="price" id="price" value="1.00" required></td>
                </tr>

                <tr>
                    <td><label for="tax">Tax Rate(%)</label></td>
                    <td><input type="text" name="tax" id="tax" value="1.00" required></td>
                </tr>

                <tr>
                    <td><label for="discount">Discount</label></td>
                    <td><input type="text" name="discount" id="discount" value="0.00" required></td>
                </tr>

                <tr>
                    <td><label for="total">Total</label></td>
                    <td><input type="text" name="total" id="total" value="0.00" required></td>
                </tr>

                <tr>
                    <td align="right" colspan="2">
                        <input type="submit"
                               value="Calculate" id="submit">
                    </td>
                </tr>

            </table>
        </fieldset>

    </form>

</body>
</html>
