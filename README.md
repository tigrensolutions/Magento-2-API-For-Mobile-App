# Magento 2 API For Mobile App
Unquestionably, the number of mobile users today is rising dramatically, which is even greater than the number of desktop users in some countries. Most Magento store owners have realized this trend and developed mobile apps to attract their customers. In general, it will take months for the app development, regardless of native apps or hybrid apps, in which developing API might consume the most time. By using our ready-to-use Magento 2 API for Mobile App, the developers will not only save significant effort for the development but also be able to deliver the app to the store in the shortest turnaround time.

<h2> Magento 2 For Mobile App = GraphQL (Pros) + REST (Pros) + SOAP (Pros)</h2>
When it comes to Magento 2 API, most of us will think about GraphQL, REST, and SOAP. 
As you probably know, each of them has certain pros and cons, that’s why we combined all three solutions to create the best Magento 2 API for Mobile App.

![magento-api-for-mobile-app-1024x558](https://user-images.githubusercontent.com/26241389/162139087-26efa4a3-2999-4cf9-bcaa-3ce59132a45f.png)

<h3> 1. SOAP (Simple Object Access Protocol)</h3>
Released in 1998, SOAP is the most long-standing web service access protocol, developed by Microsoft.

<p dir="auto"></p><strong>Pros:</strong></p>

SOAP defines a standard communication protocol specification for XML-based message exchange using different transport protocols such as HTTP and SMTP. It’s straightforward to tunnel across firewalls and proxies without any modifications to the SOAP protocol.

SOAP is often applied for enterprise-level web services that require high security or complex transactions. E.g.: APIs for financial services, payment gateways, CRM, identity management, telecommunication, etc.

<p dir="auto"></p><strong>Cons:</strong></p>

SOAP might be complicated for beginners, especially when debugging. Also, it requires more bandwidth and large resources which, in turn, slow down the page load speed.

<h3> 2. REST (Representational State Transfer)</h3>
REST APIs were created with the aim of overcoming SOAP’s constraints. It is not a protocol but an architectural style that defines a set of recommendations for designing loosely coupled applications that use HTTP for data transmission.

<p dir="auto"></p><strong>Pros:</strong></p>
REST has a flexible architecture, which allows different messaging formats, such as HTML, JSON, XML, and plain text, while SOAP only allows XML.

REST is lightweight, which is more valuable in the mobile era when a few seconds in page load time means a lot.

<p dir="auto"><strong>Cons:</strong></p>
Accessing data by using REST APIs often requires multiple round-trips to collect all of the things we need.

Moreover, REST requests always return the full set of data, there is no way to limit the request to only retrieve a subset of data fields.

<h3> 3. GraphQL</h3>
GraphQL is the newcomer to the block, a revolutionary way to think about Magento APIs. Like REST, GraphQL is an API design architecture, but with a different approach that is more flexible. It’s true to say that GraphQL can solve an array of weaknesses and inefficiencies when interacting with REST.

<p dir="auto"></p><strong>Pros:</strong></p>
In GraphQL, everything is regarded as a graph and connected with each other. This means that you can tailor the request to your exact needs and describe what you want to get as an answer. In other words, you will be able to specify which fields are included to limit the response to the data which is needed to get exactly the data you are looking for in one request.

Since fewer bits will be transferred over the wire so your process using GraphQL will be faster than that of REST. No additional server round trips are needed.

<p dir="auto"><strong>Cons:</strong></p>
GraphQL might not be suited for some APIs with few entities and relationships across entities such as analytics APIs. Another limitation is lacking built-in caching support.
As you can see, although GraphQL APIs is an amazing technology, it still has some disadvantages and cannot totally replace either REST or SOAP. In most cases, it will make things simpler, but sometimes it can make simple things become complex. That’s the reason why we combined GraphQL to treat performance as the top priority with SOAP and REST to ensure services reliability.

<h2>Other Magento 2 API For Mobile App Applications</h2>
Obviously, Tigren’s ready-made Magento API was built to decrease the burden for the developers when creating mobile apps for Magento 2 stores. Regardless of the type of your mobile app (Native Apps/ React Native Apps/ Ionic Hybrid Apps), using our free Magento 2 API for Mobile App is the fastest way to reach your product.

However, that is not the only purpose and application of the Magento 2 API for Mobile App. It also can be used to:

<ul dir="auto">
<li>Integrate with Customer Relationship Management (CRM) such as Xero, SalesForces, Hubspot, SAP, Zoho…</li>
<li>Integrate with Enterprise Resource Planning (ERP) such as Microsoft Dynamics, Oracle, SAGE, Odoo, NetSuite…</li>
<li>Integrate with a Content Management System (CMS)</li>
<li>Create JavaScript widgets in either Magento frontend or backend to make AJAX calls to access services</li>
</ul>

<h2>List of Functions in Magento 2 API for Mobile App</h2>

<strong>Initial connection setup</strong>

The initial connection is needed for REST API protocol, using OAuth for token exchange.

Some parameters are:
<ol dir="auto">
  <li>Name</li>
  <li>Email</li>
  <li>Callback URL</li>
</ol>

<strong>Customer registration</strong>

Registration is for customers only, collecting information is the same as the website’s including:

<ol dir="auto">
  <li>First name</li>
  <li>Last name</li>
  <li>Email address</li>
  <li>Date of birth</li>
  <li>Gender</li>
  <li>Password</li>
  <li>Confirm password</li>
  <li>Default_billing</li>
  <li>Defaul_shipping</li>
</ol>

<strong>Customer authentication</strong>

Customer with valid access can update their information:

<ol dir="auto">
  <li>Change password</li>
  <li>Edit billing address</li>
  <li>Edit shipping address</li>
  <li>Add additional billing address</li>
  <li>Add additional shipping address</li>
  <li>Edit First name and Last name</li>
  <li>Edit date of Birth</li>
  <li>Edit Gender</li>
  <li>Delete Address</li>
  <li>Toggle default billing, shipping address</li>
  <li>Add wishlist item to cart</li>
  <li>Remove wishlist item</li>
  </ol>
  
  <p><strong>Customer details review</strong></p>
  
  <p>Customers with valid access can view the following information:</p>
  
  <ol>
<li>Account dashboard
<ul>
<li>Recent orders</li>
</ul>
</li>
<li>Account information
<ul>
<li>First name</li>
<li>Last name</li>
<li>Date of birth</li>
<li>Gender</li>
</ul>
</li>
<li>Address book suppose
<ul>
<li>Default billing address</li>
<li>Default shipping address</li>
<li>Additional billing address</li>
<li>Additional shipping address</li>
</ul>
</li>
<li>My orders
<ul>
<li>Display all orders</li>
<li>View orders, invoices</li>
<li>Re-orders</li>
</ul>
</li>
<li>My returns
<ul>
<li>Display return orders and status</li>
</ul>
</li>
<li>My wishlist</li>
</ol>

<p><strong>CMS page </strong></p>

<p>Get CMS page content based on identity</p>

<ol>
<li>HTML content</li>
<li>Page Title</li>
</ol>

<p><strong>Store catalog </strong></p>

<p>Provide the catalog list to display in the mobile app including:</p>

<ol>
<li>Category level
<ul>
<li>First level</li>
<li>Second level</li>
<li>Third level</li>
</ul>
</li>
<li>Category name</li>
<li>URL key</li>
<li>Description</li>
<li>Thumbnail image</li>
<li>Image</li>
</ol>

<p><strong>Home page</strong></p>

<p>Get data for the home page</p>

<ol>
<li>Home Banners</li>
<li>New Products</li>
<li>Top Sales Products</li>
<li>Feature Products</li>
</ol>

<p><strong>Catalog search</strong></p>

<p>Search products by name and SKU</p>

<ol>
<li>Get popular search</li>
<li>Search by name or SKU</li>
</ol>

<p><strong>Product list</strong></p>

<p>Provide a product list to be displayed in the mobile app (derived from a category):</p>

<ol>
<li>General
<ul>
<li>Name</li>
<li>SKU</li>
<li>Short description</li>
<li>Description</li>
<li>URL key</li>
</ul>
</li>
<li>Configurable Attribute
<ul>
<li>Size</li>
<li>Color</li>
</ul>
</li>
<li>Prices
<ul>
<li>Price</li>
<li>Special price</li>
<li>Special price from date</li>
<li>Special price to date</li>
</ul>
</li>
<li>Images
<ul>
<li>Thumbnail</li>
<li>Small_image</li>
<li>Base_image</li>
</ul>
</li>
</ol>

<ol start="5">
<li>Stock</li>
<li>Quantity</li>
<li>Stock Status</li>
</ol>

<p><strong>Product action</strong></p>

<ol>
<li>Add to cart</li>
<li>Add to wish list</li>
<li>Add to compare</li>
</ol>

<p><strong>Cart</strong></p>

<p>Get Cart detail for the cart page</p>

<ol>
<li>Get all cart items
<ul>
<li>Image</li>
<li>Name</li>
<li>Options (For Configurable Product )</li>
<li>Price</li>
<li>Quantity</li>
</ul>
</li>
<li>Cart Actions
<ul>
<li>Update item</li>
<li>Remove item</li>
<li>Update cart</li>
<li>Clear cart</li>
</ul>
</li>
</ol>

<p><strong>Coupon code</strong></p>

<p>Provide discount based on Magento coupon code:</p>

<ol>
<li>Provide a check to see if the coupon usage is applicable</li>
<li>Provide a check to see if the customer is able to use the coupon</li>
<li>For the active coupon code, apply the discount</li>
<li>Apply coupon on cart page &amp; checkout page</li>
</ol>

<p><strong>Checkout</strong></p>

<p>Provide API for recording the checkout:</p><ol>
<li>Purchased on</li>
<li>Bill to name</li>
<li>Ship to name</li>
<li>Base price</li>
<li>Purchase price</li>
<li>Status</li>
<li>Payment information</li>
<li>Shipping and handling</li>
<li>Product
<ul>
<li>Product name</li>
<li>SKU</li>
<li>Color</li>
<li>Size</li>
<li>Original price</li>
<li>Price</li>
<li>Quantity</li>
<li>Subtotal</li>
<li>Tax</li>
<li>Discount Amount</li>
<li>Row total</li>
</ul>
</li>
</ol>

<p><strong>Checkout Actions</strong></p>

<p>Provide API for recording the checkout:</p>

<ol>
<li>Submit a new address to change the shipping address</li>
<li>Save shipping address</li>
<li>Save shipping method</li>
<li>Save payment method</li>
<li>Place order</li>
</ol>
