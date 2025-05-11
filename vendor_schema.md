# Palett Vendor Product Schema (v1.0)
Each scraped product should follow this structure:

| Field            | Type     | Description                                  |
|------------------|----------|----------------------------------------------|
| `name`           | string   | Product name                                 |
| `vendor`         | string   | Name of the vendor                           |
| `category`       | enum     | e.g., Tile, Textiles, Rugs, Stone            |
| `subcategory`    | string   | More specific type (e.g., Handpainted Tile)  |
| `material`       | string   | Base material (e.g., Ceramic, Wool)          |
| `color`          | string   | Color or dominant tone                       |
| `size`           | string   | Dimensions                                   |
| `price`          | string   | Price (e.g., "$10.00")                       |
| `leadTime`       | string   | Typical fulfillment time                     |
| `imageUrl`       | string   | Full URL to product image                    |
| `productPageUrl` | string   | Link to original product page                |
| `certifications` | list     | Optional: LEED, HPD, etc.                    |
| `tags`           | list     | Optional: extra descriptors                  |
| `documents`      | list     | Optional: spec sheets, PDFs, etc. (URLs)     |

💡 Note: Not every vendor will have all fields. Use `null` if missing.
