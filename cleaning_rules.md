# Cleaning rules log

| ID | Finding | Evidence (count) | Rule / decision | Rows affected |
|----|---------|------------------|-----------------|---------------|
| R00 | 4 rows have an integer in Description (code-like value, Price = 0) | 4 rows | Converted Description to text for storage; rows kept in raw file. Decision on exclusion pending | 4 |