## naa7
```python
class Attributes:
    
    @staticmethod
    def coding() -> tuple:
        langs = {
            'good': ['Python'],
            'intermediate': ['Java', 'Shell', 'C', 'C++'],
            'learning': ['C#', 'JavaScript', 'Assembly', 'PHP']
        }
        web_development = ['HTML', 'CSS']
        libraries = ['React', 'Redux', 'Sequelize']
        frameworks = ['Node.js', 'Express.js']
        databases = ['MySQL', 'PostgreSQL']
        environments = ['Terminal', 'VSCode', 'IntelliJ']
        
        return langs, web_development, libraries, frameworks, databases, environments
    
    @staticmethod
    def solo_projects() -> tuple:
        android = ['Flixster', 'SimpleTweet']
        discord = ['NaaGPT']
        general = ['databaser']
        linux = ['cipher_utility', 'cryptalight', 'work_timer',
                 'ressor_utility', 'git_utility']
        unity = ['pop_the_balloons']
        fullstack = ['chrive']
        
        return android, discord, general, linux, unity, fullstack
    
    @staticmethod
    def group_projects() -> tuple:
	discord = ['NashArt']
	unity = ['Vision']
	fullstack_web_apps = ['CrudApp', 'Wint']

	return discord, unity, fullstack_web_apps
```
