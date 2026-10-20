# Awesome-Diffusion-Models-Generative-AI

# confirm no leftover sindresorhus/awesome references
Select-String -Path README.md -Pattern 'sindresorhus/awesome'

# confirm the Support section and sponsor link are present
Select-String -Path README.md -Pattern '## .*Support','github.com/sponsors/ishandutta2007'

gh repo view ishandutta2007/$repo_name --web
