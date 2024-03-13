# -willy.github.io-
# Resume for Willy Trethewey

# Personal Information
name = "Willy Trethewey"
age = 23
university = "Payap University"

# Education
education = {
    "University": {
        "Name": university,
        "Degree": "Bachelor's Degree",
        "Major": "Computer Science",
        "Expected_Graduation": "2023"
    }
}

# Experience
experience = [
    {
        "Position": "Software Engineering Intern",
        "Company": "Tech Solutions Co., Ltd.",
        "Duration": "June 2022 - August 2022",
        "Responsibilities": [
            "Assisted in software development projects",
            "Collaborated with team members on coding tasks",
            "Tested and debugged software applications",
            "Participated in team meetings and brainstorming sessions"
        ]
    },
    {
        "Position": "IT Support Intern",
        "Company": "IT Solutions Ltd.",
        "Duration": "May 2021 - July 2021",
        "Responsibilities": [
            "Provided technical support to end-users",
            "Troubleshooted hardware and software issues",
            "Installed and configured computer systems and software",
            "Assisted in network maintenance tasks"
        ]
    }
]

# Skills
skills = ["Programming Languages: Python, Java, C++",
          "Web Development: HTML, CSS, JavaScript",
          "Database Management: SQL",
          "Version Control: Git",
          "Operating Systems: Windows, Linux",
          "Problem-Solving Skills",
          "Teamwork and Collaboration"]

# References
references_available = True

# Print Resume
print("Resume for:", name)
print("Age:", age)
print("University:", university)
print("\nEducation:")
for key, value in education["University"].items():
    print(key + ":", value)
print("\nExperience:")
for exp in experience:
    print("- Position:", exp["Position"])
    print("  Company:", exp["Company"])
    print("  Duration:", exp["Duration"])
    print("  Responsibilities:")
    for resp in exp["Responsibilities"]:
        print("  -", resp)
print("\nSkills:")
for skill in skills:
    print("-", skill)
if references_available:
    print("\nReferences available upon request.")
This Python code represents Willy Trethewey's resume, including his personal information, education, experience, skills, and availability of references. It prints out the details in a structured format.
