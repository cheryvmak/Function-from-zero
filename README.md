[![Codespaces Prebuilds](https://github.com/cheryvmak/Function-from-zero/actions/workflows/codespaces/create_codespaces_prebuilds/badge.svg)](https://github.com/cheryvmak/Function-from-zero/actions/workflows/codespaces/create_codespaces_prebuilds)

[![CI](https://github.com/cheryvmak/Function-from-zero/actions/workflows/main.yml/badge.svg)](https://github.com/cheryvmak/Function-from-zero/actions/workflows/main.yml)

# Function-from-zero
A Repo to learn function

## Step 1: Configure Development Environment

* Configure Github Codespaces or equivalent (e.g Cloud9, etc.)
* Create Scaffold for structure of project:'Makefile, requirements.txt'
* Optional(setup virtualenv),(install  ipython outside requirement.txt)

## Step 2: Get interactive debugging working
* Use iPython and ipdb
'''
python
x = 1
y = 2
import ipdb; ipdb.set_trace()
print(x+y)  
'''

