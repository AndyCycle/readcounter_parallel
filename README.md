
## Troubleshooting

- **Conda Environment Activation Failed:**
  - Ensure your_conda_env is installed and the environment exists.
- **GNU Parallel Not Found:**
  - The script attempts to install GNU Parallel via Conda. Ensure you have internet access and Conda is properly configured.
- **No BAM Files Found:**
  - Verify that `BAM_DIR` points to the correct directory containing `.bam` files.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- **hmmcopy_utils:** The `readCounter` tool is sourced from the [hmmcopy_utils GitHub repository](https://github.com/shahcompbio/hmmcopy_utils.git).

## Future Improvements

- **Dynamic Resource Allocation:** Adjust CPU and memory usage based on the size of BAM files.
- **Enhanced Logging:** Implement more detailed logging for better monitoring and debugging.
- **User Interface:** Develop a simple GUI for easier configuration and execution of the script.

---
