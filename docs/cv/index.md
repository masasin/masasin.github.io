# Curriculum Vitae
??? summary
    - 10+ years of multidisciplinary experience, including 4 years in a senior role
    - Python and Robotics expert, with work in industrial automation, data science, web development, and more
    - Currently looking for [a new full-time opportunity](../hire_me.md) in Belgium starting from 1 September
    - [Work experience](#work-experience)
        - [Senior Software Eng.](#senior-software-engineer-adimian), Adimian, 2021 &ndash; 2023
        - [Senior Python Dev.](#senior-python-developer-yieldsio), Yields.io, 2019 &ndash; 2020
        - [Ind. Automation Eng.](#industrial-automation-engineer-kapernikov), Kapernikov, 2019
        - [Data Scientist](#data-scientist-sentiance), Sentiance, 2018 &ndash; 2019
    - [Project sampling](#project-sampling)
        - [SPIRIT](#spirit): Masters thesis; third person view interface for controlling a monocular drone
        - [Yozakura](#yozakura): Software lead for a teleoperated rescue robot
        - [Gestural control of robots](#gestural-control-of-robots): Infrastructure for controlling robots with gestures
        - [Open source projects](#open-source-projects)
            - Two packages on PyPI, including [latexipy](https://github.com/masasin/latexipy) (129 stars) for exporting Matplotlib based plots into native LaTeX
            - Many repositories on GitHub, including [my resume generator](https://github.com/masasin/resume) (118 stars) and AoC [2021](https://github.com/masasin/aoc2021), [2022](https://github.com/masasin/advent-of-code-2022)
            - Contributions to major and minor open source projects, including numpy, ROS, and more
    - 20+ years of [mentoring experience](#mentoring-experience)
    - [Education](#education)
    - [Kyoto University](kyoto) ([Mechatronics lab]{{ urls.edu.matsuno }}), MEng
    - [University of Waterloo](waterloo), BASc Mechatronics
    - [Technical skills](#technical-skills) include data science, web development, and robotics (both hardware and software)
        - For more details, please see the [list of tools and technologies](#tools-and-technologies) I have experience with
    - [Soft skills](#soft-skills) include adaptability, communication, [languages](#languages), and leadership skills
    - [Tools and technologies](#tools-and-technologies)
        - Programming languages: Python, Javascript, C++, bash
        - Development: Git, CI/CD, Docker, documentation (Sphinx, mkdocs), testing (pytest)
        - Data science: Jupyter, SciPy stack, pandas, scikit-learn, SymPy, Matplotlib, Seaborn, Plotly, Streamlit
        - Web development: Python (FastAPI, Pydantic), Javascript (Vue), HTML, CSS, SQLAlchemy
        - Robotics: ROS stack; various microcontrollers, boards, sensors, and actuators
        - Hardware: Raspberry Pi, ESP8266, Arduino, mbed; MicroPython, CircuitPython, C++, C
        - Mechanical: Solidworks, Autodesk Inventor, OpenSCAD; design, analysis, simulation, and manufacturing
        - Electrical: PCB design and manufacturing, soldering, wiring, crimping, cable management
        - Other: ChatGPT and other LLMs; Gimp, Inkscape; Linux, macOS, Windows; various office suites

I'm Jean Nassar, and I'm a senior Python and robotics expert with more than 10 years of multidisciplinary experience.
My primary focus is software engineering and interfacing with hardware,
but I am also strong in mechanical and system design,
data science, visualization, and web development. 

I am currently looking for a [new full-time opportunity](../hire_me.md) in Belgium starting from 1 September 2023.

## [Work Experience](work/index.md)

I have worked primarily in a software engineering role, with a focus on Python and some robotics.
I have worked in a variety of fields, including [industrial automation](work/kapernikov.md), [data science](work/yields.md), and [web development](work/adimian.md).

### [Senior Software Engineer](work/adimian), [Adimian]{{ urls.work.adimian }}
_January 2021 &ndash; October 2023, Belgium (remote)._

- Took end-to-end project responsibility, including initial design, development, deployment, and maintenance.
- Developed and maintained a variety of Python applications, including a web-based data management system and a data processing pipeline.
- Utilized Python libraries like Pydantic, FastAPI, SqlAlchemy, and Redis for backend development and Vue for frontend tasks.
- Efficiently addressed bug reports and managed releases, maintaining high-standard deliverables.
- Mentored colleagues, helping them improve their skills and on-board new team members, to high praise.

### [Senior Python Developer](work/yields), [Yields.io]{{ urls.work.yields }}
_December 2019 &ndash; August 2020, Belgium (remote)._

- Worked on the core of the platform as the primary Python developer.
- Refactored and stabilized the codebase, added thousands of tests, fixed bugs, and developed new features.
- Worked on automatically migrating and testing client code and artifacts with version increases, and deprecated old features.
- Moved integration tests away from depending on mocks into tests that worked with a deployed Docker environment.

### [Industrial Automation Engineer](work/kapernikov), [Kapernikov]{{ urls.work.kapernikov }}
_March &ndash; October 2019, Brussels, Belgium (hybrid)._

- Developed a monitoring system for a conveyor belt using Python 3 and ROS.
- Used a laser profiler and camera for object identification and created a 3D representation of the conveyor belt.
- Detected potentially disruptive objects in real time and produced visualizations for the client’s video management system.
- Fixed bugs in C++ code and created a standalone ROS node for camera communication.

### [Data Scientist](work/sentiance), [Sentiance]{{ urls.work.sentiance }}
_February &ndash; January 2019, Antwerp, Belgium (hybrid)._

- Moved the company’s codebase from Python 2 to Python 3.
- Refactored core functionality into more modular components
- Verified and built machine learning models in numpy and scikit-learn.
- Used pyspark to increase code efficiency by parallelizing, or to add new functionality.
- Created several docker containers and docker-compose files to automate environment setup and teardown.
- Worked on standardizing DevPI index contents using Pipenv.

As a student at the [University of Waterloo](education/waterloo), I also completed six [co-operative education internships](work/coop.md)
between 2009 and 2012, working in six companies in three countries over a total of two years.

## [Project sampling](projects/index.md)
### [SPIRIT](projects/spirit)
- Masters thesis project at Kyoto University, developing a third-person view interface for controlling a monocular drone.
- Created a system that superimposed a CGI version of the drone on top of an actual image taken by the FPV camera earlier.
- Designed, conducted, and analyzed user studies which were performed to test the efficacy of the system,
  which showed a large improvement in many metrics, even with a 2 Hz transmission rate.
### [Yozakura](projects/yozakura)
- Led the software development team for the Yozakura teleoperated rescue robot at Kyoto University's Mechatronics Lab.
- Developed a client-server system for robot control and wrote code for onboard Raspberry Pi and mbed chips,
  including drivers for various controllers and sensors.
- The code was robust against failure and well-documented, providing useful error messages for hardware, software,
  and operator errors of various types, and correcting them where necessary.
### [Gestural control of robots](projects/myo)
- Initial research project at Kyoto University aimed at developing infrastructure to allow ergonomic control of robots using gestures.
- Designed and developed infrastructure that abstracted away the interface used by using an API,
  with a proof of concept using the Myo armband from Thalmic Labs to control robots.
### [Open source projects](projects/open_source)
- Two packages on PyPI, including [latexipy](https://github.com/masasin/latexipy) (129 stars) for exporting Matplotlib based plots into native LaTeX.
- Many repositories on GitHub, including [my resume generator](https://github.com/masasin/resume) (118 stars),
  as well as the [2021](https://github.com/masasin/aoc2021) and [2022](https://github.com/masasin/advent-of-code-2022) Advent of Code repositories.
- Contributions to major and minor open source projects, including numpy, ROS, and more.

## [Mentoring Experience](mentoring.md)
- Have mentored colleagues and coworkers in all my jobs, helping them with Python and software development best practices.
- Over 20 years of experience as a private tutor, teaching subjects ranging from math and physics to English and Japanese,
  as well as Python for project work.
- Recognized for the ability to explain complex concepts in simple terms and have received praise
  for my patience and effective teaching methods.

## [Skills](skills.md)
### [Technical skills](skills.md#technical-skills)
!!! tip "Tools and Technologies"
    For more details, please see the [full list of tools and technologies](tools.md) I have experience with.

- [Software engineering](skills.md#software-engineering), with expertise in Python
    - Proficient in multiple programming languages, including Javascript
    - Data science, including data analysis, modeling, and visualization.
    - Web development, including backend and frontend frameworks and languages.
- [Robotics](skills.md#robotics), including software and hardware
    - Robotic software development using Python, ROS, C++, and C. 
    - Experience developing drivers and working with various robotic hardware.
- [Mechanical and electrical engineering](skills.md#mechanical-and-electrical-engineering)
    - Can design, manufacture, and assemble electromechanical systems, including robotic systems.
    - CAD software, mechanical system simulation, electrical design platforms, and digital logic design.
- [Knowledge of LLMs and other AI tools](skills.md#other-skills)

### [Soft skills](skills.md#soft-skills)
- [Adaptability](skills.md#adaptability): Experienced in adapting to diverse environments and cultures.
- [Communication](skills.md#communication-skills): Articulate and effective written and verbal communication skills.
- [Interpersonal](skills.md#interpersonal-skills): Exhibits patience and understanding when working with others.
- [Critical thinking](skills.md#critical-thinking-and-problem-solving): Applies methodical and analytical approach to problem-solving.
- [Leadership](skills.md#leadership): Experienced in leading teams and projects effectively from start to finish.
- [Organizational](skills.md#organizational-skills): Experienced with project management as well as software development best practices.
- [Lifelong learning](skills.md#lifelong-learning): Enthusiastic about expanding expertise across multiple domains.

### [Natural Languages](skills.md#languages)
- Native English and French
- Intermediate Dutch
- Advanced Japanese
- And more

## [Education](education/index.md)
### [Kyoto University](education/kyoto.md)
- Graduated with a Master of Engineering degree from the Department of Mechanical Engineering.
- Was a member of the [Mechatronics Laboratory](http://www.mechatronics.me.kyoto-u.ac.jp/index.php?ml_lang=en) from 2013 to 2017.
- Worked on many [projects](education/kyoto.md#highlighted-projects), primarily in the field of human-robot interaction,
  including the development of a [teleoperation system for drones](projects/spirit.md) and [gestural control of robots](projects/myo.md).
- Participated in the [RoboCup Japan Open's Rescue League](projects/yozakura.md) multiple times in the teleoperated division.

### [University of Waterloo](education/waterloo.md)
- Completed Bachelor of Applied Science in Honours Mechatronics Engineering from 2008 to 2013.
- Studied a combination of mechanical, electrical, and software engineering with a focus on practical application.
- Completed [six co-operative education internships](work/coop.md) in three countries over a total of two years.
- Participated heavily in [extracurricular activities](education/waterloo.md#extracurricular-activities), including several clubs and initiatives.
- Completed [numerous projects](education/waterloo.md#highlighted-projects) across a variety of disciplines.

## [Tools and Technologies](tools.md)
This is a small sampling of the tools and technologies I have experience with. For a more complete list, please see the [full list](tools.md).

- [Programming languages](tools.md#software-engineering): Python, Javascript, C++, bash
- [Development](tools.md#software-engineering): Git, CI/CD, Docker, documentation (Sphinx, mkdocs), testing (pytest)
- [Data science](tools.md#data-science): Jupyter, SciPy stack, pandas, scikit-learn, SymPy, Matplotlib, Seaborn, Plotly, Streamlit
- [Web development](tools.md#web-development): Python (FastAPI, Pydantic), Javascript (Vue), HTML, CSS, SQLAlchemy
- [Robotics](tools.md#robotics): ROS stack; various microcontrollers, boards, sensors, and actuators
- [Hardware](tools.md#electrical-engienering): Raspberry Pi, ESP8266, Arduino, mbed; MicroPython, CircuitPython, C++, C
- [Mechanical](tools.md#mechanical-engineering): Solidworks, Autodesk Inventor, OpenSCAD; design, analysis, simulation, and manufacturing
- [Electrical](tools.md#electrical-engineering): PCB design and manufacturing, soldering, wiring, crimping, cable management
- [Other](tools.md#other-tools): ChatGPT and other LLMs; Gimp, Inkscape; Linux, macOS, Windows; various office suites

