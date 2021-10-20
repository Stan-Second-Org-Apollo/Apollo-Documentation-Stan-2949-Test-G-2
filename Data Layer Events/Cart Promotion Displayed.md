# Cart Promotion Displayed

### 

## Javascript Code
```js
window.dataLayer09876 = window.dataLayer09876 || [];
dataLayer09876.push({ ecommerce: null });  // Clear the previous ecommerce object.
dataLayer09876.push({
  "event": "Cart Promotion Displayed",
    "ecommerce": {
        "items": [
            {
                "item_id": "<item_id>",
                "item_name": "<item_name>"
            }
        ]
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|item_id|string|Item ID \(context-specific\).The product primary ID \(SKU or UPC\) |SKU\_12345|||||||
|item_name|string|Item Name \(context-specific\).|jeggings|||||||




