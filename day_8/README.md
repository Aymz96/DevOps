# DAY 8:

### Subquery:
```css
- A subquery is a nested query inside another SELECT statement.
- This allows you to take the results of one query and apply them to another query.

- A subquery may occur in any of the following clauses:
- SELECT (Nested subquery-- (returns single value only)
- FROM inline view)
- WHERE (nested subquery)
```

### Data Normalisation:
```css
- A method of reducing redundancies and designing good relational databases
```
### Normal Form (Normalisation)
```ruby
We reduce the redundancies in the tables such as removing duplicate values so that we can retrieve data with better performance.
```

### 1st Normal Form
```css
- A database is in First Normal Form when the following conditions are satisfied: Gets rid of multiple values
- Make everything Atomic Data must be presented as small as it can be
- For example, a table that records data on a book and its author(s) with the following columns: [Book ID], [Author 1], [Author 2], [Author 3] is not in 1NF because the three authors are repeating the same attribute
```
### 2nd Normal Form
```ruby
A database is in Second Normal Form when the following conditions are satisfied:
- It is in 1NF
- Partially dependent on primary key
- All non-key attributes are fully functional dependant on the Primary key / The Non-Key Attribute should be fully dependant on the primary key.
```

### 3rd Normal Form
```css
Depends on a Non Key Attribute
- A database is in Second Normal Form when the following conditions are satisfied:
- It is in 2NF
- There is no transitive functional dependency
- I.e. A transitive functional dependency is when a non-key column is Functionality Dependent on another non-key column, which is Functionally Dependent on the Primary Key.
```

### Database Considerations
```css
* Data Security
* Data Recovery
* Data Integrity
* Normal Form
```
