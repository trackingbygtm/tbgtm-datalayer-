
# Ultimate Shopify DataLayer for Google Tag Manager
👉 Contact me for support: office.tbgtm@gmail.com



## How to use:

1.Go to theme edit and paste GTM tracking code right after```` bash <head>```` tag in ```` bash theme.liquid```` file

2.Inside the snippets folder create a new file as ```` bash ultimate-datalayer````. Copy all of the code from```` bash  ultimate-datalayer.liquid```` of this repository to sinppet file ```` bash ultimate-datalayer.liquid````.

3.In the theme.liquid file after your GTM tracking code include ultimate-datalayer.liquid file as ```` bash {% render 'ultimate-datalayer' %} ````

4.From shopify admin dashboard go to Settings >> Checkout (Scroll Down) >> Additional scripts. Copy all code from ```` bash checkout.liquid```` from this repository to the ```` bash Additional```` scripts field. Change the example GTM example tracking ID 000-00000 to the real GTM ID

5.Depending on your Shopify theme, you might have to make some adjustments. For more information, please refer to the video below.

## Events Included!
1. view_item
2. view_item_list
3. select_item
4. add_to_cart
5. remove_from_cart
6. view_cart
7. view_item_list
8. begin_checkout
9. add_to_wishlist
10. add_payment_info
11. add_shopping_info
12. purchase
13. contact_form_submit
14. newsletter_signup
15. search
16. phone_number_click
17. email_click
18. Logged customer and on the checkout page customer details included as customer object with dataLayer
19. Event Parameters: currency, value, transaction_id, coupon, shipping, vat, items, item_list_name, item_list_id
20. Items Parameters item_id, item_name, quantity, price, discount, item_brand, item_category, item_variant, sku, item_list_name, item_list_id
