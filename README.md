# Ultimate Go Workshop

## Things to have at the back of your mind
- Engineering is about understanding cost. Every decision you make comes with a cost!
- productivity over performance
- mechanics → how things work
- semantics → how things behave
- latency, memory allocation, accessing data, algorithm efficiency

During code reviews:
- Integrity
    - all our code is doing is reading and writing to memory
    - those reads and write has to be accurate and efficient
    - writing less code and error handling is critical
- Write less code
- error handling
- Readability
    - not hiding the cost of the code you’re writing
        - Go doesn’t have constructors and destructors because they hide costs
- Simplicity
    - hiding complexity
    - it is something you refactor into
    - complexity sells
