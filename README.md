# pyascii

https://github.com/Slinky802/pyascii

**pyascii** is a Python library for converting images into ASCII art, using various methods and supporting several languages. It offers customization options, such as output size, ASCII characters used, and output format (text or list of lists).

## Contents
- [Installation](#installation)
- [Use](#use)
- [Features](#features)
- [License](#license)
- [Contribute](#Contribute)
- [Contact](#Contact)

---

## Installation

To install the library, use pip :

``` bash
pip install pyascii
```

---

## Use
Basic example of converting an image to ASCII:

```python
import pyascii

# Converts an image to ASCII with default parameters
ascii_art = pyascii.image_to_ascii(
    image_link=“path/to/image.jpg”,
    method=“text”,
    size=(100, 100),
    chars=None
)

print(ascii_art)
```

---

## Features

**Output Size:** Defines the dimensions (width, height) of the output ASCII image.

**ASCII characters:** Modifies the list of ASCII characters used, from more to less dense, to obtain the desired output.

**Return Method:** Choice between “list” (list of lists) or “text” (printable text) for output format.

**Supported languages:**

 - en : English

 - fr : French

 - es : Spanish

 - de : German

 - it: Italian

 - pt: Portuguese

 - ru: Russian

 - zh: Chinese

 - ja: Japanese

 - ko: Korean

 - ar : Arabic

Use ```pyascii.ascii_help(language)``` to display instructions according to the selected language.

---

## License
This project is licensed under the MIT license - see the LICENSE file for details.

---

## Contribute

We welcome contributions to improve and expand the **pyascii** library! Whether you want to add a feature, fix a bug, or enhance the documentation, follow these steps to contribute:

### Steps to Contribute

1. **Fork the Repository**: Create a copy of the project on your GitHub account using the "Fork" button.

2. **Clone the Project**: Clone your fork locally to work on the code.
   ```bash
   git clone https://github.com/Slinky802/pyascii
   cd pyascii
   ```
3. **Create a New Branch**: Before making changes, create a new branch for your work.
    ```bash
    git checkout -b my_new_feature
    ```
4. **Make Your Changes**: Add your modifications or new features.

5. **Test Your Code**: Ensure your code works correctly by testing it and adhering to the project's standards.

6. **Submit a Pull Request (PR)**: Once your changes are ready, push them to your fork, then submit a PR to the master branch of this repository.

 - Describe your changes and their purpose.
 - Mention any related issues you've resolved.
 - Request a code review.
 
### Code Review Policy
To maintain the project's stability and security, we have implemented a branch protection policy:

 - Any changes to the main branch must go through a Pull Request.
 - Each PR requires a review and may need approval before merging.
 - Only administrators and trusted contributors can merge approved PRs.

---

## Contact
Created by Alexandre Poggioli - alexandrepoggioli09@gmail.com

More information on https://slinky-presentation.netlify.app