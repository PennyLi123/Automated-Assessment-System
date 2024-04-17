# Automated-Assessment-System API Prototype


1)Background：

Due to the significant increase in university class sizes, assessment turnaround times have been prolonged. However, virtual learning environments that provide facilities for online tests are expensive.

Recognising the importance of both formative and summative assessment, there's a demand for an easy-to-use, flexible, and cost-effective tool to automate assessments while providing timely feedback to students.

2)Problem Statement：

Built an easy-to-use Automated Assessment System(AAT) Prototype that serves as an `API` interface, providing structured endpoints and functions for seamless interaction between teaching staff, students, and the system, enabling teaching staff to provide formative and summative assessments for university students.

3)Tools Used:

Python Flask is used for the web interface.

Waterfall Methodology is used for the team to work with a joint contribution. 

During the developing stage, weekly tasks were planned out by drawing a Gantt Chart and using the branch function on Gitlab to develop and merge each function together.

<img width="430" alt="image" src="https://github.com/PennyLi123/Automated-Assessment-System/blob/main/3%EF%B8%8F⃣AAT%20Gantt%20Chart.png">


4)Functions Implemented:


Through this internal API, users can perform actions such as adding, editing, and deleting questions and assessments, as well as accessing relevant statistics and feedback. This API-like interface facilitates efficient communication and operation within the system, enabling a smooth and intuitive user experience.

Teaching staff can add, edit and delete assessments of summative and formative types.

Student users are able to undertake assessments of summative type (assessment of learning), receiving automatically generated feedback at a point defined by the teaching-staff from each question.

Teaching staff are able to review relevant student-user attainment, attempt and engagement statistics. 

Students are able to review relevant attempt, attainment and engagement statistics.

Students are able to indicate satisfaction with the AAT, questions, assessments and other relevant factors.

Teaching staff can review relevant student satisfaction statistics, which can inform teaching and assessment in or out of the AAT.

Both teaching staff and students are able to leave and review comments on questions set as part of a formative assessment.

Relevant gamification features (badges/medals, profiles, profile upgrades, leaderboards) for student achievements are included and viewable by other student and teaching staff users. 
