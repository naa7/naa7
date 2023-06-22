## naa7
```python
class Attributes(naa7):

	@staticmethod
	def coding() -> tuple:
		langs = {
			'good':   ['python'],
			'intermediate': ['java', 'shell', 'c', 'c++'],
			'learning': ['c#', 'js', 'asm']
		}
		libraries = ['react', 'redux']
		frameworks = ['Node.js', 'Express.js']
		environnement = ['terminal', 'vscode', 'intelliJ']
		
		return langs, libraries, frameworks, environnement
	
	@staticmethod
	def solo_projects() -> tuple:
		android = ['Flixster', 'SimpleTweet']
		discord   = ['NaaGPT']
		general = ['databaser']
		linux = ['cipher_utility', 'cryptalight', 'work_timer', 'ressor_utility', 'git_repo_utiliy']
		unity = ['pop_the_balloons']
		return android, discord, general, linux, unity
		
	@staticmethod
	def group_projects() -> tuple:
		unity = ['Vision']
		return unity
```
