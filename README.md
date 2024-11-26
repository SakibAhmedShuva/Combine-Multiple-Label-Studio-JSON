# Combine Multiple Label Studio JSON Files

A Python utility to merge multiple JSON files exported from Label Studio into a single consolidated JSON file.

## Overview

This tool simplifies the process of combining multiple JSON files exported from Label Studio into one comprehensive JSON file. It's particularly useful when dealing with multiple annotation files that need to be consolidated for further processing or analysis.

## Features

- Combines multiple JSON files into a single file
- Handles different file encodings (UTF-8 and Latin-1)
- Robust error handling for file operations
- Preserves JSON structure and formatting
- Memory-efficient processing
  
Sample JSON file provided in "samples" folder.

## Requirements

- Python 3.x
- No additional dependencies required

## Installation

Clone the repository:

```bash
git clone https://github.com/SakibAhmedShuva/Combine-Multiple-Label-Studio-JSON.git
cd Combine-Multiple-Label-Studio-JSON
```

## Usage

1. Open the `combine-ls-json.ipynb` notebook in Jupyter Notebook or JupyterLab.

2. Modify the `directory` path to point to your JSON files:
```python
directory = r'path/to/your/json/files'
```

3. (Optional) Modify the output file name:
```python
output_file = 'combined_data.json'
```

4. Run the notebook cells to combine your JSON files.

## Code Structure

The main functionality is divided into two key functions:

- `combine_json_files(directory)`: Reads and combines JSON files from the specified directory
- `save_combined_data(combined_data, output_file)`: Saves the combined data to a new JSON file

## Error Handling

The script includes comprehensive error handling for:
- File encoding issues
- JSON parsing errors
- File read/write operations
- General exceptions

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

Sakib Ahmed Shuva

## Acknowledgments

- Label Studio team for their excellent annotation tool
- Contributors and users of this utility

## Support

If you encounter any issues or have questions, please [open an issue](https://github.com/SakibAhmedShuva/Combine-Multiple-Label-Studio-JSON/issues).
