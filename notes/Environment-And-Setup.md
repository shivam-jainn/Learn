**** Some of the things have been picked from ChatGPT , Reddit , and various sources . This isn't a personal piece of advice or opinion , but a way to share knowledge . I can be wrong , and if you have some suggestion to edit something please point it out . Thanks !


Environment setup for vscode

```json
{
  "recommendations": [
    "github.copilot",
    "github.copilot-chat",
    "tamasfe.even-better-toml",
    "ms-toolsai.jupyter",
    "ms-python.mypy-type-checker",
    "ms-python.vscode-pylance",
    "KevinRose.vsc-python-indent",
    "charliermarsh.ruff",
    "njpwerner.autodocstring",
    "usernamehw.errorlens"
  ]
}
```
and go through this : https://datalumina.clickup.com/docs/9015213037/d/h/8cnjezd-17675/ddd52c673443975

-----------
Cool tips and tricks 

1. Go to vscode extension settings , search for "jupyter interactive window execute selection"
2. Enable it
3. Go to your python (.py) file and press shift + enter (this works for scripts , not for full blown servers)
4. You will get options like variables on right split screen , this is where you can see the variable's data in memory (similar to a debugger)

-------------

Best practises 

Try using the following repo template (https://cookiecutter-data-science.drivendata.org/)
>   https://github.com/datalumina/datalumina-project-template

Use `uv` as package manager 
Why? 1. Manage python version 2. Manage venv 3. Manage deps 

