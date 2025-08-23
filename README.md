# Better-Comments-Settings

### 🛠️ **Error Handling & Debugging**

* **`# BUG:`** Indicates a known bug in the code.

  ```python
  # BUG: The discount calculation is incorrect for negative values.
  ```

  🔹 **Used to mark parts of the code that need urgent fixing.**

* **`# FIXME:`** Something that must be corrected but has not yet been fixed.

  ```python
  # FIXME: This function does not check for invalid inputs.
  ```

  🔹 **Highlights an error that requires a solution.**

* **`# HACK:`** A workaround or temporary solution that may not be ideal.

  ```python
  # HACK: Forcing a delay to avoid a synchronisation issue.
  ```

  🔹 **Usually points to code that should be replaced with a proper solution later.**

* **`# DEBUG:`** Used for debugging notes.

  ```python
  # DEBUG: Check if the variable value is correct.
  print(value)
  ```

  🔹 **Helps track down errors and understand the behaviour of the code.**

* **`# TRACE:`** For logging critical points in the execution flow.

  ```python
  # TRACE: This function is called every time the button is pressed.
  ```

  🔹 **Useful for monitoring complex code flows.**

---

### 🎯 **Code Improvement & Organisation**

* **`# TODO:`** Something that still needs to be done.

  ```python
  # TODO: Implement user authentication.
  ```

  🔹 **Lists pending tasks within the code.**

* **`# OPTIMISE:`** Code that could be improved for better performance.

  ```python
  # OPTIMISE: Improve the execution time of this search.
  ```

  🔹 **Marks areas that could be made more efficient.**

* **`# REFACTOR:`** Code that should be restructured for better organisation.

  ```python
  # REFACTOR: Extract this logic into a helper function.
  ```

  🔹 **Used when the code works but can be written in a cleaner way.**

* **`# CLEANUP:`** Unnecessary code that should be removed.

  ```python
  # CLEANUP: Remove this unused temporary variable.
  ```

  🔹 **Keeps the codebase clean and tidy.**

* **`# DEPRECATED:`** Code that should no longer be used and may be removed in the future.

  ```python
  # DEPRECATED: This method will be replaced in the next release.
  ```

  🔹 **Warns about outdated functionality.**

* **`# LEGACY:`** Old code that is still in use but may need reviewing.

  ```python
  # LEGACY: Keeping this function for backwards compatibility.
  ```

  🔹 **Identifies code that may need modernisation.**

---

### 🚀 **Security & Performance Concerns**

* **`# SECURITY:`** Code with security implications.

  ```python
  # SECURITY: Sanitise user input to avoid SQL injection.
  ```

  🔹 **Ensures that vulnerabilities are spotted and fixed.**

* **`# PERFORMANCE:`** Code that could be optimised for better performance.

  ```python
  # PERFORMANCE: Reduce unnecessary database calls.
  ```

  🔹 **Focuses on making the code faster and more efficient.**

* **`# SCALABILITY:`** Code that may not handle large-scale growth well.

  ```python
  # SCALABILITY: This method may fail with millions of records.
  ```

  🔹 **Helps plan for systems that need to support growth.**

---

### 🔗 **Dependencies & Compatibility**

* **`# COMPATIBILITY:`** Compatibility concerns between versions or environments.

  ```python
  # COMPATIBILITY: Check if this API works on Python 3.8.
  ```

  🔹 **Ensures the code works across different versions.**

* **`# DEPENDENCY:`** Indicates an important dependency of the code.

  ```python
  # DEPENDENCY: Requires the requests library for HTTP calls.
  ```

  🔹 **Reminds you about required external libraries.**

---

### 💡 **Suggestions & Questions**

* **`# NOTE:`** Important information about the code.

  ```python
  # NOTE: This function uses a recursive algorithm.
  ```

  🔹 **Explains something relevant to aid understanding.**

* **`# WARNING:`** Warning about possible problems.

  ```python
  # WARNING: This method may raise exceptions if input is invalid.
  ```

  🔹 **Alerts about risks in the code.**

* **`# QUESTION:`** A doubt or something that should be reviewed.

  ```python
  # QUESTION: Is this approach really the most efficient?
  ```

  🔹 **Raises questions about how the code works.**

* **`# IDEA:`** A suggestion for future improvement.

  ```python
  # IDEA: Create an asynchronous version of this function.
  ```

  🔹 **Keeps track of potential enhancements.**

* **`# REVIEW:`** Code that must be reviewed before being considered final.

  ```python
  # REVIEW: Double-check if the calculations are correct.
  ```

  🔹 **Marks code that requires further verification.**

* **`# WTF:`** Something odd or unexpected in the code.

  ```python
  # WTF: This variable changes value without clear reason.
  ```

  🔹 **Highlights confusing or suspicious behaviour.**
