```markdown
# AGENTS.md - Guidelines for AI Coding Agents

These guidelines are designed to ensure the consistent, robust, and maintainable development of our AI coding agents. Adherence to these principles will contribute to a high-quality, reliable, and easily understandable codebase.

**1. DRY (Don't Repeat Yourself)**

*   **Module Structure:** Each module should implement a single, well-defined purpose. Avoid creating overly complex modules with repeated functionality.
*   **Function/Class Reusability:**  Functions and classes should have clear, focused responsibilities, minimizing duplication of logic.  Favor composition over inheritance whenever possible.
*   **Parameterization:** Design functions and classes to accept parameters that significantly alter their behavior, reducing repetition.

**2. KISS (Keep It Simple, Stupid)**

*   **Code Clarity:** Prioritize readability and understandability.  Strive for simple, declarative code.
*   **Avoid Complexity:** Resist the temptation to over-engineer solutions. When complexity is unavoidable, document it thoroughly.
*   **Minimize Lines:** Aim for the shortest code to achieve the intended functionality.

**3. SOLID Principles**

*   **Single Responsibility Principle:** Each class/module should have one and only one reason to change.
*   **Open/Closed Principle:**  Code should be open for extension but closed for modification. This promotes flexibility without compromising core functionality.
*   **Liskov Substitution Principle:**  Subclasses should be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:** Clients should not be forced to depend on methods they don't use.

**4. YAGNI (You Aren't Gonna Need It)**

*   **Avoid Unnecessary Code:**  Do not implement functionality that is demonstrably unnecessary for the current task.
*   **Focus on the Core:**  Maintain a clear, concise, and focused implementation.

**5. Testing & Coverage**

*   **Mocks ONLY for Testing:** All tests should *only* utilize mocks.  No real implementations are required.
*   **Test-Driven Development:**  Write tests *before* implementing the code.
*   **Comprehensive Tests:** Aim for at least 80% test coverage.
*   **Unit Tests:**  Each function/class should have at least one unit test covering its core logic.
*   **Integration Tests:**  Tests that verify interactions between multiple components.

**6. Code Length & Structure**

*   **Maximum Code Length:** 180 lines of code (excluding comments and docstrings).
*   **Consistent Formatting:** Follow a consistent code style (e.g., using a linter and formatting tool).
*   **Meaningful Names:** Use descriptive and concise names for variables, functions, and classes.

**7.  Specific Requirements (Illustrative - Adapt to Project Needs)**

*   **State Management:**  Implement a robust state management system using a consistent approach (e.g., a state object or a dedicated state management library).
*   **Data Structures:** Employ appropriate data structures for efficient data representation and manipulation.
*   **Error Handling:**  Implement clear and informative error handling mechanisms.
*   **Logging:**  Use structured logging to aid in debugging and monitoring.

**8.  Documentation**

*   **Docstrings:** Provide clear and concise docstrings for all functions, classes, and modules.
*   **Comments:**  Use comments sparingly and only to explain non-obvious logic.  Prioritize clear code over lengthy comments.

**9.  File Structure**

*   Each file should follow a clear naming convention.
*   Use a consistent directory structure.
*   Consider a "README" file at the top of the repository explaining the project's goals and setup.

**10.  Code Quality**

*   **Readability:**  Code should be easily understandable by other developers.
*   **Maintainability:** Code should be easy to modify and extend in the future.
*   **Security:**  Consider potential security implications and implement appropriate safeguards.

**11.  Development Workflow**

*   Follow a defined development workflow (e.g., pull requests, code reviews).
*   Conduct regular code reviews.

These guidelines are subject to change as the project evolves. Updated versions will be communicated via a dedicated `CONTRIBUTING.md` file.
```