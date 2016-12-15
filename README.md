# sublime-setting
Sublime setting


## mocha runner for Mac

```json
{
  "cmd": ["mocha", "--recursive", "--reporter", "spec", "$file"],
  "file_regex": "^(..[^:]*):([0-9]+):?([0-9]+)?:? (.*)$",
  "working_dir": "${project_path:${folder:${file_path}}}",
  "selector": "source.js",
  "path": "$PATH:/usr/local/bin"
}
```
