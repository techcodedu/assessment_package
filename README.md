
**Project Title: Kiosk for an Online Store**

## System Requirements

* **Database:** Create a relational database with the following tables:
    * `orders`
    * `order_details`
    * `products`

## Index Page

* **Product Display:** All products are listed on the index page. Each product should have:
    * **Image:** A clear and representative image.
    * **Order Now Button:** An easily identifiable button to initiate the ordering process.
    * **Product Information:**
        * Name
        * Price (including unit)
    * **Image Modal:** Clicking the image opens a modal window with a larger image.

## Order Form Modal

* **Product Details:**
    * Product Name (pre-filled)
    * Quantity (adjustable input field)
    * Total Price (calculated in real-time based on quantity)
* **Real-time Price Calculation:** The total price automatically updates as the user changes the quantity.
* **Submit Button:** Saves the order to the database.

## Orders Page

* **Order Listing:** A dedicated page displays all placed orders. Consider including:
    * Order ID
    * Customer Name (if applicable)
    * Products Ordered (with quantity and price)
    * Total Order Amount
    * Order Status (pending, confirmed, shipped, etc.)
