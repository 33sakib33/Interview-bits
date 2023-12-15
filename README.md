# Interview-bits
Compilation of resources for practicing technical interview questions in software companies across various technical positions.

# Table of Contents

1. [Data Structures and Algorithms](#data-structures-and-algorithms)
   1.1 [Linked Lists](#linked-lists)
      1.1.1 [Linked List Cycle - LeetCode](#linked-list-cycle---leetcode)
   1.2 [Stacks](#stacks)
      1.2.1 [Valid Parentheses - LeetCode](#valid-parentheses---leetcode)

2. [Structured Algorithms](#structured-algorithms)
   2.1 [Difference Between Ones and Zeros in Row and Column - LeetCode](#difference-between-ones-and-zeros-in-row-and-column---leetcode)

3. [Web](#web)
   3.1 [Interesting Bits of Information](#interesting-bits-of-information)
      3.1.1 [Session-Based vs Token-Based Authentication](#session-based-vs-token-based-authentication)

4. [Detailed Sections](#detailed-sections)
   4.1 [Data Structures and Algorithms](#data-structures-and-algorithms-1)
      4.1.1 [Linked Lists](#linked-lists-1)
         4.1.1.1 [Linked List Cycle - LeetCode](#linked-list-cycle---leetcode-1)
      4.1.2 [Stacks](#stacks-1)
         4.1.2.1 [Valid Parentheses - LeetCode](#valid-parentheses---leetcode-1)
   4.2 [Structured Algorithms](#structured-algorithms-1)
      4.2.1 [Difference Between Ones and Zeros in Row and Column - LeetCode](#difference-between-ones-and-zeros-in-row-and-column---leetcode)
   4.3 [Web](#web-1)
      4.3.1 [Session-Based vs Token-Based Authentication](#session-based-vs-token-based-authentication-1)

5. [Database](#database)
   5.1 [Coalesce vs IsNull](#coalesce-vs-isnull)


---

# Detailed Sections

## Data Structures and Algorithms

### Linked Lists

#### Linked List Cycle - LeetCode
- **Problem Description:** [Linked List Cycle - LeetCode](https://leetcode.com/problems/linked-list-cycle/)

### Stacks

#### Valid Parentheses - LeetCode
- **Problem Description:** [Valid Parentheses - LeetCode](https://leetcode.com/problems/valid-parentheses/)

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
