# dev-tools-and-configs
Repository with tips to help during development

## Git configurations

Edit configurations to all projects for my user
```bash
git config --global --edit 

Into de config file add:
[alias]
        s = !git status -s
        c = !git add --all && git commit -m 
        l = !git log --pretty=format:'%C(blue)%h %C(red)%d %C(white)%s - %C(cyan)%cn, %C(green)%cr'
```

Field Name | Descripton
------------ | -------------
**%h** | commit hash
**%d** | commit branch
**%s** | commit message
**%cn** | name of who did the commit
**%cr** | relative date of the commit
**%C(<colos>)** | color to the text
  
Conventional Commits:
https://www.conventionalcommits.org/
