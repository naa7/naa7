## naa7
class Attributes(naa7):

	@staticmethod
	def coding() -> tuple:
		langs = {
			'good':   ['python'],
			'intermediate': ['java', 'shell', 'c', 'c++'],
			'learning': ['c#', 'js', 'asm']
		}
		environnement = ['terminal', 'vscode', 'intelliJ']
		
		return langs, environnement
	
	@staticmethod
	def projects() -> tuple:
		android = ['Flixster', 'SimpleTweet']
		discord   = ['NaaGPT']
		linux = ['Cipher_utility', 'work_timer', 'ressor_utility', 'git_repo_utiliy']
		unity = ['pop_the_balloons']
		return android, discord, linux, unity