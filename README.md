# Log File Analysis Tool

## Overview
A Python script to analyze web server log files for:
- Requests per IP address
- Most accessed endpoint
- Suspicious activity detection

## Usage
1. Place your log data in `sample.log`.
2. Run the script:
   ```bash
   python log_analysis.py
   ```
3. View results in the terminal and `log_analysis_results.csv`.

## CSV Output Structure
- **Requests per IP**: `IP Address`, `Request Count`
- **Most Accessed Endpoint**: `Endpoint`, `Access Count`
- **Suspicious Activity**: `IP Address`, `Failed Login Count`

## License
Licensed under the [MIT License](LICENSE).
