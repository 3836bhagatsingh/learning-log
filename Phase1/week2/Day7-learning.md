List vs Dict: list = ordered sequence, dict = key-value O(1) lookup → use dict when search is frequent
Dict keys must be unique, list allows duplicates
List search = O(n), dict lookup = O(1) → performance question



.split(",") → string → list
.join() → list → string (ONLY works on strings)
⚠️ ",".join([1,2]) → ❌ error → convert to str first



INNER JOIN → only matching rows (intersection)
LEFT JOIN → all left rows + matched right (NULL if no match)
⚠️ Missing rows problem = mostly wrong JOIN type



WHERE → filters rows (before GROUP BY)
HAVING → filters groups (after GROUP BY)
⚠️ WHERE COUNT(*) → ❌ invalid → must use HAVING



Execution order (VERY IMPORTANT):
FROM → WHERE → GROUP BY → HAVING → SELECT → ORDER BY



GROUP BY rule:
Every selected column must be
→ either in GROUP BY OR aggregated



Interview query pattern:

SQLSELECT category, COUNT(*), AVG(price)FROM productsGROUP BY categoryHAVING COUNT(*) > 5;Show more lines


LEFT JOIN trick:

SQLSELECT *FROM ALEFT JOIN B ON A.id = B.idWHERE B.id IS NULL;  -- find unmatchedShow more lines


Safe file handling:
with open() → auto close → prevents memory leak



Biggest mistakes:

Using WHERE instead of HAVING
Wrong JOIN type
Forgetting GROUP BY columns
.join() on non-string
Not handling NULLs in JOIN





Real-world thinking:
JOIN = combine tables
GROUP BY = aggregation (Power BI backend logic)
HAVING = business rule on aggregated data


