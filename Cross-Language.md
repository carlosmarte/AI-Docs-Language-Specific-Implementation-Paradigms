# Cross-Language Differences

|            | **Python** | **Go**     | **Java**     | **Rust**   |             |
| ---------- | ---------- | ---------- | ------------ | ---------- | ----------- |
| Client     | Class      | Class      | Struct       | Builder    | Struct      |
| Async      | Native     | Optional   | Goroutines   | Futures    | Async       |
| Errors     | Exceptions | Exceptions | Error return | Exceptions | Result<T,E> |
| Middleware | Common     | Growing    | Strong       | Strong     | Strong      |
| Typing     | Weak       | Medium     | Strong       | Strong     | Very strong |

# Async / Concurrency Pattern

Language-specific:

- Node.js → async/await
- Python → async/await
- Go → goroutines
- Java → CompletableFuture / reactive
- Rust → async + ownership model
