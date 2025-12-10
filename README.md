class Elahe:
    def __init__(self):
        self.name = "Elahe Moharrampour"
        self.pronouns = ["she", "her"]
        self.major = "Computer Science Student"
        self.role = "Node.js Developer"
        self.languages = ["Python", "JavaScript"]

    def getEmail(self):
        return "Eli.mhrp1395@gmail.com"

    def getAge(self):
        b = date(2004, 4, 8)
        t = date.today()
        return t.year - b.year - ((t.month, t.day) < (b.month, b.day))

    def getStack(self):
        return {
            "backEnd": {
                "frameworks": ["Express.js", "Nest.js"],
                "microServiceTools": ["gRPC", "RabbitMQ"],
                "realTimeTools": ["socket.io"],
                "databases": ["MongoDB", "PostgreSQL", "Redis"],
                "architectures": ["MVC", "Clean Architecture", "SOLID"],
                "apiTools": ["Postman", "Swagger"],
            }
        }
