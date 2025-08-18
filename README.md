"""
starter-kit
------------

A minimal single-file GitHub-ready Python project.

Features:
- Core logic
- Embedded test function
- MIT License info
- Can be used as a script or library
"""

__version__ = "0.1.0"
__license__ = "MIT"
__author__ = "YOUR NAME"


# =========================
# Core Logic
# =========================
def hello() -> str:
    return "Hello, GitHub!"


if __name__ == "__main__":
    print(hello())


# =========================
# Tests (run with pytest)
# =========================
def test_hello():
    assert hello() == "Hello, GitHub!"


# =========================
# MIT License
# =========================
__license_text__ = """
MIT License

Copyright (c) 2025 YOUR NAME

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

[Full MIT license text]
"""
