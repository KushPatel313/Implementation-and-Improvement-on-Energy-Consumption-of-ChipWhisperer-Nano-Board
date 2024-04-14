# Energy Usage Analysis of ChaCha20-Poly1305 Using ChipWhisperer

This repository contains the implementation and energy analysis of the ChaCha20-Poly1305 cryptographic algorithm on an ARM Cortex-M0 platform, specifically using the ChipWhisperer Nano board. The focus is on understanding the energy consumption associated with key cryptographic operations and exploring optimizations to enhance energy efficiency.

## Abstract

This study evaluates the energy consumption of the ChaCha20-Poly1305 algorithm focusing on operations such as key generation, encryption, decryption, signature, and verification. The analysis is performed on the ChipWhisperer Nano board, and optimizations are suggested to reduce energy usage while maintaining algorithmic integrity and functionality.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Experimental Setup](#experimental-setup)
- [Results](#results)
- [Contributing](#contributing)
- [Acknowledgments](#acknowledgments)
- [References](#references)

## Installation

To set up the project environment:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-github-username/chacha20-poly1305-energy-analysis.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd chacha20-poly1305-energy-analysis
   ```

3. **Install necessary Python libraries:**

   ```bash
   pip install -r requirements.txt
   ```

## Usage

To run the analysis, execute the main script:

```bash
python analyze_energy.py
```

Replace `analyze_energy.py` with the appropriate script name that you use for your analysis. Ensure that the ChipWhisperer and the target device are correctly configured and connected as per the instructions in the script comments.

## Experimental Setup

- **Code Selection and Compilation:** Select the appropriate cryptographic implementations for the ChipWhisperer platform.
- **Hex File Conversion:** Convert compiled binaries to HEX format suitable for uploading to the target.
- **Capturing Power Traces:** Execute the cryptographic operations while capturing power traces with the ChipWhisperer.

## Results

The results section outlines the analysis of power consumption and the effectiveness of optimization techniques. Results indicate a small percentage decrease in energy consumption with optimizations. For detailed results and graphs, see the `results` folder.

## Contributing

Interested in contributing? Great! You can contribute by:

- Improving the existing code for better energy efficiency.
- Extending the analysis to other cryptographic algorithms.
- Improving documentation or adding educational content.

Please send a pull request or open an issue to discuss potential changes/additions.

## Acknowledgments

Special thanks to the faculty and peers at Carleton University, whose guidance and support made this research possible. We are particularly grateful to our project supervisor for their invaluable insights and encouragement throughout this project.

## References

- [ChaCha20-Poly1305 Algorithm](https://datatracker.ietf.org/doc/html/rfc8439)
- [ChipWhisperer Documentation](https://rtfm.newae.com/Capture/ChipWhisperer-Nano/)
- [Jupyter Notebook Introduction](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/what_is_jupyter.html)

For a full list of references, please refer to the [References](#references) section.
```
