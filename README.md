### Flask Application Design

#### HTML Files

- `index.html`: The main landing page of the application that showcases the app's key features, including the convenience, variety, and freshness of the offered snacks, with a call-to-action encouraging users to download the app.
- `menu.html`: This page displays the entire menu of available snacks, categorized by type, with detailed descriptions and high-quality images. It includes options for filtering and searching for specific snacks.
- `cart.html`: Here, users can view the items they have added to their cart, review the total price, and proceed to checkout.
- `checkout.html`: This page collects the necessary shipping and payment information from the user before placing the order. It ensures secure payment options and clear communication of delivery timelines.

#### Routes

- `/`: Redirects to the `index.html` page.
- `/menu`: Serves the `menu.html` page, displaying the menu of snacks.
- `/cart`: Directs to the `cart.html` page, where users can manage their cart and proceed to checkout.
- `/checkout`: Serves the `checkout.html` page for order finalization.
- `/order-confirmation`: A backend endpoint that processes the order information, generates an order confirmation message, and redirects to a confirmation page.