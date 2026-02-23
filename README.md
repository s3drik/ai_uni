# ai_uni
this repository created for putting csv files for using at university ai_basics lesson and code files of them.

## How to Get the Raw Format of a File from GitHub

To use a file (e.g., a CSV) directly in your code, you need its **raw** URL. Follow these steps:

1. Navigate to the file you want in this repository on GitHub.
2. Click the **Raw** button (top-right area of the file view).
3. Copy the URL from your browser's address bar.

The raw URL will look like this:
```
https://raw.githubusercontent.com/s3drik/ai_uni/main/<filename>
```

### Example (using pandas in Python)
```python
import pandas as pd

url = 'https://raw.githubusercontent.com/s3drik/ai_uni/main/your_file.csv'
df = pd.read_csv(url)
```
