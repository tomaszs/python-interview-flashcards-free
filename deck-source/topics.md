# Python Interview 2026 · question index

Technologies: Python 3.12+, typing, asyncio, data structures, OOP, and production Python

## All questions

1. Explain the GIL in Python 3.12 and its implications for multi-threaded applications. How has it evolved, and what are common strategies to work around it?
2. Describe the new features and improvements introduced in Python 3.12. Focus on those relevant to performance or developer experience.
3. How do you effectively use `asyncio` for building high-performance network services in Python 3.12? Discuss common patterns and potential pitfalls.
4. What are type hints in Python, and how do they contribute to maintainable and robust codebases, especially in large projects? Provide examples of advanced typing features.
5. Differentiate between `mypy` and `pyright`. When would you choose one over the other for static type checking in a Python project?
6. Explain the concept of a `Protocol` in Python typing. Provide a practical example where it significantly improves code clarity or flexibility.
7. How do you handle dependency management and virtual environments in a large Python project? Compare `pip-tools`, `Poetry`, and `Rye`.
8. Discuss the trade-offs between using `dataclasses`, `NamedTuple`, and custom classes for defining data structures. When would you choose each?
9. Implement a custom context manager using both a class and a generator function (`@contextlib.contextmanager`). Explain the differences.
10. Describe the principles of Object-Oriented Programming (OOP) in Python. How does Python's approach to OOP differ from strictly class-based languages?
11. Explain the Method Resolution Order (MRO) in Python. How does it work, and how can you inspect it?
12. What are metaclasses in Python? Provide a concrete example of when you might use a metaclass in a production system.
13. Discuss the use of decorators in Python. Implement a decorator that caches the results of a function call with a time-to-live (TTL).
14. How do you design for extensibility and maintainability in a large Python codebase? Discuss design patterns relevant to Python.
15. Explain the difference between `__slots__` and `__dict__` in Python classes. When and why would you use `__slots__`?
16. Describe different ways to achieve polymorphism in Python. Provide examples beyond simple method overriding.
17. How do you handle configuration management in a complex Python application? Compare environment variables, `configparser`, and `Pydantic` settings.
18. Discuss the Python packaging ecosystem. What are the key components (e.g., `setuptools`, `wheel`, `PyPI`), and how do they interact?
19. Explain the process of building and publishing a Python package to PyPI. What are best practices for package metadata and structure?
20. How do you ensure the quality and correctness of a Python package through testing? Discuss different types of tests (unit, integration, end-to-end).
21. Describe your approach to logging in a production Python application. What considerations do you take for log levels, formatters, and handlers?
22. How do you monitor the performance of a Python application in production? Discuss tools and metrics you would track.
23. Explain the concept of a generator in Python. Provide an example where a generator is more efficient than a list.
24. What is the difference between an iterator and an iterable? How do you create custom iterators in Python?
25. Discuss the use of `functools.lru_cache` and `functools.cached_property`. When would you use each, and what are their limitations?
26. Explain the concept of a closure in Python. Provide an example of its practical application.
27. How do you handle exceptions effectively in Python? Discuss custom exception hierarchies and best practices for error handling.
28. Describe the `with` statement and its underlying mechanism (`__enter__`, `__exit__`). Provide an example of a custom context manager.
29. What are descriptors in Python? Provide a simple example of a descriptor and explain its use case.
30. Discuss the differences between `is` and `==` in Python. When would you use each?
31. Explain how Python manages memory. Discuss reference counting and garbage collection.
32. How do you optimize Python code for performance? Discuss profiling tools and common optimization techniques.
33. Describe the differences between `list`, `tuple`, `set`, and `dict` in Python. When would you choose each data structure?
34. Implement a `deque` (double-ended queue) using Python's `collections` module. Explain its advantages over a standard list for certain operations.
35. Discuss the use of `collections.Counter` and `collections.defaultdict`. Provide practical examples for each.
36. How do you work with files and I/O in Python? Discuss binary vs. text modes and error handling during file operations.
37. Explain the purpose of `sys.path` and how Python locates modules. How can you influence this process?
38. Describe the concept of a module and a package in Python. How are they organized and imported?
39. What are `__init__.py` files, and what is their role in Python packages?
40. Discuss the use of `argparse` for command-line argument parsing. Provide an example with subcommands.
41. How do you interact with external APIs in Python? Discuss common libraries and best practices for error handling and rate limiting.
42. Explain the concept of dependency injection in Python. How can it improve testability and modularity?
43. Describe the principles of clean code and how they apply to Python development.
44. How do you handle secrets and sensitive information in a Python application deployed to production?
45. Discuss the importance of code reviews in a team setting. What do you look for during a code review?
46. Explain the concept of immutability in Python. How can it lead to more robust and predictable code?
47. Describe the use of `namedtuple` for creating simple, immutable data structures. When is it preferred over a `dataclass`?
48. How do you implement thread-safe data structures in Python? Discuss synchronization primitives like `Lock` and `RLock`.
49. Explain the difference between `threading` and `multiprocessing` in Python. When would you choose one over the other?
50. Discuss the role of `asyncio.Task` and `asyncio.Future` in asynchronous programming.
51. How do you handle cancellation of `asyncio` tasks? Provide an example.
52. Explain the concept of backpressure in asynchronous systems and how `asyncio` helps manage it.
53. Describe the use of `asyncio.Queue` for inter-task communication in an asynchronous application.
54. How do you perform concurrent HTTP requests efficiently using `aiohttp` or similar libraries?
55. Discuss the challenges of debugging asynchronous Python code and common strategies to overcome them.
56. Explain the `await` keyword and its role in `asyncio`. What happens under the hood?
57. Describe the `async with` statement and its use with asynchronous context managers.
58. How do you test asynchronous Python code effectively? Discuss mocking `async` functions.
59. What are `type aliases` and `NewType` in Python typing? Provide examples of their use cases.
60. Explain the concept of `Generics` in Python typing. How do they enable writing flexible and type-safe code?
61. Discuss the use of `TypedDict` for defining dictionary schemas with type hints.
62. How do you handle optional values and `None` safely with type hints in Python?
63. Describe the `match` statement (structural pattern matching) introduced in Python 3.10. Provide a practical example.
64. Explain the concept of `f-strings` and their advantages over older string formatting methods.
65. Discuss the use of `pathlib` for working with file paths. Provide examples of common operations.
66. How do you effectively use `subprocess` to run external commands in Python? Discuss security considerations.
67. Describe the `collections.deque` and its performance characteristics compared to a list for queue-like operations.
68. Explain the concept of a `weakref` in Python. When would you use it?
69. How do you handle internationalization and localization (i18n/l10n) in a Python application?
70. Discuss the use of `enum` for defining sets of symbolic names. Provide an example.
71. Explain the difference between `abstract base classes (ABCs)` and `interfaces` in Python. How do you define an ABC?
72. How do you manage database interactions in a Python application? Compare ORMs like SQLAlchemy with direct SQL.
73. Describe the principles of RESTful API design. How would you implement a RESTful API in Python?
74. Discuss the use of `unittest.mock` for testing Python code. Provide examples of patching and spying.
75. Explain the concept of test-driven development (TDD) and how you apply it in Python.
76. How do you ensure code style and formatting consistency in a Python project? Discuss `Black`, `isort`, and `Flake8`.
77. Describe the continuous integration/continuous deployment (CI/CD) pipeline for a Python application. What tools would you use?
78. What are common security vulnerabilities in Python applications, and how do you mitigate them?
79. Explain the concept of dependency inversion principle (DIP) and how it applies to Python.
80. Discuss the use of `property` decorators for controlled attribute access in Python classes.
81. How do you handle concurrency and parallelism in Python beyond the GIL? Discuss `multiprocessing` and `asyncio`.
82. Describe the `sys` module and its utility for interacting with the Python interpreter.
83. Explain the `os` module and its common functions for interacting with the operating system.
84. How do you work with JSON data in Python? Discuss serialization and deserialization.
85. Discuss the use of `pickle` for object serialization. What are its security implications?
86. Explain the concept of a `heapq` in Python. Provide an example of its use for priority queues.
87. How do you implement a custom iterator for a complex data structure?
88. Describe the `typing.Self` type hint and its utility in class methods and constructors.
89. Explain the concept of `Literal` types in Python typing. Provide an example.
90. Discuss the use of `Union` and `Optional` for expressing type variations.
91. How do you handle circular imports in Python? What are common strategies to avoid them?
92. Describe the `collections.ChainMap` and its use cases for combining multiple dictionaries.
93. Explain the `zip` function and its applications for iterating over multiple iterables.
94. How do you use `map`, `filter`, and `reduce` (from `functools`) effectively in Python?
95. Discuss the `any` and `all` built-in functions. Provide examples.
96. Explain the `__getattr__`, `__getattribute__`, and `__setattr__` methods. When would you use each?
97. Describe the `super()` function and its role in cooperative multiple inheritance.
98. How do you implement custom comparison methods (`__eq__`, `__lt__`, etc.) for Python objects?
99. Discuss the `hash()` function and its importance for objects used in sets and dictionary keys.
100. Explain the concept of `data classes` with `slots=True`. What are the benefits?
