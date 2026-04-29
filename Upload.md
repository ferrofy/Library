# 📦 Build and Upload Python Package

## 📁 Steps

1. 🛠️ **Build dist/***

```bash
python -m build
```

4. 🚀 **Upload the package to PyPI using Twine**

```bash
twine upload dist/*
```

5. **Add Your API Key**

# ⚠️ Note

- 🔢 Always upgrade the version number in setup.py before building, otherwise upload may fail.