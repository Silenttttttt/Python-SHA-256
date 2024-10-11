# Custom SHA-256 Implementation

## Overview

This project is a custom implementation of the SHA-256 hashing algorithm, developed purely for educational purposes. It was created to gain a deeper understanding of how the SHA-256 algorithm functions internally. This implementation is not optimized for performance or security and should **not** be used in any production environment or for any security-sensitive applications.

## Features

- Implements the SHA-256 hashing algorithm from scratch.
- Provides a simple function to hash a given message.
- Includes an example usage to demonstrate how the function works.

## Usage

To use this implementation, simply call the `sha256` function with a byte string as the input message. The function will return the SHA-256 hash of the message as a hexadecimal string.

```python
message = b"hello world"
custom_hash = sha256(message)
print(f"Custom SHA-256: {custom_hash}")
```

## Important Note

This implementation is for educational purposes only. It is not intended for use in any real-world applications. For secure and efficient hashing, please use a well-tested library such as Python's built-in `hashlib` module.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
