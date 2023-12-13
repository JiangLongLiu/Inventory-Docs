# ✨ Features

* Check if there are any missing items in a set.
* Check if you have all your items with you when leaving a place.
* Locate an item via its RFID tag.
* Full-text search for your items and collections.
* Data Synchronization through self-hosted CouchDB.
* CSV export and import.
* Item expiry date tracking.
* Consumable item stocked quantity tracking.
* [Deep link support](../app/deep-linking-url-schemes.md) - use special URLs to open the app and go to a specific item or collection. You can also make the URL into a QR Code and then open an item by scanning it.
  * This is useful when combined with consumable item tracking - scan the QR Code of the item, then have a quick update on the stock level in the app.

### Integrations

* Snipe-IT: Currently a simple one-way synchronization (import) is implemented. We're planning on implementing a complete two-way synchronization.

## Known Limitations

### RFID tag limitations.

It’s essential to be cognizant of the limitations associated with UHF RFID tags and metal or liquid environments. Standard RFID tags may not function optimally on metal surfaces or liquid-containing containers due to signal reflection or absorption. Specialized anti-metal tags are available for these scenarios, though they come at a premium. Additionally, the effective read range of RFID tags can diminish significantly if obscured by metal, and tags housed within fully enclosed metal containers will be unreadable.

### App performance.

Currently, the app's development focuses on new features but not performance optimizations - we have many performance optimization plans in the TODO list.

As a result, the app might not perform well on devices older than iPhone 12 if you have more than 500 items.
