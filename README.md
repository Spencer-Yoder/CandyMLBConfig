# Sales bot config

**Price** (`Number`): Amount without the decimal
  - example: $25.00 is just 2500

**Rarity** (`Array of Strings | null`): Rarities to be included in the filter
  - types:
    - PRODUCT_RARITY_CORE (Unopned packs)
    - PRODUCT_RARITY_COMMON
    - PRODUCT_RARITY_UNCOMMON
    - PRODUCT_RARITY_RARE
    - PRODUCT_RARITY_EPIC
    - PRODUCT_RARITY_LEGENDARY

**Sync Interval** (`Number`): Seconds between marketplace refreshes
