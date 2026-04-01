Compression Algorithms Comparison Tool

A comprehensive GUI application that compares five popular data compression algorithms: Golomb, LZW, RLE, Huffman, and Arithmetic Encoding. Input text and instantly see detailed compression metrics, efficiency analysis, and optimal algorithm recommendations.

✨ Features

Interactive GUI built with Tkinter
Five Compression Algorithms with real-time comparison
Comprehensive Metrics:
Bits before/after encoding
Compression ratio
Entropy calculation
Average code length
Efficiency scores
Character probabilities
Optimal Algorithm Detection - Automatically identifies the best algorithm for your input
Detailed Results Display with formatted output

Quick Start
Prerequisites
Python 3.7+
Tkinter (usually included with Python)

git clone https://github.com/yourusername/compression-comparison.git
cd compression-comparison

python compression_tool.py

📖 Usage
Launch the application
Enter text in the input field
Click "Encode" to analyze
View results - detailed metrics for all algorithms
Click "Show Results" to expand the full analysis
Optimal algorithm is automatically highlighted

📈 Example Output

Golomb Encoding Results:
Bits before encoding: 104
Bits after encoding: 12
Compression ratio: 8.67
Entropy: 1.23

LZW Compression Results:
Compression Ratio: 4.2
Efficiency: 0.89

Optimal Algorithm: Huffman Compression

🛠️ Technical Details

Key Metrics Calculated
Compression Ratio: Original Bits / Compressed Bits
Entropy: -∑(p*log₂(p))
Efficiency: Entropy / Average Code Length
Average Length: Total Compressed Bits / Symbols
Algorithm Implementations
Golomb: Unary + binary encoding with parameter M=2
LZW: Dynamic dictionary building (codes 0-255 start)
RLE: Run-length encoding with count+character pairs
Huffman: Optimal prefix codes via priority queue
Arithmetic: Range encoding with symbol probabilities

🔧 Customization
Modify algorithm parameters in the encode_text() function:




M = 2  # Golomb parameter
# Adjust for different text characteristics

📁 File Structure

compression_tool.py  # Main application
README.md           # This file


👩‍💻 Author
Nourhan Mohammed  
Computer Science Student | Data Analyst
