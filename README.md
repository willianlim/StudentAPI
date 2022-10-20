# `StudentAPI`

📚 Student API.

- Certification: 👉[`Getting Started With Spring Boot`](https://github.com/willianlim/StudentAPI/blob/master/img/certificate-of-completion-for-getting-started-with-spring-boot%20(1).pdf)👈

<p align="center">
    <img src="https://github.com/willianlim/StudentAPI/blob/master/img/stud.drawio.png" width="490">
</p>

## 📥 Installation

```bash
git clone https://github.com/willianlim/StudentAPI.git
```

## ✍ Usage

```json
GET:
http://localhost:8080/api/v1/student/
[
    {
        "id": 1,
        "name": "Alex",
        "email": "alex@gmail.com",
        "dob": "2004-01-05",
        "age": 18
    }
]

POST:
http://localhost:8080/api/v1/student/
{
    "name": "Maria",
    "email": "mariam.jamal@gmail.com",
    "dob": "2000-01-05",
    "age": 22
}

PUT:
http://localhost:8080/api/v1/student/?name=mariaaaaa
{
    "name": "mariaaaaa",
    "email": "mariam.jamal@gmail.com",
    "dob": "2000-01-05",
    "age": 22
}

DELETE:
http://localhost:8080/api/v1/student/1
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## 📝 License
- Licença de software [`LICENSE`](https://github.com/willianlim/StudentAPI/blob/master/LICENSE)
