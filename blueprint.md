:::mermaid
flowchart

User

Main[Main_System
When we execute this program, this begins to assemble data and compute programs.
]

System[System
Calculate scores, probabilities, values, etc.
]

User -->|Input| Main
Main -->|Instruction| System
System -->|Output| Main
Main -->|Score, Probability, etc.| User
:::




:::mermaid
flowchart

System[System]

module[module
READNE.md
]

config[config
Config.yaml
README.md
]

data[data
sample.csv
README.md
]

notebook[notebook
EDA.ipynb
create_model.ipynb
evaluate_model.ipynb
get_data.ipynb
README.md
]

System --> module
System --> config
System --> data
System --> notebook
:::