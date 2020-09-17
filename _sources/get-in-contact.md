# Get in Cotact: Use github

This page: A short guides roundtrip how you create a respository and invite others



## Github

1. Register or log in at Github 
2. Create a new repository Public is important - we need it later for hosting.
3. ... or import code from ... -> https://github.com/hawla-dsci-lab/dsci-lab
4. Generating a new SSH key: https://docs.github.com/en/enterprise/2.15/user/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent
5. Adding a new SSH key to your GitHub account:
https://docs.github.com/en/enterprise/2.15/user/articles/adding-a-new-ssh-key-to-your-github-account
6. Terminal: 
```sh
git clone git@github.com......
``` 
7. GitHub Pages and Actions: https://jupyterbook.org/publish/gh-pages.html
      Terminal: 
      ```sh 
      pip install ghp-import
      ```
      ```sh
        ghp-import -n -p -f <repositoryName>/_build/html
      ``` 
8. Live: https://<yourGitHubName>.github.io/<repositoryName>/
9. Go to your Repositroy -> Settings -> Manage access: Here you can invite others 
 


