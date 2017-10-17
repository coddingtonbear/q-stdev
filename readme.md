*NOTE*: This functionality is contingent upon [this pull request](https://github.com/harelba/q/pull/155).

---

Adds functionality allowing you to calculate the standard deviation of columns using the `stdev` function in your
[`q`](https://github.com/harelba/q) SQL queries.

Example:

```python
SELECT stdev(some_column) FROM ./my_file.csv;
```
