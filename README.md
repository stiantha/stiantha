![webdev](https://github.com/stiantha/stiantha/assets/132207909/bac8f9c2-37e8-4abc-ba59-fa6c384ad9ec)

```python
const currentDate = new Date();

def github_profile():
    return {

        "personalInfo": {
            "age": 27,
            "origin": ["Grefsen", "Oslo", "Norway"],
            "passion": ["UI Design", "Responsive Web Design", "New Technologies"],
        },

        "tech": {
            "languages": ["Javascript", "Typescript", "Python", ".NET"],
            "stack": ["MongoDB", "Express", "React", "Node"],
            "tools": ["Docker", "Git", "VS", "VS Code", "Termius"],
            "design": ["Figma", "Canva", "Photoshop",
        },

        "education": [
            {
                "organization": "GET Academy",
                "department": "Fagskolen",
                "credit": 30,
                "period": {
                    "start": "2023-08-07",
                    "end": "2024-01-10",
                },
            },

            {
                "organization": "GET Academy",
                "department": "Get Prepared",
                "period": {
                    "start": "2024-01-22",
                    "end": currentDate,
                },
            },
        ],
    }
```
