# cat-dir-content

- A Bash script for printing the contents of files in a directory using the `cat` command for efficient viewing of multiple files.
- Accepts the path to the directory as a command line argument and is useful for DAG and Prompt Engineers.

## URL 
https://patimejia.github.io/cat-dir-content/

## Installation

1. Open your terminal.
2. Download the script from the GitHub repository using this command:
   ```
   wget https://patimejia.github.io/cat-dir-content/cat-dir-content.sh
   ```
3. Set the script file's executable permission by running this command:
   ```
   chmod +x cat-dir-content.sh
   ```

## Installation

1. Open your terminal.
2. Ensure that you have `wget` installed on your system by running the command:
   ```
   which wget
   ```
   If the command returns a path, `wget` is already installed. If it returns nothing, you can install `wget` using a package manager such as `apt` or `brew`. For examples, 
   ```
   brew install wget
   ``
3. Download the script from the project's GitHub repository by running the following command:
   ```
   wget https://patimejia.github.io/cat-dir-content/cat-dir-content.sh
   ```
4. Set the executable permission on the script file using the following command:
   ```
   chmod +x cat-dir-content.sh
   ```

This will allow you to execute the script as a program.



## Usage:

1. Open your terminal.

2. Navigate to the directory where you saved the `cat-dir-content.sh` script.

3. Run the script by specifying the path to the directory as a command line argument. For example, to print the contents of all files in the directory `/path/to/directory`, run:

```
./cat-dir-content.sh /path/to/directory
```

Note: The path you specify must be relative to the location of the script file. If you saved the script in a different directory than the one you want to print the contents of, you must provide the full path to the directory you want to read from.

This will print the contents of all files in the specified directory using the `cat` command.

## Security Considerations

`cat-dir-content.sh` can be used to view the contents of any file in a directory, including sensitive files. Be sure to only use this script on directories and files that you trust, and do not execute it with superuser privileges.

Additionally, be cautious when downloading scripts from the internet, and verify the source and integrity of the script before executing it on your system.

## Contributing

Please create an issue in the GitHub repository if you encounter any bugs while using `cat-dir-content.sh`. Provide a detailed description of the problem along with the steps to reproduce it.

You can contribute to the project by submitting a pull request on the GitHub repository. Fork the repository, make your changes, and submit a pull request for review.

## License

`cat-dir-content.sh` is licensed under the MIT License. See [`LICENSE`](https://github.com/patimejia/cat-dir-content/blob/main/LICENSE) for more information.
