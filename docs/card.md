<style>
    table {
        border-collapse: collapse;
    }

    table,
    th,
    td {
        border: 1px solid black;
        font-family: Arial, Helvetica, sans-serif;
    }

    td,
    th {
        border: 1px solid #ddd;
        padding: 8px;
    }
    tr:hover {background-color: #ddd;}
</style>

<h3>Test Data for Card</h3>
<div style="overflow-x: scroll; border: 1px solid #cccccc">
    <table _ngcontent-c45="">
        <thead _ngcontent-c45="">
            <!---->
            <th _ngcontent-c45="" class="big-header" colspan="12">Request</th>
            <!---->
            <th _ngcontent-c45="" class="big-header" colspan="6">Response</th>
        </thead>
        <thead _ngcontent-c45="">
            <!---->
            <th _ngcontent-c45="" class="subheader key">Scenario</th>
            <th _ngcontent-c45="" class="subheader key">primaryAccountNumber</th>
            <th _ngcontent-c45="" class="subheader key">addressVerificationResults.street</th>
            <th _ngcontent-c45="" class="subheader key">addressVerificationResults.postalCode</th>
            <th _ngcontent-c45="" class="subheader key">cardExpiryDate</th>
            <th _ngcontent-c45="" class="subheader key">cardCvv2Value</th>
            <th _ngcontent-c45="" class="subheader key">acquiringBin</th>
            <th _ngcontent-c45="" class="subheader key">cardAcceptor.name</th>
            <th _ngcontent-c45="" class="subheader key">cardAcceptor.address.state</th>
            <th _ngcontent-c45="" class="subheader key">cardAcceptor.address.city</th>
            <th _ngcontent-c45="" class="subheader key">cardAcceptor.address.zipCode</th>
            <th _ngcontent-c45="" class="subheader key">cardAcceptor.address.country</th>
            <th _ngcontent-c45="" class="subheader key">transactionIdentifier</th>
            <th _ngcontent-c45="" class="subheader key">actionCode</th>
            <th _ngcontent-c45="" class="subheader key">approvalCode</th>
            <th _ngcontent-c45="" class="subheader key">responseCode</th>
            <th _ngcontent-c45="" class="subheader key">addressVerificationResults</th>
            <th _ngcontent-c45="" class="subheader key">cvv2ResultCode</th>
        </thead>
        <tbody _ngcontent-c45="">
            <!---->
            <tr _ngcontent-c45="">
                <!---->
                <td _ngcontent-c45="">API Validation Error: 3001. Expiration Date has invalid content or has expired.</td>
                <td _ngcontent-c45="">4957030420210454</td>
                <td _ngcontent-c45="">801 Metro Center Blv</td>
                <td _ngcontent-c45="">94404</td>
                <td _ngcontent-c45="">2015-10</td>
                <td _ngcontent-c45="">999</td>
                <td _ngcontent-c45="">408999 or 400171</td>
                <td _ngcontent-c45="">Visa Inc</td>
                <td _ngcontent-c45="">CA</td>
                <td _ngcontent-c45="">San Francisco</td>
                <td _ngcontent-c45="">94404</td>
                <td _ngcontent-c45="">USA</td>
                <td _ngcontent-c45=""></td>
                <td _ngcontent-c45=""></td>
                <td _ngcontent-c45=""></td>
                <td _ngcontent-c45=""></td>
                <td _ngcontent-c45=""></td>
                <td _ngcontent-c45=""></td>
            </tr>
            <tr _ngcontent-c45="">
                <!---->
                <td _ngcontent-c45="">Action Code - 00</td>
                <td _ngcontent-c45="">4957030420210454</td>
                <td _ngcontent-c45="">801 Metro Center Blv</td>
                <td _ngcontent-c45="">94404</td>
                <td _ngcontent-c45="">2020-10</td>
                <td _ngcontent-c45="">999</td>
                <td _ngcontent-c45="">408999 or 400171</td>
                <td _ngcontent-c45="">Visa Inc</td>
                <td _ngcontent-c45="">CA</td>
                <td _ngcontent-c45="">San Francisco</td>
                <td _ngcontent-c45="">94404</td>
                <td _ngcontent-c45="">USA</td>
                <td _ngcontent-c45="">Any Positive Integer (15 digit)</td>
                <td _ngcontent-c45="">00</td>
                <td _ngcontent-c45="">12AB54</td>
                <td _ngcontent-c45="">5</td>
                <td _ngcontent-c45="">Y</td>
                <td _ngcontent-c45="">M</td>
            </tr>
            <tr _ngcontent-c45="">
                <!---->
                <td _ngcontent-c45="">Invalid account number</td>
                <td _ngcontent-c45="">4957040000000001</td>
                <td _ngcontent-c45="">801 Metro Center Blv</td>
                <td _ngcontent-c45="">94404</td>
                <td _ngcontent-c45="">2020-10</td>
                <td _ngcontent-c45="">999</td>
                <td _ngcontent-c45="">408999 or 400171</td>
                <td _ngcontent-c45="">Visa Inc</td>
                <td _ngcontent-c45="">CA</td>
                <td _ngcontent-c45="">San Francisco</td>
                <td _ngcontent-c45="">94404</td>
                <td _ngcontent-c45="">USA</td>
                <td _ngcontent-c45="">Any Positive Integer (15 digit)</td>
                <td _ngcontent-c45="">25</td>
                <td _ngcontent-c45=""></td>
                <td _ngcontent-c45="">5</td>
                <td _ngcontent-c45="">I</td>
                <td _ngcontent-c45="">P</td>
            </tr>
            <tr _ngcontent-c45="">
                <!---->
                <td _ngcontent-c45="">Invalid Zip Code</td>
                <td _ngcontent-c45="">4895070000012123</td>
                <td _ngcontent-c45="">801 Metro Center Blv</td>
                <td _ngcontent-c45="">0</td>
                <td _ngcontent-c45="">2020-10</td>
                <td _ngcontent-c45="">999</td>
                <td _ngcontent-c45="">408999 or 400171</td>
                <td _ngcontent-c45="">Visa Inc</td>
                <td _ngcontent-c45="">CA</td>
                <td _ngcontent-c45="">San Francisco</td>
                <td _ngcontent-c45="">0</td>
                <td _ngcontent-c45="">USA</td>
                <td _ngcontent-c45="">Any Positive Integer (15 digit)</td>
                <td _ngcontent-c45=""></td>
                <td _ngcontent-c45=""></td>
                <td _ngcontent-c45=""></td>
                <td _ngcontent-c45="">N/A</td>
                <td _ngcontent-c45="">N/A</td>
            </tr>
            <tr _ngcontent-c45="">
                <!---->
                <td _ngcontent-c45="">Invalid Zip Code and CVV2 values</td>
                <td _ngcontent-c45="">4957030420210488 </td>
                <td _ngcontent-c45="">900 Metro Center Blv</td>
                <td _ngcontent-c45="">94402</td>
                <td _ngcontent-c45="">2020-10</td>
                <td _ngcontent-c45="">227</td>
                <td _ngcontent-c45="">408999 or 400171</td>
                <td _ngcontent-c45="">Visa Inc</td>
                <td _ngcontent-c45="">CA</td>
                <td _ngcontent-c45="">San Francisco</td>
                <td _ngcontent-c45="">94402</td>
                <td _ngcontent-c45="">USA</td>
                <td _ngcontent-c45="">Any Positive Integer (15 digit)</td>
                <td _ngcontent-c45="">N7</td>
                <td _ngcontent-c45=""></td>
                <td _ngcontent-c45="">5</td>
                <td _ngcontent-c45="">A</td>
                <td _ngcontent-c45="">N</td>
            </tr>
            <tr _ngcontent-c45="">
                <!---->
                <td _ngcontent-c45="">Invalid CVV2 value</td>
                <td _ngcontent-c45="">4957030420210496 </td>
                <td _ngcontent-c45="">900 Metro Center Blv</td>
                <td _ngcontent-c45="">94404</td>
                <td _ngcontent-c45="">2020-10</td>
                <td _ngcontent-c45="">664</td>
                <td _ngcontent-c45="">408999 or 400171</td>
                <td _ngcontent-c45="">Visa Inc</td>
                <td _ngcontent-c45="">CA</td>
                <td _ngcontent-c45="">San Francisco</td>
                <td _ngcontent-c45="">94404</td>
                <td _ngcontent-c45="">USA</td>
                <td _ngcontent-c45="">Any Positive Integer (15 digit)</td>
                <td _ngcontent-c45="">N7</td>
                <td _ngcontent-c45=""></td>
                <td _ngcontent-c45="">5</td>
                <td _ngcontent-c45="">Y</td>
                <td _ngcontent-c45="">N</td>
            </tr>
            <tr _ngcontent-c45="">
                <!---->
                <td _ngcontent-c45="">Invalid Address,Zip code and CVV2 values</td>
                <td _ngcontent-c45="">4957030420210504</td>
                <td _ngcontent-c45="">901 Metro Center Blv</td>
                <td _ngcontent-c45="">94404</td>
                <td _ngcontent-c45="">2020-10</td>
                <td _ngcontent-c45="">322</td>
                <td _ngcontent-c45="">408999 or 400171</td>
                <td _ngcontent-c45="">Visa Inc</td>
                <td _ngcontent-c45="">CA</td>
                <td _ngcontent-c45="">San Francisco</td>
                <td _ngcontent-c45="">94404</td>
                <td _ngcontent-c45="">USA</td>
                <td _ngcontent-c45="">Any Positive Integer (15 digit)</td>
                <td _ngcontent-c45="">N7</td>
                <td _ngcontent-c45=""></td>
                <td _ngcontent-c45="">5</td>
                <td _ngcontent-c45="">Z</td>
                <td _ngcontent-c45="">N</td>
            </tr>
            <tr _ngcontent-c45="">
                <!---->
                <td _ngcontent-c45="">Invalid Address,Zip code and CVV2 values</td>
                <td _ngcontent-c45="">4957030420210512 </td>
                <td _ngcontent-c45="">901 Metro Center Blv</td>
                <td _ngcontent-c45="">94404</td>
                <td _ngcontent-c45="">2020-10</td>
                <td _ngcontent-c45="">899</td>
                <td _ngcontent-c45="">408999 or 400171</td>
                <td _ngcontent-c45="">Visa Inc</td>
                <td _ngcontent-c45="">CA</td>
                <td _ngcontent-c45="">San Francisco</td>
                <td _ngcontent-c45="">94404</td>
                <td _ngcontent-c45="">USA</td>
                <td _ngcontent-c45="">Any Positive Integer (15 digit)</td>
                <td _ngcontent-c45="">N7</td>
                <td _ngcontent-c45=""></td>
                <td _ngcontent-c45="">5</td>
                <td _ngcontent-c45="">Z</td>
                <td _ngcontent-c45="">N</td>
            </tr>
            <tr _ngcontent-c45="">
                <!---->
                <td _ngcontent-c45="">Action Code - 00</td>
                <td _ngcontent-c45="">4957030420210462</td>
                <td _ngcontent-c45="">900 Metro Center Blv</td>
                <td _ngcontent-c45="">94404</td>
                <td _ngcontent-c45="">2020-10</td>
                <td _ngcontent-c45="">022</td>
                <td _ngcontent-c45="">408999 or 400171</td>
                <td _ngcontent-c45="">Visa Inc</td>
                <td _ngcontent-c45="">CA</td>
                <td _ngcontent-c45="">San Francisco</td>
                <td _ngcontent-c45="">94404</td>
                <td _ngcontent-c45="">USA</td>
                <td _ngcontent-c45="">Any Positive Integer (15 digit)</td>
                <td _ngcontent-c45="">00</td>
                <td _ngcontent-c45="">12AB54</td>
                <td _ngcontent-c45="">5</td>
                <td _ngcontent-c45="">Y</td>
                <td _ngcontent-c45="">M</td>
            </tr>
            <tr _ngcontent-c45="">
                <!---->
                <td _ngcontent-c45="">Action Code - 00</td>
                <td _ngcontent-c45="">4957030420210470 </td>
                <td _ngcontent-c45="">900 Metro Center Blv</td>
                <td _ngcontent-c45="">94404</td>
                <td _ngcontent-c45="">2020-10</td>
                <td _ngcontent-c45="">022</td>
                <td _ngcontent-c45="">408999 or 400171</td>
                <td _ngcontent-c45="">Visa Inc</td>
                <td _ngcontent-c45="">CA</td>
                <td _ngcontent-c45="">San Francisco</td>
                <td _ngcontent-c45="">94404</td>
                <td _ngcontent-c45="">USA</td>
                <td _ngcontent-c45="">Any Positive Integer (15 digit)</td>
                <td _ngcontent-c45="">00</td>
                <td _ngcontent-c45="">12AB54</td>
                <td _ngcontent-c45="">5</td>
                <td _ngcontent-c45="">Y</td>
                <td _ngcontent-c45="">M</td>
            </tr>
            <tr _ngcontent-c45="">
                <!---->
                <td _ngcontent-c45="">Action Code - 00</td>
                <td _ngcontent-c45="">4957030420210488 </td>
                <td _ngcontent-c45="">900 Metro Center Blv</td>
                <td _ngcontent-c45="">94404</td>
                <td _ngcontent-c45="">2020-10</td>
                <td _ngcontent-c45="">022</td>
                <td _ngcontent-c45="">408999 or 400171</td>
                <td _ngcontent-c45="">Visa Inc</td>
                <td _ngcontent-c45="">CA</td>
                <td _ngcontent-c45="">San Francisco</td>
                <td _ngcontent-c45="">94404</td>
                <td _ngcontent-c45="">USA</td>
                <td _ngcontent-c45="">Any Positive Integer (15 digit)</td>
                <td _ngcontent-c45="">00</td>
                <td _ngcontent-c45="">12AB54</td>
                <td _ngcontent-c45="">5</td>
                <td _ngcontent-c45="">Y</td>
                <td _ngcontent-c45="">M</td>
            </tr>
            <tr _ngcontent-c45="">
                <!---->
                <td _ngcontent-c45="">Action Code - 00</td>
                <td _ngcontent-c45="">4957030420210496</td>
                <td _ngcontent-c45="">900 Metro Center Blv</td>
                <td _ngcontent-c45="">94404</td>
                <td _ngcontent-c45="">2020-10</td>
                <td _ngcontent-c45="">022</td>
                <td _ngcontent-c45="">408999 or 400171</td>
                <td _ngcontent-c45="">Visa Inc</td>
                <td _ngcontent-c45="">CA</td>
                <td _ngcontent-c45="">San Francisco</td>
                <td _ngcontent-c45="">94404</td>
                <td _ngcontent-c45="">USA</td>
                <td _ngcontent-c45="">Any Positive Integer (15 digit)</td>
                <td _ngcontent-c45="">00</td>
                <td _ngcontent-c45="">12AB54</td>
                <td _ngcontent-c45="">5</td>
                <td _ngcontent-c45="">Y</td>
                <td _ngcontent-c45="">M</td>
            </tr>
            <tr _ngcontent-c45="">
                <!---->
                <td _ngcontent-c45="">Action Code - 00</td>
                <td _ngcontent-c45="">4957030420210504</td>
                <td _ngcontent-c45="">900 Metro Center Blv</td>
                <td _ngcontent-c45="">94404</td>
                <td _ngcontent-c45="">2020-10</td>
                <td _ngcontent-c45="">022</td>
                <td _ngcontent-c45="">408999 or 400171</td>
                <td _ngcontent-c45="">Visa Inc</td>
                <td _ngcontent-c45="">CA</td>
                <td _ngcontent-c45="">San Francisco</td>
                <td _ngcontent-c45="">94404</td>
                <td _ngcontent-c45="">USA</td>
                <td _ngcontent-c45="">Any Positive Integer (15 digit)</td>
                <td _ngcontent-c45="">00</td>
                <td _ngcontent-c45="">12AB54</td>
                <td _ngcontent-c45="">5</td>
                <td _ngcontent-c45="">Y</td>
                <td _ngcontent-c45="">M</td>
            </tr>
            <tr _ngcontent-c45="">
                <!---->
                <td _ngcontent-c45="">Action Code - 00</td>
                <td _ngcontent-c45="">4957030420210512</td>
                <td _ngcontent-c45="">900 Metro Center Blv</td>
                <td _ngcontent-c45="">94404</td>
                <td _ngcontent-c45="">2020-10</td>
                <td _ngcontent-c45="">022</td>
                <td _ngcontent-c45="">408999 or 400171</td>
                <td _ngcontent-c45="">Visa Inc</td>
                <td _ngcontent-c45="">CA</td>
                <td _ngcontent-c45="">San Francisco</td>
                <td _ngcontent-c45="">94404</td>
                <td _ngcontent-c45="">USA</td>
                <td _ngcontent-c45="">Any Positive Integer (15 digit)</td>
                <td _ngcontent-c45="">00</td>
                <td _ngcontent-c45="">12AB54</td>
                <td _ngcontent-c45="">5</td>
                <td _ngcontent-c45="">Y</td>
                <td _ngcontent-c45="">M</td>
            </tr>
            <tr _ngcontent-c45="">
                <!---->
                <td _ngcontent-c45="">Action Code - 00</td>
                <td _ngcontent-c45="">4895142232120006</td>
                <td _ngcontent-c45="">900 Metro Center Blv</td>
                <td _ngcontent-c45="">94404</td>
                <td _ngcontent-c45="">2020-10</td>
                <td _ngcontent-c45="">022</td>
                <td _ngcontent-c45="">408999 or 400171</td>
                <td _ngcontent-c45="">Visa Inc</td>
                <td _ngcontent-c45="">CA</td>
                <td _ngcontent-c45="">San Francisco</td>
                <td _ngcontent-c45="">94404</td>
                <td _ngcontent-c45="">USA</td>
                <td _ngcontent-c45="">Any Positive Integer (15 digit)</td>
                <td _ngcontent-c45="">00</td>
                <td _ngcontent-c45="">12AB54</td>
                <td _ngcontent-c45="">5</td>
                <td _ngcontent-c45="">Y</td>
                <td _ngcontent-c45="">M</td>
            </tr>
            <tr _ngcontent-c45="">
                <!---->
                <td _ngcontent-c45="">Action Code - 00</td>
                <td _ngcontent-c45="">4895070000007685</td>
                <td _ngcontent-c45="">900 Metro Center Blv</td>
                <td _ngcontent-c45="">94404</td>
                <td _ngcontent-c45="">2020-10</td>
                <td _ngcontent-c45="">022</td>
                <td _ngcontent-c45="">408999 or 400171</td>
                <td _ngcontent-c45="">Visa Inc</td>
                <td _ngcontent-c45="">CA</td>
                <td _ngcontent-c45="">San Francisco</td>
                <td _ngcontent-c45="">94404</td>
                <td _ngcontent-c45="">USA</td>
                <td _ngcontent-c45="">Any Positive Integer (15 digit)</td>
                <td _ngcontent-c45="">00</td>
                <td _ngcontent-c45="">12AB54</td>
                <td _ngcontent-c45="">5</td>
                <td _ngcontent-c45="">Y</td>
                <td _ngcontent-c45="">M</td>
            </tr>
            <tr _ngcontent-c45="">
                <!---->
                <td _ngcontent-c45="">Action Code - 00</td>
                <td _ngcontent-c45="">4895070000006687</td>
                <td _ngcontent-c45="">900 Metro Center Blv</td>
                <td _ngcontent-c45="">94404</td>
                <td _ngcontent-c45="">2020-10</td>
                <td _ngcontent-c45="">022</td>
                <td _ngcontent-c45="">408999 or 400171</td>
                <td _ngcontent-c45="">Visa Inc</td>
                <td _ngcontent-c45="">CA</td>
                <td _ngcontent-c45="">San Francisco</td>
                <td _ngcontent-c45="">94404</td>
                <td _ngcontent-c45="">USA</td>
                <td _ngcontent-c45="">Any Positive Integer (15 digit)</td>
                <td _ngcontent-c45="">00</td>
                <td _ngcontent-c45="">12AB54</td>
                <td _ngcontent-c45="">5</td>
                <td _ngcontent-c45="">Y</td>
                <td _ngcontent-c45="">M</td>
            </tr>
            <tr _ngcontent-c45="">
                <!---->
                <td _ngcontent-c45="">Action Code - 00</td>
                <td _ngcontent-c45="">4895070000005671</td>
                <td _ngcontent-c45="">900 Metro Center Blv</td>
                <td _ngcontent-c45="">94404</td>
                <td _ngcontent-c45="">2020-10</td>
                <td _ngcontent-c45="">022</td>
                <td _ngcontent-c45="">408999 or 400171</td>
                <td _ngcontent-c45="">Visa Inc</td>
                <td _ngcontent-c45="">CA</td>
                <td _ngcontent-c45="">San Francisco</td>
                <td _ngcontent-c45="">94404</td>
                <td _ngcontent-c45="">USA</td>
                <td _ngcontent-c45="">Any Positive Integer (15 digit)</td>
                <td _ngcontent-c45="">00</td>
                <td _ngcontent-c45="">12AB54</td>
                <td _ngcontent-c45="">5</td>
                <td _ngcontent-c45="">Y</td>
                <td _ngcontent-c45="">M</td>
            </tr>
            <tr _ngcontent-c45="">
                <!---->
                <td _ngcontent-c45="">Action Code - 00</td>
                <td _ngcontent-c45="">4895070000004674</td>
                <td _ngcontent-c45="">900 Metro Center Blv</td>
                <td _ngcontent-c45="">94404</td>
                <td _ngcontent-c45="">2020-10</td>
                <td _ngcontent-c45="">022</td>
                <td _ngcontent-c45="">408999 or 400171</td>
                <td _ngcontent-c45="">Visa Inc</td>
                <td _ngcontent-c45="">CA</td>
                <td _ngcontent-c45="">San Francisco</td>
                <td _ngcontent-c45="">94404</td>
                <td _ngcontent-c45="">USA</td>
                <td _ngcontent-c45="">Any Positive Integer (15 digit)</td>
                <td _ngcontent-c45="">00</td>
                <td _ngcontent-c45="">12AB54</td>
                <td _ngcontent-c45="">5</td>
                <td _ngcontent-c45="">Y</td>
                <td _ngcontent-c45="">M</td>
            </tr>
            <tr _ngcontent-c45="">
                <!---->
                <td _ngcontent-c45="">Action Code - 00</td>
                <td _ngcontent-c45="">4895070000003551</td>
                <td _ngcontent-c45="">900 Metro Center Blv</td>
                <td _ngcontent-c45="">94404</td>
                <td _ngcontent-c45="">2020-10</td>
                <td _ngcontent-c45="">022</td>
                <td _ngcontent-c45="">408999 or 400171</td>
                <td _ngcontent-c45="">Visa Inc</td>
                <td _ngcontent-c45="">CA</td>
                <td _ngcontent-c45="">San Francisco</td>
                <td _ngcontent-c45="">94404</td>
                <td _ngcontent-c45="">USA</td>
                <td _ngcontent-c45="">Any Positive Integer (15 digit)</td>
                <td _ngcontent-c45="">00</td>
                <td _ngcontent-c45="">12AB54</td>
                <td _ngcontent-c45="">5</td>
                <td _ngcontent-c45="">Y</td>
                <td _ngcontent-c45="">M</td>
            </tr>
        </tbody>
    </table>
</div>
