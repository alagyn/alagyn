README generator how-to:

Put header stuff in `header.md`
Put footer stuff in `footer.md`

Add new projects with a toml file in the `projects` folder like this:
```toml
name = "MyProject"
url = "https://mywebsite.com"
langs = ["Java", "JavaScript"] # Currently only accepts C++, Java, or JavaScript
# But you can have arbitrary badges here
otherBadges = [
    "![Vue](https://img.shields.io/badge/Vue%20js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D)",
]
desc = """
This is a freeform markdown project description  
make it multiline if you want
"""
logo = "images/MyLogo.png"
```

Then add the path to `projects.toml` (just the filename, no `.toml` needed):
```toml
projects = [
    "project1",
    "project2",
    "project3"
]
```

