## Python install locations
	Frameworks (installed from Python.org):
	'/Library/Frameworks/Python.framework/Versions/'
	
	Installed from pyenv
	'~/.pyenv/versions/'
	
## Pipenv (Package manager for Python)
	pipenv shell --python <version> (create virtual environment with specified Python version)
	<ctrl-d>												(exit virtual environment shell)
	pipenv --rm											(delete virtual env. [be sure to remove Pipfile])	
	pipenv install <package>				(install package using pipenv)
	pipenv graph										(show currently installed packages)
	
## Pyenv (Manage multiple Python versions)
	pyenv help										(help)
	pyenv install --list 					(show all available Python versions)
	pyenv versions 								(show currently installed python versions)
	pyenv local  <python_version> (local Python version)
	pyenv global <python_version>	(global Python version) 
	
	### SOURCES
	https://realpython.com/intro-to-pyenv/#virtual-environments-and-pyenv

## Python commands
	python -V 										(check current Python version)
	





















## Virtualenv (not from standard library)
	pyenv virtualenv <python_version> <environment_name> (Create virtualenv with specific Python version)
	pyenv local myproject (Activate environment)
	
	(To delete an environment, make sure it is deactivated and go to:
	'~/.pyenv/versions/<python_version>/envs/')
	
		AND	
		
	'/Users/<user>/.pyenv/versions/<environment_name>'
	
	pyenv shell . (Deactivate	environment)
	
	find $HOME -name "*activate" -type f		(Looks for the activate script. Doesn't matter if its venv or virtualenv)

	
	
	

## Pyenv-virtualenv (uses both pyenv and virtualenv together)
