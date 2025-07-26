# Python PDF Compare

## Modules Used

### `difflib`
A Python module that contains functions that allow comparison of sets of data. This module provides tools for comparing sequences and finding differences between them.

### `SequenceMatcher`
A class from the `difflib` module used to compare pairs of input sequences. It provides methods to find the longest common subsequence and calculate similarity ratios between sequences.

## Functions Used

### `hash_file(string $algo, string $filename, bool $binary = false)`
A function that generates the hash of a file using a specified algorithm.
- **Parameters:**
  - `$algo` (string): The hashing algorithm to use
  - `$filename` (string): The path to the file to hash
  - `$binary` (bool): Whether to return binary output (default: false)
- **Returns:** Hash of the specified file

### `object.hexdigest()`
A method that returns the digest of the data as a string containing only hexadecimal digits.
- **Returns:** String representation of the hash in hexadecimal format

### `fileObject.read(size)`
A method that reads and returns a specified number of bytes from a file object.
- **Parameters:**
  - `size`: The number of bytes to read from the file
- **Returns:** The specified number of bytes from the file as a string or bytes object
