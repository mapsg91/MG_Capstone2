kagglehub installation and import required

```python
import kagglehub

# Download latest version
path = kagglehub.dataset_download("valbauman/student-engagement-online-learning-supplement")

print("Path to dataset files:", path)
# copied dataset files to working directory under "data"
```