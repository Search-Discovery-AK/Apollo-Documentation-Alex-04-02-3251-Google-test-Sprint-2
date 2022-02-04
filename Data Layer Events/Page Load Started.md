# Page Load Started

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({ page_data: null });  // Clear the previous page_data object.
dataLayer.push({
  "event": "Page Load Started",
    "ecommerce": {
        "page_type_merchandising": "<page_type_merchandising>"
    },
    "event_data": {
        "content_owner": "<content_owner>"
    },
    "page_data": {
        "country": "<country>",
        "language": "<language>",
        "page_location": "<page_location>",
        "page_name": "<page_name>",
        "page_name_detailed": "<page_name_detailed>",
        "page_title": "<page_title>",
        "page_type": "<page_type>",
        "site_name": "<site_name>",
        "site_type": "<site_type>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|content_owner|string|Counts of times the user performed an interaction on the order confirmation page.|XX product management, marketing, vendor name|||||||
|country|string|The country the site is associated with.||||||||
|language|string|The language of the current page, usually pulled from the &lt;html&gt; tag lang attribute.||||||||
|page_location|string|The url of the page currently being viewed.||||||||
|page_name|string|Amount of money discounted for the entire order.|product - XYZ123, Mens - Tops - Sweaters, Order Confirmation|||||||
|page_name_detailed|string|Captures the filter applied to the product listings or search results.|product - XYZ123 - super cotton neck scarf, Mens - Tops - Sweaters - Supmina, Wool, Rayon, Order Confirmation - 098fghjkl|||||||
|page_title|string|The title of the page currently being viewed, generally available in &lt;title&gt;.||||||||
|page_type|string|The type of page currently viewed.|home, pdp, article|||||||
|page_type_merchandising|string|Captures the revenue dollar amount of the order for use in bucketing orders into specific revenue bands \(i.e. $0-$50, $51-$100\).|Home, Event Detail, Property Detail, Product Listing, Blog Post, Shopping Cart|||||||
|site_name|string|Captures the business unit associated with each product.|Prospecting-EU, Prospecting-US, Member Portal, Shop-CA, Shop-US, Shop-EU|||||||
|site_type|string|Amount of money associated with markdown prices for products reached the order confirmation step of the shopping cart.|Prospecting, Shop, Members, Brand|||||||




