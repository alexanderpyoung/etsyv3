# Etsyv3 

## Implementation details


| **Etsy API**                                        | **Package API**                                            | **Implemented**        |
|-----------------------------------------------------|------------------------------------------------------------|------------------------|
| GetBuyerTaxonomyNodes                               | get_buyer_taxonomy_nodes                                   | ✔️                     |
| GetPropertiesByBuyerTaxonomyId                      | get_properties_by_buyer_taxonomy_id                        | ✔️                     |
| GetSellerTaxonomyNodes                              | get_seller_taxonomy_nodes                                  | ✔️                     |
| GetPropertiesByTaxonomyId                           | get_properties_by_taxonomy_id                              | ✔️                     |
| CreateDraftListing                                  | create_draft_listing                                       | ✔️                     |
| GetListingsByShop                                   | get_listings_by_shop                                       | ✔️                     |
| DeleteListing                                       | delete_listing                                             | ✔️                     |
| GetListing                                          | get_listing                                                | ✔️                     |
| FindAllListingsActive                               | find_all_listings_active                                   | ✔️                     |
| FindAllActiveListingsByShop                         | find_all_active_listings_by_shop                           | ✔️                     |
| GetListingsByListingIds                             | get_listings_by_listing_ids                                | ✔️                     |
| GetFeaturedListingsByShop                           | get_featured_listings_by_shop                              | ✔️                     |
| DeleteListingProperty                               | delete_listing_property                                    | ✔️                     |
| UpdateListingProperty                               | update_listing_property                                    | ❌                      |
| GetListingProperty                                  | get_listing_property                                       | ❌ (501 only from Etsy) |
| GetListingProperties                                | get_listing_properties                                     | ✔️                     |
| UpdateListing                                       | update_listing                                             | ❌                      |
| GetListingsByShopReceipt                            | get_listings_by_shop_receipt                               | ✔️                     |
| GetListingsByShopSectionId                          | get_listings_by_shop_section_id                            | ✔️                     |
| DeleteListingFile                                   | delete_listing_file                                        | ✔️                     |
| GetListingFile                                      | get_listing_file                                           | ✔️                     |
| GetAllListingFiles                                  | get_all_listing_files                                      | ✔️                     |
| UploadListingFile                                   | upload_listing_file                                        | ❌                      |
| DeleteListingImage                                  | delete_listing_image                                       | ❌                      |
| GetListingImage                                     | get_listing_image                                          | ❌                      |
| GetListingImages                                    | get_listing_images                                         | ❌                      |
| UploadListingImage                                  | upload_listing_image                                       | ❌                      |
| GetListingInventory                                 | get_listing_inventory                                      | ✔️                     |
| UpdateListingInventory                              | update_listing_inventory                                   | ✔️                     |
| GetListingOffering                                  | get_listing_offering                                       | ❌                      |
| GetListingProduct                                   | get_listing_product                                        | ❌                      |
| CreateListingTranslation                            | create_listing_translation                                 | ❌                      |
| GetListingTranslation                               | get_listing_translation                                    | ❌                      |
| UpdateListingTranslation                            | update_listing_translation                                 | ❌                      |
| GetListingVariationImages                           | get_listing_variation_images                               | ❌                      |
| UpdateVariationImages                               | update_variation_images                                    | ❌                      |
| UserInfo                                            | user_info                                                  | ❌                      |
| Ping                                                | ping                                                       | ❌                      |
| TokenScopes                                         | token_scopes                                               | ❌                      |
| GetShopPaymentAccountLedgerEntry                    | get_shop_payment_account_ledger_entry                      | ❌                      |
| GetShopPaymentAccountLedgerEntries                  | get_shop_payment_account_ledger_entries                    | ❌                      |
| GetPaymentAccountLedgerEntryPayments                | get_payment_account_ledger_entry_payments                  | ❌                      |
| GetShopPaymentByReceiptId                           | get_shop_payment_by_receipt_id                             | ❌                      |
| GetPayments                                         | get_payments                                               | ❌                      |
| GetShopReceipts                                     | get_shop_receipts                                          | ✔️                     |
| CreateReceiptShipment                               | create_receipt_shipment                                    | ❌                      |
| GetShopReceiptTransactionsByListing                 | get_shop_receipt_transactions_by_listing                   | ❌                      |
| GetShopReceiptTransactionsByReceipt                 | get_shop_receipt_transactions_by_receipt                   | ❌                      |
| GetShopReceiptTransaction                           | get_shop_receipt_transaction                               | ❌                      |
| GetShopReceiptTransactionsByShop                    | get_shop_receipt_transactions_by_shop                      | ❌                      |
| GetReviewsByListing                                 | get_reviews_by_listing                                     | ❌                      |
| GetReviewsByShop                                    | get_reviews_by_shop                                        | ❌                      |
| GetShippingCarriers                                 | get_shipping_carriers                                      | ❌                      |
| CreateShopShippingProfile                           | create_shop_shipping_profile                               | ❌                      |
| GetShopShippingProfiles                             | get_shop_shipping_profiles                                 | ❌                      |
| DeleteShopShippingProfile                           | delete_shop_shipping_profile                               | ❌                      |
| GetShopShippingProfile                              | get_shop_shipping_profile                                  | ❌                      |
| UpdateShopShippingProfile                           | update_shop_shipping_profile                               | ❌                      |
| CreateShopShippingProfileDestination                | create_shop_shipping_profile_destination                   | ❌                      |
| GetShopShippingProfileDestinationsByShippingProfile | get_shop_shipping_profile_destinations_by_shipping_profile | ❌                      |
| DeleteShopShippingProfileDestination                | delete_shop_shipping_profile_destination                   | ❌                      |
| UpdateShopShippingProfileDestination                | update_shop_shipping_profile_destination                   | ❌                      |
| CreateShopShippingProfileUpgrade                    | create_shop_shipping_profile_upgrade                       | ❌                      |
| GetShopShippingProfileUpgrades                      | get_shop_shipping_profile_upgrades                         | ❌                      |
| DeleteShopShippingProfileUpgrade                    | delete_shop_shipping_profile_upgrade                       | ❌                      |
| UpdateShopShippingProfileUpgrade                    | update_shop_shipping_profile_upgrade                       | ❌                      |
| GetShop                                             | get_shop                                                   | ❌                      |
| UpdateShop                                          | update_shop                                                | ❌                      |
| GetShopByOwnerUserId                                | get_shop_by_owner_user_id                                  | ❌                      |
| FindShops                                           | find_shops                                                 | ❌                      |
| GetShopProductionPartners                           | get_shop_production_partners                               | ❌                      |
| CreateShopSection                                   | create_shop_section                                        | ❌                      |
| GetShopSections                                     | get_shop_sections                                          | ❌                      |
| DeleteShopSection                                   | delete_shop_section                                        | ❌                      |
| GetShopSection                                      | get_shop_section                                           | ❌                      |
| UpdateShopSection                                   | update_shop_section                                        | ❌                      |
| GetUser                                             | get_user                                                   | ✔️ ️                   |
| DeleteUserAddress                                   | delete_user_address                                        | ❌                      |
| GetUserAddress                                      | get_user_address                                           | ❌                      |
| GetUserAddresses                                    | get_user_addresses                                         | ❌                      |




