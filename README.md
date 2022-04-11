# cocoMart
An Web application which deals with the marketing and production of coconut

Setting PSQL - https://www.digitalocean.com/community/tutorials/how-to-install-and-use-postgresql-on-ubuntu-20-04

Models

Users - Buyer & Seller
Products
UserActivity - order, cancel
Likes
Demands

Models:

User - First Name, Last name, email (optional), phone number, role, verification, address
Product - Title, categoty(Edible, `Fibre Products, Oil), quantity(kg, piece, litre), amount, image, product_address, lat, long
User Activity - user_id, product_id, quantity(kg, piece, litre), total_amount, paid_status, order_status(ordered, cancelled, delivered)
Likes - user_id, product_id
Demands - user_id, product_name(list out), preferred_location

Pages:

Sign Up/Sign In -> verification -> listing/dashboard
Listing -> search -> location / category
Listing -> Product Details -> Order Page -> Order Payment and Confirmation -> Your Order Page
Listing -> Product Details -> Like Icon -> Your Likes page
Dashboard -> Add product -> Product Details Page
Dashboard -> Product Detail -> Likes page
Dashboard -> Order Page with order_status
Listing -> Order Page with order_status
Listing -> Demand
Dashboard -> how their location is demanded?
