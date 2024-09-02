## naa7
```python
class Attributes:
    
    @staticmethod
    def coding() -> tuple:
        languages = ['Python', 'Java', 'C', 'C++', 'JavaScript', 'TypeScript', 'HTML', 'CSS']
        frameworks = ['React', 'Redux', 'Next.js', 'Node.js', 'Express.js', 'Django', 'Flask', 'TailwindCSS']
        libraries = ['Pandas', 'NumPy', 'Seaborn', 'Matplotlib', 'PyTorch', 'TensorFlow', 'Keras', 'scikit-learn', 'HuggingFace', 'Sequelize']
	tools_and_technologies = ['Git', 'Npm', 'Github', 'Figma', 'Jira', 'Docker', 'Sentry', 'Buildkite', 'Redis', 'Bash', 'Ollama', 'Postman']
        databases = ['MySQL', 'PostgreSQL', 'MongoDB', 'ChromaDB']
	environments = ['Terminal', 'VSCode', 'IntelliJ']
	other = ['Kanban', 'Scrum', 'JWT', 'OAuth2', 'Jest', 'Pytest', 'RESTful APIs', 'Confluence']
        
        return languages, frameworks, libraries, tools_and_technologies, databases, environments, other
    
    @staticmethod
    def solo_projects() -> tuple:
        android = ['Flixster', 'SimpleTweet']
        discord = ['NaaGPT']
        general = ['databaser', 'git_utility']
        linux = ['cipher_utility', 'cryptalight', 'work_timer',
                 'ressor_utility']
        unity = ['pop_the_balloons']
        fullstack = ['chrive', 'Portfolio', 'url_shortener', 'receipt_processor']
        
        return android, discord, general, linux, unity, fullstack
    
    @staticmethod
    def group_projects() -> tuple:
	discord = ['NashArt']
	unity = ['Vision']
	fullstack_web_apps = ['CrudApp', 'Wint', 'NOK-Draw', 'HikerAI']

	return discord, unity, fullstack_web_apps
```
