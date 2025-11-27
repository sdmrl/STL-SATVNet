# Dataset
The main dataset files are stored externally due to their size.
​​Download link: https://pan.baidu.com/s/13Fc23RyZAgvyvLTC1EQzuw?pwd=hvc8
# Usage Instructions

## Step-by-Step Process

1. **Run STL decomposition** to generate:
   - `seasonal_data.txt`
   - `residual_data.txt` 
   - `trend_data.txt`

2. **Manually update** the files in the `search_sequence` directory as needed

3. **Execute models in order**:
   - Run `demo.py`
   - Run `mlp.py` 
   - Run `sarima.py`

4. **Calculate metrics**:
   - Run `calculate.py` to obtain SMAPE and MASE scores

## Important Notes
- **Check file paths**: Ensure all file paths in the scripts are correctly configured for your system
- **Execution order**: Follow the specified sequence for accurate results
