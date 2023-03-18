### The Data
- I see redundant data in ocid and title. May only retain the last 17 characters present in title.
- Both amount and budget are numeric but being represented as object data type. They may contain NaNs which may preclude the option of making them numeric of smaller denomination.
    Solution may entail removing NaNs such that these can be numeric.
- All string must be lowercase. Accents and other special characters ougth to be removed.
- Need to strip whitespace from the beginning of phrases in each data cell.

### Missing Values
- The initial calculations to estimate incidence of missing values are misleading since many data cells contains strings 'None'
- 