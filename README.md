## Coffee Shop Problem Design

### HTML Files

- **menu.html**: Displays the menu items and their prices.
- **order.html**: Allows users to create an order by selecting items from the menu.
- **confirmation.html**: Displays the order summary and provides payment options.
- **success.html**: Confirms successful payment and provides an order receipt.

### Routes

- **@app.route('/')**: Home page that redirects to the menu.
- **@app.route('/menu')**: Displays the menu (menu.html).
- **@app.route('/order', methods=['GET', 'POST'])**: Handles user orders (order.html).
- **@app.route('/confirmation', methods=['GET', 'POST'])**: Displays order summary and handles payment (confirmation.html).
- **@app.route('/success')**: Confirms payment and provides receipt (success.html).