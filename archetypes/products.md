---
# product ID
productID: "0001"

title: "{{ replace .Name "-" " " | title }}"
date: {{.Date}}
draft: true

# type must be "products"
type: "products"

# product Images
# first image will be shown in the product page
# add multiple image with - image: "image path with extension"
images:
  - image: "images/products/productName-1.jpeg"
  - image: "images/products/productName-2.jpeg"
  - image: "images/products/productName-3.jpeg"
  - image: "images/products/productName-4.jpeg"
  - image: "images/products/productName-5.jpeg"
  - image: "images/products/productName-6.jpeg"

# product Price
price: "Rs. "
priceBefore: ""

url: "link_Url_Search_In_Google"

# meta description for google search product list page
description : "desciption_In_List_Page"

# Product Short Description
shortDescription: "desciption_In_Item_Page"
---
**product_Description_Remove_This_Line

