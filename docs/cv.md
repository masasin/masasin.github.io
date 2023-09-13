# Curriculum Vitae
??? summary
    - 10+ years of multidisciplinary experience, including 4 years in a senior role
    - Python and Robotics expert, with work in industrial automation, data science, web development, and more
    - [[#work-experience|Work experience]]
        - [[#software-developer-nipro-digital-technologies-europe|Software Dev.]], Nipro, 2023 &ndash; Present
        - [[#senior-software-engineer-adimian|Senior Software Eng.]], Adimian, 2021 &ndash; 2023
        - [[#senior-python-developer-yieldsio|Senior Python Dev.]], Yields.io, 2019 &ndash; 2020
        - [[#industrial-automation-engineer-kapernikov|Ind. Automation Eng.]], Kapernikov, 2019
        - [[#data-scientist-sentiance|Data Scientist]], Sentiance, 2018 &ndash; 2019
    - [[#project-sampling|Project sampling]]
        - [[#spirit|SPIRIT]]: Masters thesis; third person view interface for controlling a monocular drone
        - [[#yozakura|Yozakura]]: Software lead for a teleoperated rescue robot
        - [[#gestural-control-of-robots|Gestural control of robots]]: Infrastructure for controlling robots with gestures
        - [[#open-source-projects|Open source projects]]
            - Two packages on PyPI, including [latexipy]{{ urls.projects.latexipy }} (129 stars) for exporting Matplotlib-based plots into native LaTeX
            - Many repositories on GitHub, including [my resume generator]{{ urls.projects.resume }} (118 stars) and AoC [2021]{{ urls.projects.aoc2021 }}, [2022]{{ urls.projects.aoc2022 }}
            - Contributions to major and minor open source projects, including numpy, ROS, and more
    - 20+ years of [[#mentoring-experience|mentoring experience]]
    - [[#education|Education]]
    - [[kyoto|Kyoto University]] ([Mechatronics lab]{{ urls.edu.matsuno }}), MEng
    - [[waterloo|University of Waterloo]], BASc Mechatronics
    - [[#technical-skills|Technical skills]] include data science, web development, and robotics (both hardware and software)
        - For more details, please see the [[#tools-and-technologies|list of tools and technologies]] I have experience with
    - [[#soft-skills|Soft skills]] include adaptability, communication, [[#languages|languages]], and leadership skills
    - [[#tools-and-technologies|Tools and technologies]]
        - Programming languages: Python, Javascript, C++, bash
        - Development: Git, CI/CD, Docker, documentation (Sphinx, mkdocs), testing (pytest)
        - Data science: Jupyter, SciPy stack, pandas, scikit-learn, SymPy, Matplotlib, Seaborn, Plotly, Streamlit
        - Web development: Python (FastAPI, Pydantic), Javascript (Vue), HTML, CSS, SQLAlchemy
        - Robotics: ROS stack; various microcontrollers, boards, sensors, and actuators
        - Hardware: Raspberry Pi, ESP8266, Arduino, mbed; MicroPython, CircuitPython, C++, C
        - Mechanical: Solidworks, Autodesk Inventor, OpenSCAD; design, analysis, simulation, and manufacturing
        - Electrical: PCB design and manufacturing, soldering, wiring, crimping, cable management
        - Other: ChatGPT and other LLMs; Gimp, Inkscape; Linux, macOS, Windows; various office suites
    - [[#testimonials-from-colleagues|Testimonials from my colleagues]] highlight my technical expertise in Python, robotics, and related tools,
      with specific emphasis on my innovative problem-solving skills, continuous learning approach, and commitment to excellence.
      They further appreciate my proactive knowledge sharing, engaging in thoughtful discussions, and being a reliable, enjoyable teammate.

!!! tip "Résumé"
    You can also download [my two-page résumé (PDF)](/assets/files/jnassar_resume.pdf).

I'm Jean Nassar, and I'm a senior Python and robotics expert with more than 10 years of multidisciplinary experience.
My primary focus is software engineering and interfacing with hardware,
but I am also strong in mechanical and system design,
data science, visualization, and web development. 

## [[work|Work Experience]]

I have worked primarily in a software engineering role, with a focus on Python and some robotics.
I have worked in a variety of fields, including [[#industrial-automation-engineer-kapernikov|industrial automation]],
[[#senior-python-developer-yieldsio|data science]], and [[#senior-software-engineer-adimian|web development]].

### Software Developer, [Nipro Digital Technologies Europe]{{ urls.work.ndte }}
_September 2023 &ndash; Present, Belgium (remote)_

### [[adimian|Senior Software Engineer]], [Adimian]{{ urls.work.adimian }}
_January 2021 &ndash; August 2023, Belgium (remote)_

- Took end-to-end project responsibility, including initial design, development, deployment, and maintenance.
- Developed and maintained a variety of Python applications, including a web-based data management system and a data processing pipeline.
- Utilized Python libraries like Pydantic, FastAPI, SQLAlchemy, and Redis for backend development and Vue for frontend tasks.
- Efficiently addressed bug reports and managed releases, maintaining high-standard deliverables.
- Mentored colleagues, helping them improve their skills and on-board new team members, to high praise.

### [[yields|Senior Python Developer]], [Yields.io]{{ urls.work.yields }}
_December 2019 &ndash; August 2020, Belgium (remote)_

- Worked on the core of the platform as the primary Python developer.
- Refactored and stabilized the codebase, added thousands of tests, fixed bugs, and developed new features.
- Worked on automatically migrating and testing client code and artifacts with version increases, and deprecated old features.
- Moved integration tests away from depending on mocks into tests that worked with a deployed Docker environment.

### [[kapernikov|Industrial Automation Engineer]], [Kapernikov]{{ urls.work.kapernikov }}
_March &ndash; October 2019, Brussels, Belgium (hybrid)_

- Developed a monitoring system for a conveyor belt using Python 3 and ROS.
- Used a laser profiler and camera for object identification and created a 3D representation of the conveyor belt.
- Detected potentially disruptive objects in real time and produced visualizations for the client’s video management system.
- Fixed bugs in C++ code and created a standalone ROS node for camera communication.

### [[sentiance|Data Scientist]], [Sentiance]{{ urls.work.sentiance }}
_February &ndash; January 2019, Antwerp, Belgium (hybrid)_

- Moved the company’s codebase from Python 2 to Python 3.
- Refactored core functionality into more modular components
- Verified and built machine learning models in numpy and scikit-learn.
- Used pyspark to increase code efficiency by parallelizing, or to add new functionality.
- Created several docker containers and docker-compose files to automate environment setup and teardown.
- Worked on standardizing DevPI index contents using Pipenv.

As a student at the [[waterloo|University of Waterloo]], I also completed six [[coop|co-operative education internships]]
between 2009 and 2012, working in six companies in three countries over a total of two years.

## [[projects|Project sampling]]
### [[spirit|SPIRIT]]
- Masters thesis project at Kyoto University, developing a third-person view interface for controlling a monocular drone.
- Created a system that superimposed a CGI version of the drone on top of an actual image taken by the FPV camera earlier.
- Designed, conducted, and analyzed user studies which were performed to test the efficacy of the system,
  which showed a large improvement in many metrics, even with a 2 Hz transmission rate.
### [[yozakura|Yozakura]]
- Led the software development team for the Yozakura teleoperated rescue robot at Kyoto University's Mechatronics Lab.
- Developed a client-server system for robot control and wrote code for onboard Raspberry Pi and mbed chips,
  including drivers for various controllers and sensors.
- The code was robust against failure and well-documented, providing useful error messages for hardware, software,
  and operator errors of various types, and correcting them where necessary.
### [[myo|Gestural control of robots]]
- Initial research project at Kyoto University aimed at developing infrastructure to allow ergonomic control of robots using gestures.
- Designed and developed infrastructure that abstracted away the interface used by using an API,
  with a proof of concept using the Myo armband from Thalmic Labs to control robots.
### [[open_source|Open source projects]]
- Two packages on PyPI, including [latexipy]{{ urls.projects.latexipy }} (129 stars) for exporting Matplotlib-based plots into native LaTeX.
- Many repositories on GitHub, including [my resume generator]{{ urls.projects.resume }} (118 stars),
  as well as the [2021]{{ urls.projects.aoc2021 }} and [2022]{{ urls.projects.aoc2022 }} Advent of Code repositories.
- Contributions to major and minor open source projects, including numpy, ROS, and more.

## [[mentoring|Mentoring Experience]]
- Have mentored colleagues and coworkers in all my jobs, helping them with Python and software development best practices.
- Over 20 years of experience as a private tutor, teaching subjects ranging from math and physics to English and Japanese,
  as well as Python for project work.
- Recognized for the ability to explain complex concepts in simple terms and have received praise
  for my patience and effective teaching methods.

## [[skills|Skills]]
### [[skills#technical-skills|Technical skills]]
!!! tip "Tools and Technologies"
    For more details, please see the [[tools|full list of tools and technologies]] I have experience with.

- [[skills#software-engineering|Software engineering]], with expertise in Python
    - Proficient in multiple programming languages, including Javascript
    - Data science, including data analysis, modeling, and visualization.
    - Web development, including backend and frontend frameworks and languages.
- [[skills#robotics|Robotics]], including software and hardware
    - Robotic software development using Python, ROS, C++, and C. 
    - Experience developing drivers and working with various robotic hardware.
- [[skills#mechanical-and-electrical-engineering|Mechanical and electrical engineering]]
    - Can design, manufacture, and assemble electromechanical systems, including robotic systems.
    - CAD software, mechanical system simulation, electrical design platforms, and digital logic design.
- [[skills#other-skills|Knowledge of LLMs and other AI tools]]

### [[skills#soft-skills|Soft skills]]
- [[skills#adaptability|Adaptability]]: Experienced in adapting to diverse environments and cultures.
- [[skills#communication-skills|Communication]]: Articulate and effective written and verbal communication skills.
- [[skills#interpersonal-skills|Interpersonal]]: Exhibits patience and understanding when working with others.
- [[skills#critical-thinking-and-problem-solving|Critical thinking]]: Applies methodical and analytical approach to problem-solving.
- [[skills#leadership|Leadership]]: Experienced in leading teams and projects effectively from start to finish.
- [[skills#organizational-skills|Organizational]]: Experienced with project management as well as software development best practices.
- [[skills#lifelong-learning|Lifelong learning]]: Enthusiastic about expanding expertise across multiple domains.

### [[skills#languages|Natural Languages]]
- Native English and French
- Intermediate Dutch
- Advanced Japanese
- And more

## [[education|Education]]
### [[kyoto|Kyoto University]]
- Graduated with a Master of Engineering degree from the Department of Mechanical Engineering.
- Was a member of the [Mechatronics Laboratory]{{ urls.edu.matsuno }} from 2013 to 2017.
- Worked on many [[kyoto#highlighted-projects|projects]], primarily in the field of human-robot interaction,
  including the development of a [[spirit|teleoperation system for drones]] and [[myo|gestural control of robots]].
- Participated in the [[yozakura|RoboCup Japan Open's Rescue League]] multiple times in the teleoperated division.

### [[waterloo|University of Waterloo]]
- Completed Bachelor of Applied Science in Honours Mechatronics Engineering from 2008 to 2013.
- Studied a combination of mechanical, electrical, and software engineering with a focus on practical application.
- Completed [[coop|six co-operative education internships]] in three countries over a total of two years.
- Participated heavily in [[waterloo#extracurricular-activities|extracurricular activities]], including several clubs and initiatives.
- Completed [[waterloo#highlighted-projects|numerous projects]] across a variety of disciplines.

## [[tools|Tools and Technologies]]
This is a small sampling of the tools and technologies I have experience with. For a more complete list, please see the [[tools|full list]].

- [[tools#software-engineering|Programming languages]]: Python, Javascript, C++, bash
- [[tools#software-engineering|Development]]: Git, CI/CD, Docker, documentation (Sphinx, mkdocs), testing (pytest)
- [[tools#data-science|Data science]]: Jupyter, SciPy stack, pandas, scikit-learn, SymPy, Matplotlib, Seaborn, Plotly, Streamlit
- [[tools#web-development|Web development]]: Python (FastAPI, Pydantic), Javascript (Vue), HTML, CSS, SQLAlchemy
- [[tools#robotics|Robotics]]: ROS stack; various microcontrollers, boards, sensors, and actuators
- [[tools#electrical-engienering|Hardware]]: Raspberry Pi, ESP8266, Arduino, mbed; MicroPython, CircuitPython, C++, C
- [[tools#mechanical-engineering|Mechanical]]: Solidworks, Autodesk Inventor, OpenSCAD; design, analysis, simulation, and manufacturing
- [[tools#electrical-engineering|Electrical]]: PCB design and manufacturing, soldering, wiring, crimping, cable management
- [[tools#other-tools|Other]]: ChatGPT and other LLMs; Gimp, Inkscape; Linux, macOS, Windows; various office suites

## [[testimonials|Testimonials from colleagues]]
- Antonio Ferraro appreciates my talent, enthusiasm, innovative thinking, and quality Python coding skills, learning a lot from our time together.
- Ann Peeters endorses me for my deep knowledge, methodical approach, advanced Git operations expertise, and my dedication to excellence, enjoying our nerdy topic discussions and my continuous learning pace.
- Kenny Van de Maele recommends me for my impressive Python expertise, quick learning, innovative problem-solving skills, and collaborative demeanor, acknowledging my diverse knowledge beyond typical coding.
- Bram Vereertbrugghen notes my ability to learn quickly, in-depth, and with enthusiasm, appreciating my specialized and well-researched questions and my excitement about new things.
- Sergey Paramonov commends my deep knowledge of Python programming and ability to tackle challenging technical problems due to a strong understanding of computer science fundamentals.