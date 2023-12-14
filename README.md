# Interview-bits
Compilation of resources for practicing technical interview questions in software companies across various technical positions.

## Data Structures and Algorithms

### Linked Lists
- [Linked List Cycle - LeetCode](#linked-list-cycle)

### Stacks
- [Valid Parentheses - LeetCode](#valid-parentheses)

## Structured Algorithms
- [Difference Between Ones and Zeros in Row and Column - LeetCode](#difference-between-ones-and-zeros)

# Web

## Interesting Bits of Information
- [Session-Based vs Token-Based Authentication](#session-based-vs-token-based-authentication)

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

