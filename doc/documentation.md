Here is the documentation for the python template.

### HW1 Technology Template Repository
Based on the objectives outlined in the assignment, here are the final choices we have made for setting up Python project template repository:

1. Select a Programming Language:
   - Choice: Python.
2. Choose a Toolchain/Runtime Environment:
   - Choice: Python with a virtual environment using venv initially discussed, but then pivoted to using PDM (Python Dependency Management) for managing dependencies and virtual environments, aligning with the modern Python development practices.
3. Select a Testing Framework:
   - Choice: pytest for writing and executing tests.
4. Continuous Integration Solution:
   - Choice: CircleCI, configured in .circleci/config.yml for automating tests, static analysis, and code formatting.
5. Static Analysis Tool:
   - Choice: flake8 for linting, and the option to use mypy for type checking was mentioned as a possibility for projects that benefit from static typing.
6. Code Formatting Solution:
   - Choice: black for automatic code formatting, with isort for sorting imports to ensure consistent code style.
7. Package Manager:
   - Initial Discussion: Use pip for managing Python packages, as per the assignment's guidelines.
   - Final Decision: Implement Python Dependency Management (PDM) for managing project dependencies and environments, reflecting a more modern approach to Python project setup.
8. Use PDM for Python Projects:
   - Confirmation: We decided to use PDM, emphasizing its benefits for dependency management and integration with the pyproject.toml file for project configuration.
9. Component Specification:
   - Implementation: We ensured the template includes a structured approach to organizing the project, with clear definitions and documentation for components such as the src directory for source code and tests directory for test scripts.
10. Issue and Pull Request Templates:
    - Setup: Created templates for issues and pull requests within the .github directory to standardize submissions and facilitate clear, structured communication for contributions.

We aimed to align with the assignment's objectives while also considering modern best practices in Python development. The use of PDM, in particular, reflects a forward-looking approach to Python project management, balancing the assignment requirements with the evolving landscape of Python tooling.

