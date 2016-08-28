# Payment processing example: Lasso

This sample demonstrates processing card payments with Square Connect API
using Lasso Professional 9.

## Setup

Copy the files to any location within the web root.

### Provide required credentials

Both `/process_card.lasso` and `index.html` have values near the top of the
file that you need to replace with various credentials associated with your
application.

If you're just testing things out, it's recommended that you use your
_sandbox_ credentials for now. See
[this article](https://docs.connect.squareup.com/articles/using-sandbox/)
for more information on the API sandbox.

You can `grep` for `REPLACE_ME` to find all of the fields to replace.

## Running the sample

Visit `https://example.com/index.html` in your browser to see the card form.

If you're using your sandbox credentials, you can test a valid credit card
transaction by providing the following card information in the form:

* Card Number 4532 7597 3454 5858
* Card CVV 111
* Card Expiration (Any time in the future)
* Card Postal Code (Any valid US postal code)

**Note that if you are _not_ using your sandbox credentials and you enter
_real_ credit card information, YOU WILL CHARGE THE CARD.**
