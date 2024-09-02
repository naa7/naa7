## naa7
```python
class Attributes:
    
    @staticmethod
    def coding() -> tuple:
        languages = ['Python', 'Java', 'C', 'C++', 'JavaScript', 'TypeScript', 'HTML', 'CSS']
        frameworks = ['React', 'Redux', 'Next.js', 'Node.js', 'Express.js', 'Django', 'Flask', 'TailwindCSS']
        libraries = ['Pandas', 'NumPy', 'Seaborn', 'Matplotlib', 'PyTorch', 'TensorFlow', 'Keras', 'scikit-learn',
                     'Langchain', 'HuggingFace', 'Sequelize']
	tools_and_technologies = ['Git', 'Npm', 'Github', 'Figma', 'Jira', 'Docker', 'Sentry', 'Buildkite', 'Redis',
                                  'Bash', 'Ollama', 'Postman']
        databases = ['MySQL', 'PostgreSQL', 'MongoDB', 'ChromaDB']
	environments = ['Terminal', 'VSCode', 'IntelliJ']
	other = ['Kanban', 'Scrum', 'JWT', 'OAuth2', 'Jest', 'Pytest', 'RESTful APIs', 'Confluence']
        
        return languages, frameworks, libraries, tools_and_technologies, databases, environments, other
    
    @staticmethod
    def solo_projects() -> tuple:
        general = ['databaser', 'git_utility', 'cipher_utility', 'cryptalight', 'work_timer', 'ressor_utility',
		   'AWS_flow_log_parser']
        fullstack = ['chrive', 'Portfolio', 'url_shortener', 'receipt_processor']
        android = ['Flixster', 'SimpleTweet']
        discord = ['NaaGPT']
        unity = ['pop_the_balloons']
        
        return  general, fullstack, android, discord, unity
    
    @staticmethod
    def team_projects() -> tuple:
	fullstacks = ['HikerAI', 'NOK-Draw', 'Wint', 'CrudApp']
	discord = ['NashArt']
	unity = ['Vision']

	return fullstack, discord, unity
```
