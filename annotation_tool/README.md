# Annotation Tool 

## How to run locally

If you haven't already, install the required dependencies

```bash
pip install -r annotation_tool/requirements.in
```

From the project root directory, run:

```bash
streamlit run annotation_tool/app.py
```

Done! You can now use the app in your browser.

## Requirements
Streamlit uses the requirements.txt file in the app directory to install python package dependencies.

To pin package versions we use `pip-compile` from `pip-tools`.
Similar to pip, pip-tools must be installed in each of your project's virtual environments.

Now, run pip-compile requirements.in

```$ pip-compile requirements.in```
