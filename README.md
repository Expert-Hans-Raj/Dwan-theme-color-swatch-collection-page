# Dwan-theme-color-swatch-collection-page

# Snippet folder and find card-product.liquid. 
# Once found, scroll down until you find the below code

{% render 'price', product: card_product, price_class: '' %}

# Copy my code &  paste the below.

# Find the my js code & copy & paste on your js file.
# Add this class under "mian_image" image tag.


# Add Code To Base.css
Now, head over to the Asset folder, find base.css and paste the below code at the bottom of the file


Add Code To Base.css
input[type=radio][name$=_card_color]{
width: 20px;
height: 20px;
border-radius: 50%;
appearance: none;
background-size: 9px 9px;
background-image: repeating-linear-gradient(45deg, #000 0, #000 1px, #ebebeb 0, #ebebeb 50%);
}
.collection .card-wrapper {
   
    position: unset !important;
   
}


# Here is the demo url:- https://teenam49.myshopify.com/


# If you facing any issue, contact me any time. Emial:- ecommerce.web.expert@gmail.com
