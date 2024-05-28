<p align="center">
  <img src="https://cdn4.iconfinder.com/data/icons/bold-blue-symbols-vol-2/1024/move_in_go_proceed_prompt_app_mobile-512.png" width="100" alt="project-logo">
</p>
<p align="center">
    <h1 align="center">PROMPT-LOGGING-SYSTEM-FRONTEND</h1>
</p>
<p align="center">
    <em>Unleash real-time insights through interactive visualization.</em>
</p>
<p align="center">
	<img src="https://img.shields.io/github/last-commit/kashishvjain/Prompt-Logging-System-fe?style=default&logo=git&logoColor=white&color=0080ff" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/kashishvjain/Prompt-Logging-System-fe?style=default&color=0080ff" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/kashishvjain/Prompt-Logging-System-fe?style=default&color=0080ff" alt="repo-language-count">
<p>
<p align="center">
	<!-- default option, no dependency badges. -->
</p>

<br><!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary><br>

- [ Overview](#-overview)
- [ Features](#-features)
- [ Repository Structure](#-repository-structure)
- [ Modules](#-modules)
- [ Getting Started](#-getting-started)
  - [ Installation](#-installation)
  - [ Usage](#-usage)
  - [ Tests](#-tests)
- [ Project Roadmap](#-project-roadmap)
- [ Contributing](#-contributing)
- [ License](#-license)
- [ Acknowledgments](#-acknowledgments)
</details>
<hr>

##  Overview

Prompt-Logging-System-fe, a web application built with Streamlit, provides real-time data visualization and interactive querying capabilities. Users can select model types and environments to retrieve dynamic responses from a backend API, enhancing interactivity and visualization within the Prompt Logging System architecture. The project offers a Dashboard for filtering and visualizing user data, and a Metrics page for real-time metric retrieval and display. Its value lies in empowering users to explore and interact with data visually, improving data analysis efficiency and decision-making processes within the logging system.

---

##  Features

|    |   Feature         | Description |
|----|-------------------|---------------------------------------------------------------|
| ⚙️  | **Architecture**  | Based on the provided details, the project seems to be structured around a Streamlit app that facilitates querying an API to generate responses based on user prompts. It enhances interactivity and real-time response visualization within the Prompt Logging System architecture. |
| 📄 | **Documentation** | The project includes a requirements.txt file, which lists the dependencies for the Prompt Logging System. This ensures the availability of essential libraries for project functionality. Further documentation on code structure, usage, and contribution guidelines would enhance the overall documentation quality. |
| 🔌 | **Integrations**  | Key integrations and external dependencies include Pygments, plotly, pydeck, watchdog, Streamlit, GitPython, pandas, and more. These integrations enhance the project's capability to interact with APIs, visualize data, and manage dependencies effectively. |
| 🧩 | **Modularity**    | The project exhibits modularity by separating functionalities into different modules such as prompt.py, Dashboard.py, and Metrics.py. This design approach promotes code reusability and maintainability. |
| 📦 | **Dependencies**  | Key external libraries and dependencies include Pygments, plotly, pandas, Streamlit, GitPython, and more. Managing dependencies effectively is crucial for ensuring project functionality and stability. |

---

##  Repository Structure

```sh
└── Prompt-Logging-System-fe/
    ├── README.md
    ├── pages
    │   ├── Dashboard.py
    │   └── Metrics.py
    ├── prompt.py
    └── requirements.txt
```

---

##  Modules

<details closed><summary>Home</summary>

| File                                                                                                      | Summary                                                                                                                                                                                                                                                                                                           |
| ---                                                                                                       | ---                                                                                                                                                                                                                                                                                                               |
| [prompt.py](https://github.com/kashishvjain/Prompt-Logging-System-fe/blob/master/prompt.py)               | Facilitates querying an API to generate responses based on user prompts in a Streamlit app. Features user input selection for model type and environment, enabling dynamic data retrieval and display. Enhances interactivity and real-time response visualization within the Prompt Logging System architecture. |
| [requirements.txt](https://github.com/kashishvjain/Prompt-Logging-System-fe/blob/master/requirements.txt) | Requirements file lists dependencies for the Prompt Logging System.-Ensures availability of essential libraries for project functionality.                                                                                                                                                                        |

</details>

<details closed><summary>Pages</summary>

| File                                                                                                    | Summary                                                                                                                                                                                                                                                                                  |
| ---                                                                                                     | ---                                                                                                                                                                                                                                                                                      |
| [Dashboard.py](https://github.com/kashishvjain/Prompt-Logging-System-fe/blob/master/pages/Dashboard.py) | Generates data visualizations with filtering options from a backend API using Streamlit. Displays unique user data and allows time frame, environment, model, status, and user filtering. Visualizes the data in a table format on a web dashboard for user interaction.                 |
| [Metrics.py](https://github.com/kashishvjain/Prompt-Logging-System-fe/blob/master/pages/Metrics.py)     | Retrieves and displays metrics data dynamically from a backend API. Users can filter metrics by time range, environment, model, status, and user. The dashboard includes total input and output tokens, a real-time Requests per Second plot, and various interactive filtering options. |

</details>

---

##  Getting Started

**System Requirements:**

* **Python**: `version 3.10`

###  Installation

<h4>From <code>source</code></h4>

> 1. Clone the Prompt-Logging-System-fe repository:
>
> ```console
> $ git clone https://github.com/kashishvjain/Prompt-Logging-System-fe
> ```
>
> 2. Change to the project directory:
> ```console
> $ cd Prompt-Logging-System-fe
> ```
>
> 3. Install the dependencies:
> ```console
> $ pip install -r requirements.txt
> ```

###  Usage

<h4>From <code>source</code></h4>

> Run Prompt-Logging-System-fe using the command below:
> ```console
> $ python main.py
> ```


---



