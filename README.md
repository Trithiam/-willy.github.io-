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

User
write me a resume in code form, my name is Willy Trethewey, age 23, study at Payap university, my major is English Communication and make up the rest for a third year male uni student
ChatGPT
python
Copy code
# Resume for Willy Trethewey

# Personal Information
name = "Willy Trethewey"
age = 23
university = "Payap University"
major = "English Communication"

# Education
education = {
    "University": {
        "Name": university,
        "Degree": "Bachelor's Degree",
        "Major": major,
        "Expected_Graduation": "2023"
    }
}

# Experience
experience = [
    {
        "Position": "English Tutor",
        "Company": "Private Tutoring",
        "Duration": "September 2021 - Present",
        "Responsibilities": [
            "Providing personalized English language tutoring sessions to students",
            "Creating lesson plans tailored to individual student needs",
            "Assessing student progress and adjusting teaching methods accordingly"
        ]
    },
    {
        "Position": "Social Media Intern",
        "Company": "Digital Marketing Agency",
        "Duration": "June 2021 - August 2021",
        "Responsibilities": [
            "Assisting in the management of social media accounts",
            "Creating engaging content for various platforms",
            "Analyzing social media metrics and trends"
        ]
    }
]

# Skills
skills = ["Excellent verbal and written communication skills",
          "Proficient in Microsoft Office Suite",
          "Strong interpersonal skills",
          "Creative problem solver",
          "Adaptable and quick learner",
          "Basic knowledge of graphic design tools"]

# References
references_available = True

# Print Resume
print("Resume for:", name)
print("Age:", age)
print("University:", university)
print("Major:", major)
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
