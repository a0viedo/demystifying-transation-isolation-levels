
Emoji | Represents 
:---: | --- 
:notebook: | Blog post
:page_facing_up: | White paper
:computer: | Code
:book: | Book

# Transaction isolation

- :notebook: [An Introduction to Transaction Isolation Levels][fauna-intro-isolation-levels] - FaunaDB blog
- :notebook: [Serializability vs “Strict” Serializability: The Dirty Secret of Database Isolation Levels][fauna-strict-serializability] - FaunaDB blog
- :page_facing_up: [A Critique of ANSI SQL Isolation Levels][critique-isolation-levels] - Berenson, Gray, Bernstein et al.
- :page_facing_up: [Weak Consistency: A Generalized Theory and Optimistic
Implementations for Distributed Transactions][weak-consistency-generalized-theory] - Atul Adya's PhD thesis
- :notebook: [Transaction Isolation in Postgres, explained
][transaction-isolation-postgres] - Nile blog
- :notebook: [Understanding Weak Isolation Is a Serious Problem][understanding-weak-isolation] - Peter Bailis' blog
- :book: [Chapter 6: Weak Isolation and Distribution][chapter6-weak-isolation] - Readings in Database Systems book
- :notebook: [Strict Serializability][strict-serializable] - jepsen.io
- :computer: [transaction isolation levels testing tool][hermitage-test]


[fauna-strict-serializability]: https://fauna.com/blog/serializability-vs-strict-serializability-the-dirty-secret-of-database-isolation-levels
[fauna-intro-isolation-levels]: https://fauna.com/blog/introduction-to-transaction-isolation-levels
[hermitage-test]: https://github.com/ept/hermitage
[critique-isolation-levels]: https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/tr-95-51.pdf
[weak-consistency-generalized-theory]: https://pmg.csail.mit.edu/papers/adya-phd.pdf
[transaction-isolation-postgres]: https://www.thenile.dev/blog/transaction-isolation-postgres
[understanding-weak-isolation]: http://www.bailis.org/blog/understanding-weak-isolation-is-a-serious-problem/
[chapter6-weak-isolation]: http://www.redbook.io/ch6-isolation.html
[strict-serializable]: https://jepsen.io/consistency/models/strict-serializable
