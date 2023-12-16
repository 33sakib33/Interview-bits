# Interview-bits: A Resource for Technical Interviews in Software Industries

## Table of Contents
1. [Data Structures and Algorithms](#data-structures-and-algorithms)
    - [Linked Lists](#linked-lists)
        - [Linked List Cycle - LeetCode](#linked-list-cycle---leetcode)
    - [Stacks](#stacks)
        - [Valid Parentheses - LeetCode](#valid-parentheses---leetcode)
    - [Backtracking](#backtracking)
        - [Combination Sum - LeetCode](#combination-sum---leetcode)
    - [Structured Algorithms](#structured-algorithms)
        - [Difference Between Ones and Zeros in Row and Column - LeetCode](#difference-between-ones-and-zeros-in-row-and-column---leetcode)
2. [Web](#web)
    - [Session-Based vs Token-Based Authentication](#session-based-vs-token-based-authentication)
3. [Database](#database)
    - [Coalesce vs IsNull](#coalesce-vs-isnull)

---

## Data Structures and Algorithms

### Linked Lists

#### Linked List Cycle - LeetCode
- **Problem Description:** [Linked List Cycle - LeetCode](https://leetcode.com/problems/linked-list-cycle/)

### Stacks

#### Valid Parentheses - LeetCode
- **Problem Description:** [Valid Parentheses - LeetCode](https://leetcode.com/problems/valid-parentheses/)

### Backtracking

#### Combination Sum - LeetCode
- **Problem Description:** [Combination Sum - LeetCode](https://leetcode.com/problems/combination-sum/)

### Structured Algorithms

#### Difference Between Ones and Zeros in Row and Column - LeetCode
- **Problem Description:** [Difference Between Ones and Zeros in Row and Column](https://leetcode.com/problems/difference-between-ones-and-zeros-in-row-and-column)
- **Solution:** [A two pass solution](https://leetcode.com/problems/difference-between-ones-and-zeros-in-row-and-column/solutions/4403123/two-pass-solution/)

## Web

### Session-Based vs Token-Based Authentication

| **Aspect** | **Session-Based** | **Token-Based** |
|------------|-------------------|-----------------|
| **Storage Location** | Server (session identifier in cookie) | Client (token in cookie or local storage) |
| **Server State** | Maintains session state | Stateless, token contains user information |
| **Scalability** | May require shared session storage | Scales easily without shared storage |
| **Statelessness** | Stateful | Stateless |
| **Implementation Complexity** | Session management complexities | Simpler storage management, but additional security considerations |
| **Use Cases** | Traditional web apps | Modern, stateless, distributed apps (SPAs, mobile apps) |

## Database

### Coalesce vs IsNull

**COALESCE:**
- *Syntax:* `COALESCE(expr1, expr2, ..., exprn)`
- *Returns:* First non-null expression in the list.

**ISNULL:**
- *Syntax:* `ISNULL(expr1, expr2)`
- *Returns:* First argument if not null; otherwise, second argument.
