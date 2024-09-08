# Hi, I'm ALAM 👋

[![GitHub followers](https://img.shields.io/github/followers/your-github-username?label=Follow%20Me&style=social)](https://github.com/the-alam) [![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://www.linkedin.com/in/the-alam/) [![](https://visitcount.itsvg.in/api?id=the-ALAM&icon=4&color=12)](https://visitcount.itsvg.in)
## 💫 About Me:
**Experienced Software Engineer** with a **diverse background** in **AI/ML**, **data science**, and **data engineering**, known for delivering high-impact solutions across multiple domains. <br />
From **CubeSat development** to **CRE platform overhauls**, I focus on helping companies optimize data for smarter decision-making and operational efficiency, 
Whether it's building **machine learning models**, **designing data pipelines**, or implementing **real-time analytics**, my work is driven by maximizing value through data.

## 💻 My Tech Stack (WIP):
- **CS Fields**: Software Engineering, Machine Learning, Computer Vision, Data Engineering, Data Science, Statistics
- **Languages**: Python, SQL, BASH, JavaScript, C++, C#
- **Databases**: PostgreSQL, DuckDB, Weaviate, Redis, MSSS, Motherduck, MySQLL
- **Tools**: Git, Docker, DBT, SpLink, Grafana, Rill, Superset, Quary, Metabase
- **Framework**: OpenCV, Spacy, FastAPI, Streamlit, NestJS, REST, GraphQL
- **Machine Learning**: Entity Resolution, Recommender Systems, Record Linkage, LLMs, Clustering, Classification, Regression
- **Computer Vision**: NERF, GaSp, Object Recognition, Depth Estimation, Image segmentation, Image Enhancement and Restoration, Upscaling, Inpainting
- **Cloud**: Heroku, RunPod, Salesforce, AWS
- **Data Engineering**: ETL/ELT, Data Warehousing, Data Integration, Data Cleaning, Data Pipeline, Data Modelling, Data Governance, Data Analytics, Data Visualization

## 🌟 Highlighted Projects:
- **[DBT Transformation & Metadata Layer](#)** 📐
	- Streamlining ETL/ELT processes for seamless data analysis and ML model prepping.
- **[Data Linkage & Deduplication](#)** 🔗
	- Tackling large-scale dynamic entity resolution via Probabilistic record linkage for ID-less deduplication across multiple data sources.
- **[Semantic Modeling & Metadata Metrics Layer](#)** 🗺️
	- Streamlined semantic modeling for self-service analytics and improved data discoverability.
- **[EYES - Automated Image Enhancement Service](#)** 🖌️
	- Automated system for enhancing street view images, handling up to 1,000 images per hour, and helping marketing and sales teams excel.
- **[N-side - Novel-View Synthesis by Image Depth Estimation](#)** 📷
	- Image depth estimation for novel view synthesis and simulate perspective changes in static images, creating immersive video-like experiences.
- **[Real Estate Recommendation Engine](#)** 🏡
	- A hybrid recommendation system utilizing collaborative filtering to boost the CRE's personalization.
-  **[Reverse Image Search Engine](#)** 🔍
	- Built a **reverse image search** engine, vectorizing data for fast image similarity search, akin to Google’s image search functionality.

## 💡 Let’s Collaborate!

If you're interested in **AI, Data Engineering**, or need help with **intelligent automation**, feel free to connect. Let's build something great together!


## 📫 **How to reach me**:

- [LinkedIn](https://linkedin.com/in/the-alam)
- [Email](dev.alameldeen@gmail.com)


<!--- ![](https://github-readme-stats.vercel.app/api/top-langs/?username=the-ALAM&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact) --->

---

```python
class SoftwareEngineer:

    def __init__(self):
        self.name = "Mohamed Alam"
        self.role = "Software Engineer"
        self.language_spoken = ["ar_EG", "en_US"]
        self.cs_fields = ["Software Engineering", "Machine Learning", "Computer Vision", "Data Engineering", "Data Science", "Statistics"]
        self.languages = ["Python", "SQL", "BASH", "JavaScript", "C++", "C#"]
        self.databases = ["PostgreSQL", "DuckDB", "Weaviate", "Redis", "MSSS", "Motherduck", "MySQL"]
        self.tools = ["Git", "Docker", "DBT", "SpLink", "Grafana", "Rill", "Superset", "Quary", "Metabase"]
        self.frameworks = ["OpenCV", "Spacy", "FastAPI", "Streamlit", "NestJS", "REST", "GraphQL"]
        self.ml = ["Entity Resolution", "Recommender Systems", "Record Linkage", "LLMs", "Clustering", "Classification", "Regression"]
        self.cv = ["NERF", "GaSp", "Object Recognition", "Depth Estimation", "Image segmentation", "Image Enhancement and Restoration", "Upscaling", "Inpainting"]
        self.cloud = ["Heroku", "RunPod", "Salesforce", "AWS"]
        self.data_engineering = ["ETL/ELT", "Data Warehousing", "Data Integration", "Data Cleaning", "Data Pipeline", "Data Modelling", "Data Governance", "Data Analytics", "Data Visualization"]
        self.code = ["Python", "JavaScript", "C++", "C#", "Processing"]
        self.ask_me_about = ["Islam", "Data", "AI", "SWE", "Physics", "Space", "Your Problems"]
        self.technologies = {
            "backend": {
                "py": ["FastAPI", "OpenCV"],
                "js": ["Node", "NestJS"],
            },
            "devops": ["AWS", "Docker"],
            "databases": ["PostgreSQL", "DuckDB", "Weaviate", "Redis", "MSSS", "Motherduck", "MySQL"],
            "tools": ["Git", "Docker", "DBT", "SpLink", "Grafana", "Rill", "Superset", "Quary", "Metabase"],
            "frameworks": ["OpenCV", "Spacy", "FastAPI", "Streamlit", "NestJS", "P5JS", "REST", "GraphQL"],
            "ml": ["Entity Resolution", "Recommender Systems", "Record Linkage", "LLMs", "Clustering", "Classification", "Regression"],
            "cv": ["NERF", "GaSp", "Object Recognition", "Depth Estimation", "Image segmentation", "Image Enhancement and Restoration", "Upscaling", "Inpainting"],
            "cloud": ["Heroku", "RunPod", "Salesforce", "AWS"],
            "data_engineering": ["ETL/ELT", "Data Warehousing", "Data Integration", "Data Cleaning", "Data Pipeline", "Data Modelling", "Data Governance", "Data Analytics", "Data Visualization"]
        }

        self.fun_facts = [
            "There are 10 types of people in the world. Those who get Binary and those who don't.",
            "Why did the developer ground their kid? They weren't telling the truthy.",
            "Why was the developer unhappy at their job? He wanted arrays.",
            "Why did the functional programmer get thrown out of school? Because he refused to take classes."
        ]

    def say_hi(self):
        print("Thanks for dropping by, hope you find some of my work interesting.")

    def list_technologies(self):
        for category, items in self.technologies.items():
            print(f"{category.capitalize()}:")
            if isinstance(items, dict):
                for subcategory, subitems in items.items():
                    print(f" {subcategory.capitalize()}: {', '.join(subitems)}")
            else:
                print(f" {', '.join(items)}")

    def get_fun_fact(self):
        import random
        return random.choice(self.fun_facts)

    def display_profile(self):
        print(f"Name: {self.name}")
        print(f"Role: {self.role}")
        print("Languages Spoken:", ", ".join(self.language_spoken))
        print("CS Fields:", ", ".join(self.cs_fields))
        print("Programming Languages:", ", ".join(self.languages))
        print("Databases:", ", ".join(self.databases))
        print("Tools:", ", ".join(self.tools))
        print("Frameworks:", ", ".join(self.frameworks))
        print("Machine Learning Techniques:", ", ".join(self.ml))
        print("Computer Vision Techniques:", ", ".join(self.cv))
        print("Cloud Platforms:", ", ".join(self.cloud))
        print("Data Engineering Skills:", ", ".join(self.data_engineering))

        print("\nTechnologies Overview:")
        self.list_technologies()

        print("\nFun Fact:")
        print(self.get_fun_fact())


me = SoftwareEngineer()
me.say_hi()
me.display_profile()
```



<!---
the-ALAM/the-ALAM is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
