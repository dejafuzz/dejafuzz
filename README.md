```js
class BackendEngineer {

    constructor() {
        this.name = "Fajri Ikmal Ghozali";
        this.role = "Backend Engineer";

        this.specialization = [
            "Scalable Backend Systems",
            "RESTful APIs",
            "System Architecture"
        ];

        this.techStack = {
            backend: ["Laravel", "Node.js", "Golang"],
            database: ["MySQL", "PostgreSQL", "Redis", "MongoDB"],
            tools: ["Docker", "Git", "Linux", "Postman"]
        };

        this.currentlyLearning = [
            "System Design",
            "Microservices",
            "Performance Optimization"
        ];
    }

    introduce() {
        return `Hi 👋 I'm ${this.name}, a ${this.role} focused on building clean, scalable, and maintainable systems.`;
    }
}

const me = new BackendEngineer();

console.log(me.introduce());
```
