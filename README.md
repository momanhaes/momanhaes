<h1 align="center">Olá, visitante! Sou Matheus Manhães 👋</h1>

<p align="center">
    <a href="https://www.linkedin.com/in/mmanhaes/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the badge&logo=linkedin&logoColor=white"/></a>
    <a href="https://www.instagram.com/manhaesdev/"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/></a>
</p>

Tive meu primeiro contato com programação em 2010, trabalho com TI desde 2013, virei desenvolvedor de software profissional em 2019, mas sou entusiasta de tecnologia desde que me entendo por gente. Sou bacharel em Sistemas de Informação e adoro fazer parte de projetos da comunidade e hackathons. Ah, também amo aprender coisas novas, ouvir boa música e assistir filmes cult.

```typescript

interface ITech {
    backend: Array<string>;
    frontend: Array<string>;
    mobile: Array<string>;
    integration: Array<string>;
    testing: Array<string>;
    backend: Array<string>;
    database: Array<string>;
    devops: Array<string>;
}

interface IProfile {
    keywords: Array<string>;
    technologies: ITech;
    architecture: Array<string>;
}

const momanhaes: IProfile = {
    keywords: ["Frontend", "Developer", "Mobile-First", "Agile"],
    technologies: {
        backend: ["NodeJS", "Express", "C#", "Java", "JSF", "Spring"],
        frontend: ["Angular", "React", "JavaScript", "TypeScript", "HTML", "CSS", "SASS"],
        mobile: ["Ionic", "React Native"],
        integration: ["RestAPIs", "GraphQL"],
        testing: ["Jasmine", "Cypress", "JUnit"],
        database: ["Mongo", "MySQL", "PostgreSQL"],
        devops: ["AWS", "Microsoft Azure", "Jenkins", "Firebase", "Docker", "Kubernetes"],
    },
    architecture: ["Microservices", "Event-Driven", "Single Page Applications"],
};
```
