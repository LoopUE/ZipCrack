---

# ZipCrack

ZipCrack is a Python script for brute forcing password-protected zip files using a wordlist. It is fully open source and available on GitHub.

## GitHub Repository

- Repository Link: [GitHub.com/LoopUE/ZipCrack](https://github.com/LoopUE/ZipCrack)

## Prerequisites

- Python 3.x
- Required Python libraries (`zipfile`, `argparse`)

## Usage

1. Clone the repository or download the `ZipCrack.py` script.
2. Open a terminal or command prompt.
3. Navigate to the directory containing the script.
4. Run the script with the following command:

   ```bash
   python ZipCrack.py <path_to_zipfile> <path_to_wordlist>
   ```

   Replace `<path_to_zipfile>` with the path to your zip file and `<path_to_wordlist>` with the path to your wordlist file.

## Arguments

- `zipfile`: Path to the zip file you want to brute force.
- `wordlist`: Path to the wordlist file containing potential passwords.

## Example

```bash
python ZipCrack.py example.zip wordlist.txt
```

## Notes

- This script performs a brute force attack by trying each password from the wordlist until the correct password is found.
- Ensure that you have permission to perform brute force attacks and are using it responsibly and ethically.

---
