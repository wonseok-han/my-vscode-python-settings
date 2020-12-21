# my-vscode-python-settins

```json
{
    "editor.formatOnSave": true,
    "python.linting.pylintEnabled": false,
    "python.linting.flake8Enabled": true,
    "python.linting.flake8Args": [
        "--init-hook",
        "import sys; sys.path.append('<path to folder your module is in>')",

        "--max-line-length=88"
        
    ],
    "python.formatting.provider": "black",
    "python.linting.enabled": true,    
    "python.pythonPath": "/Users/doul/opt/anaconda3/envs/py38/bin/python"
}
```json
