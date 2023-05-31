# nushell-cheatsheet


```nushell
# list files and content

ls *-session.py|each {|file| {name: $file.name, content: (open $file.name|lines) }}
```
