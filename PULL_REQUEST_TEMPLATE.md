# Pull Request (PR) Checklist
Before submitting your PR, and as part of the review process, it is crucial to ensure that the following steps have been completed. This checklist serves as a guide for both the PR owner and the reviewer to maintain high standards and consistency in our codebase.

## Brief Description about this Pull Request's scope (Add links or related info if needed)

## ClickUp Task Link

## Pre-Requisite Steps for the PR owner
- [ ] **Commit:** Ensure commits are following the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) guidelines.
- [ ] **Run Linters:** Ensure that the code is linted to meet our coding standards.
- [ ] **Run Type Checking:** Perform type checking to catch any type-related errors.
- [ ] **Run Tests:** Execute all the tests to ensure that they pass and cover the expected functionality.

## Documentation or PR Explanation
- [ ] **Edge-Case Handling:** Is any edge-case handling described?
- [ ] **Third-Party Libraries:** Is the use and function of third-party libraries documented?
- [ ] **Data Structures & Units:** Are data structures and units of measurement explained?

## General
- [ ] **Functionality Check:** Does the code perform its intended function correctly?
- [ ] **Code Clarity:** Is the code easily understood and logically correct?
- [ ] **Linting:** Does the code have correct linting according to team standards?
- [ ] **Redundancy Check:** Is there any redundant or duplicate code?
- [ ] **Modularity:** Is the code as modular as possible?
- [ ] **Global Variables:** Can any global variables be replaced or minimized?
- [ ] **Library Functions:** Can any of the code be replaced with library functions?
- [ ] **Debugging Code:** Can any logging or debugging code be removed?
- [ ] **Architecture Compliance:** Does code follow the defined architecture?
- [ ] **Design & UAC Compliance:** Does the feature implementation follow User Acceptance Criteria (UAC) and specified design?
- [ ] **CI Server Passing:** Ensure the PR passes the CI server, re-run if necessary and determine PR responsibility in case of failure.
- [ ] **Code Review:** Request changes to the code and/or additional unit tests if any issues are found.
- [ ] **Naming Conventions:** Are good names used for classes, enums, structs, methods, and variables?
- [ ] **Memory Management (Only if applicable):** Is any code invoking memory leaks?
- [ ] **Storage Semantics (Only if applicable):** Are properties declared with the correct storage semantics (e.g., weak or unowned instead of strong)?

## Testing
- [ ] **Testability:** Is the code testable (e.g., minimal hidden dependencies, object initialization)?
- [ ] **Test Coverage:** Do tests exist and are they comprehensive, meeting agreed code coverage?
- [ ] **Functionality Testing:** Do unit tests verify that the code performs the intended functionality?
- [ ] **Array Bounds:** Are arrays checked for 'out-of-bound' errors?
- [ ] **Existing API Utilization:** Could any test code be replaced with the use of an existing API?

## Additional Considerations
- [ ] **Third-Party Licenses:** If using any third-party library, check for licenses and compliances.
- [ ] **Sensitive Information Storage:** If storing any sensitive information, ensure it is securely stored with appropriate encryption techniques like hash stretching.
- [ ] **Code Quality:** Avoid code smells and aim to follow the concepts of Clean Code by Robert C. Martin.
