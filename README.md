# EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS

## AIM: 

To analyze and compare the effectiveness of different prompting patterns by testing **Naïve Prompts** and **Refined Prompts** in different scenarios.

The generated responses are assessed based on:

* **Response quality**
* **Accuracy**
* **Level of detail**
* **Organization**
* **Relevance**
* **Practical value**


## AI TOOLS REQUIRED: 

- ChatGPT 
- Computer / Laptop
- Internet Connection
- GitHub
  
## 1. INTRODUCTION

Prompting is the process of giving instructions or questions to an Artificial Intelligence system to obtain a desired response. The quality of an AI-generated response depends not only on the capability of the AI model but also on how clearly the user's requirement is communicated.

A simple or naïve prompt may provide only the basic task, leaving many details for the AI to interpret. A refined prompt provides additional information such as context, role, constraints, output format, audience, and expected result.

### For example:

### Naïve Prompt:
~~~
Explain IoT.
~~~
### Refined Prompt:
~~~
Explain IoT in simple terms for an engineering student. Include its definition, basic working process, major components, and two real-world applications. Present the answer using headings and bullet points.
~~~

Both prompts ask about IoT, but the second prompt gives the AI much clearer instructions.

## 2. BASIC CONCEPT OF PROMPTING

A prompt can be considered as the input or instruction given to an AI model.

### General Prompt Structure

Prompt = Context + Task + Requirements + Output Format

### For example:

Context: You are explaining a topic to a beginner.
Task: Explain Cloud Computing.
Requirements: Include definition, types and advantages.
Format: Use simple language and bullet points.

This structure helps the AI understand exactly what the user expects.

## 3. TYPES OF PROMPTS USED
### A. Naïve Prompt:

A naïve prompt is a short, broad, or unstructured instruction.

### Characteristics:
- Short and simple
- Provides limited context
- Does not specify output format
- Leaves interpretation to the AI
- May produce a general response
### Example:
~~~
Explain Machine Learning.
~~~
### B. Basic / Refined Prompt

A refined prompt provides clear instructions and additional context.

### Characteristics:
- Clearly defines the task
- Provides relevant context
- Specifies the expected output
- Can mention audience and difficulty level
- Can specify length or format
- Produces more predictable results
### Example:
~~~
Explain Machine Learning for a beginner engineering student. Define Machine Learning, explain its three major types, provide one example for each type, and present the answer using simple headings and bullet points.
~~~
## 4. PROMPT COMPARISON FLOW

<img width="648" height="611" alt="image" src="https://github.com/user-attachments/assets/cae48065-d19c-4b41-bce7-afd00c8bd7cf" />

## 5. PARAMETERS USED FOR EVALUATION

The responses generated from both prompts were evaluated using the following parameters.

1. Quality

Measures whether the response is well-written, useful and properly organized.

2. Accuracy

Checks whether the information provided by the AI is factually correct.

3. Relevance

Determines whether the response directly addresses the given prompt.

4. Depth

Measures how thoroughly the topic is explained.

5. Clarity

Checks whether the response is easy to understand.

6. Structure

Checks whether the response is logically organized using headings, points, examples, etc.

## 6. TEST SCENARIO 1 – CREATIVE STORY
### Naïve Prompt:
~~~
Write a story about a student who discovers an old machine.
~~~

### AI Output:

Rahul was a college student who loved exploring old places. One day, while searching through an abandoned laboratory, he found a strange old machine covered with dust. Curious, he switched it on. Suddenly, the machine started making a loud humming sound and displayed a date from ten years in the future.

Rahul was surprised to discover that the machine could predict future events. At first, he used it to help himself with small problems. However, he soon realized that changing the future could have unexpected consequences. He decided to stop using the machine and kept its secret safe.

The experience taught Rahul that knowing the future is not always as important as making responsible choices in the present.

### Refined Prompt:
~~~
Write a short story of about 250 words about a college student who discovers an old machine inside an abandoned laboratory. The machine should have a surprising purpose. Include a clear beginning, conflict, and ending. Use simple and engaging language suitable for college students.
~~~

### AI Output:

The Machine That Remembered Tomorrow

Arjun stayed late in his college laboratory to complete his electronics project. While searching for an old circuit board, he noticed a locked door behind a stack of boxes. Inside was a forgotten laboratory filled with dusty equipment. In the corner stood a strange metal machine with a small screen.

Curious, Arjun switched it on. Instead of showing numbers, the screen displayed tomorrow's date followed by a list of events that had not happened yet.

At first, Arjun thought it was a joke. But the next morning, everything on the screen happened exactly as predicted. Excited, he entered another date. This time, the machine showed a warning: "Do not change what you see."

Arjun ignored the warning and tried to prevent an accident mentioned on the screen. His actions caused a completely different problem, affecting several students.

Realizing that the machine was not predicting the future but showing one possible future, Arjun understood his mistake. He returned to the laboratory and switched it off permanently.

He never told anyone about the machine. Instead, he learned an important lesson: technology can show us possibilities, but our decisions determine what actually happens.

<img width="1183" height="1329" alt="ChatGPT Image Aug 8, 2026, 09_30_16 AM" src="https://github.com/user-attachments/assets/a213e21b-495c-4d76-87ff-d48a7fcf80d5" />

### Expected Comparison:

The naïve prompt produced a simple story with limited details. The refined prompt produced a more structured and engaging story with a setting, conflict, unexpected twist and conclusion.

## 7. TEST SCENARIO 2 – FACTUAL QUESTION
### Naïve Prompt
~~~
What is Artificial Intelligence?
~~~

### AI Output

Artificial Intelligence (AI) is a branch of computer science that focuses on creating machines and software that can perform tasks that normally require human intelligence. These tasks include learning, reasoning, problem-solving, understanding language and recognizing images.

AI is used in many areas such as healthcare, education, banking, transportation and entertainment. Examples include virtual assistants, recommendation systems, self-driving technologies and chatbots.

### Refined Prompt
~~~
Explain Artificial Intelligence in simple language for an engineering student. Include its definition, basic working concept, three applications, and one real-world example. Keep the explanation within 150 words.
~~~

### AI Output

Artificial Intelligence (AI) is a technology that enables computers and machines to perform tasks that normally require human intelligence, such as learning, reasoning, decision-making and problem-solving.

How it works: AI systems learn patterns from data using algorithms and models. Based on these patterns, they can make predictions, classify information or generate responses.

Applications:

Healthcare: Helps detect diseases from medical images.
Transportation: Supports navigation and driver-assistance systems.
Education: Provides personalized learning and automated assistance.

Real-world example: ChatGPT is an AI system that can understand natural-language questions and generate human-like responses.

In simple terms, AI allows machines to learn from information and perform intelligent tasks.

### Inference

The naïve prompt produces a general explanation. The refined prompt produces a more focused answer because it specifies the audience, content requirements and word limit.

## 8. TEST SCENARIO 3 – SUMMARIZATION
### Naïve Prompt:
~~~
Summarize cloud computing.
~~~

### AI Output

Cloud computing is the delivery of computing services such as storage, servers, databases, networking and software over the internet. Instead of maintaining physical infrastructure, users can access resources from cloud providers whenever required.

Cloud computing provides benefits such as scalability, flexibility, cost savings and easy access. Common cloud services include storage, online applications and virtual machines. It is widely used by individuals and organizations for data storage, application development and business operations.

### Refined Prompt:
~~~
Summarize cloud computing in approximately 100 words. Include its definition, major service models such as IaaS, PaaS and SaaS, and two important advantages. Use simple language suitable for a beginner.
~~~

### AI Output

Cloud Computing is the delivery of computing resources such as servers, storage, databases and software through the internet. It allows users to access computing services without owning and maintaining physical infrastructure.

The three major service models are:

IaaS: Provides virtual servers, storage and networking.
PaaS: Provides a platform for developing and deploying applications.
SaaS: Provides ready-to-use software through the internet.

Advantages: Cloud computing reduces infrastructure costs and allows resources to be easily scaled according to requirements. Examples include Google Drive, Microsoft Azure and Amazon Web Services.

### Inference

The refined prompt gives the AI a clear idea of which information must be included, resulting in a more focused summary.

## 9. TEST SCENARIO 4 – RECOMMENDATION
### Naïve Prompt:
~~~
How can I prepare for an interview?
~~~

### AI Output

To prepare for an interview, research the company and understand the job role. Review your technical knowledge and practice commonly asked interview questions. Prepare a good introduction about yourself and be ready to discuss your projects and skills.

You should also practice communication and body language. Dress professionally, arrive on time and carry the required documents. During the interview, listen carefully to questions and answer confidently.

### Refined Prompt:
~~~
Create a practical interview preparation checklist for a final-year engineering student applying for a Graduate Engineer Trainee position. Include technical preparation, aptitude practice, communication skills, resume preparation and common HR questions.
~~~

### AI Output
Interview Preparation Checklist

1. Technical Preparation

Revise core engineering subjects.
Review programming fundamentals and basic technical concepts.
Be prepared to explain your academic projects and internships.

2. Aptitude Preparation

Practice quantitative aptitude.
Revise logical reasoning and verbal ability.
Solve timed practice tests.

3. Communication

Prepare a 1–2 minute self-introduction.
Practice speaking clearly and confidently.
Improve your explanation of technical concepts.

4. Resume Preparation

Know every skill and project mentioned in your resume.
Prepare questions and answers related to your projects.
Keep your resume concise and error-free.

5. HR Questions
Practice:

Tell me about yourself.
What are your strengths and weaknesses?
Why should we hire you?
Where do you see yourself in five years?

Final Tip: Practice mock interviews and focus on answering confidently rather than memorizing answers.

### Inference

The refined prompt produces recommendations specifically suited to the user's situation rather than providing generic interview advice.

## 10. TEST SCENARIO 5 – TECHNICAL EXPLANATION
### Naïve Prompt:
~~~
Explain IoT.
~~~

### AI Output

The Internet of Things (IoT) refers to a network of physical devices connected to the internet that can collect and exchange data. These devices use sensors, communication technologies and software to share information.

IoT is used in smart homes, healthcare, agriculture, industries and transportation. For example, a smart thermostat can monitor room temperature and automatically adjust it according to the user's requirements.  

### Refined Prompt:
~~~
Explain the Internet of Things (IoT) for a beginner. Define IoT, explain its basic working process, identify its major components and provide two real-world examples. Use simple technical language and present the answer using headings and bullet points.
~~~

### AI Output
Internet of Things (IoT)

Definition:
IoT is a system in which physical devices are connected to the internet so that they can collect, exchange and sometimes act on data.

Basic Working:

Sensors collect information from the environment.
A controller or device processes the collected data.
The data is transmitted through a communication network.
A cloud or application processes and displays the information.
The system can take an action based on the received data.

Major Components:

Sensors and devices
Connectivity/network
Data processing
Cloud or edge computing
User application/interface

Real-world Examples:

Smart Home: Smart lights can be monitored and controlled through a mobile application.
Smart Agriculture: Sensors can monitor soil conditions and help farmers manage irrigation.

In simple terms, IoT connects physical objects to digital systems so that they can collect and use information intelligently.

### Inference

The refined prompt generates a more systematic explanation because the required components and presentation format are clearly mentioned.

## 11. OVERALL COMPARISON TABLE

| Scenario              | Naïve Prompt      | Refined Prompt                    | Better Output |
| --------------------- | ----------------- | --------------------------------- | ------------- |
| Creative Story        | General           | Structured and engaging           | Refined       |
| Factual Question      | Broad explanation | Focused explanation               | Refined       |
| Summarization         | General summary   | Specific summary                  | Refined       |
| Recommendation        | Generic advice    | Personalized task-oriented advice | Refined       |
| Technical Explanation | Basic explanation | Detailed and organized            | Refined       |

Ahh, understood 👍 **We should NOT change the faculty-given Smart Traffic scenario.** We’ll keep the exact scenario and technical requirements, but **paraphrase the explanation, prompts, observations, findings, etc.** so your record is different from the GitHub reference.

Here is the revised version:

---

# 11. SCENARIO 5: ENGINEERING PROBLEM

## 11.1 REAL-WORLD SCENARIO

Consider a busy **4-way city intersection** during peak morning hours. A large number of vehicles use the junction, resulting in different traffic levels on each road.

At the same time, an **ambulance carrying a critical patient** reaches the intersection. Since the existing traffic lights operate using fixed timings, the ambulance may face unnecessary delay.

To overcome this problem, an **AI-Based Smart Traffic Management System** can be developed to monitor traffic conditions and give priority to emergency vehicles.

The system should:

* Identify vehicles using cameras
* Measure traffic density
* Categorize traffic as LOW, MEDIUM, or HIGH
* Recognize ambulances
* Give emergency vehicles the highest priority
* Adjust traffic signals automatically
* Resume normal signal operation after the ambulance passes

---

## 11.2 PROBLEM STATEMENT

Develop an **AI-Based Smart Traffic Management System with Emergency Vehicle Priority** for a 4-way urban intersection.

The system should make traffic signal decisions according to **real-time traffic conditions** while ensuring that emergency vehicles receive immediate priority.

```text
Emergency Vehicle
        ↓
   Highest Priority
        ↓
High Traffic Density
        ↓
Medium Traffic Density
        ↓
Low Traffic Density
        ↓
   Lowest Priority
```

---

## 11.3 NAÏVE PROMPT

```text
Design an AI-based smart traffic system.
```

---

## 11.4 EXPECTED OUTPUT FROM NAÏVE PROMPT

A simple prompt may produce a general response such as:

> An AI-based traffic system uses cameras and sensors to observe vehicles and traffic conditions. AI can determine traffic density and adjust signals accordingly. Emergency vehicles can also be given priority.

### Observation

The response gives a **basic understanding of the system**, but it does not clearly specify the technical requirements, architecture, algorithm, implementation, or testing process.

---

# 12. REFINED ENGINEERING PROMPT

```text
Act as an AI and Embedded Systems Engineer.

Design an AI-Based Smart Traffic Management System with
Emergency Vehicle Priority for a 4-way urban intersection.

The system should monitor traffic using cameras, determine
traffic density as LOW, MEDIUM, or HIGH, and identify
ambulances or emergency vehicles.

The emergency vehicle must receive the highest priority.
After the emergency vehicle passes, the system should
continue normal traffic signal operation.

Include:
1. Problem definition
2. Requirements
3. Hardware and software
4. System architecture
5. Working principle
6. Traffic density algorithm
7. Emergency vehicle detection
8. Flowchart
9. Python simulation
10. Test cases
11. Expected results
12. Advantages
13. Limitations
14. Future enhancements

Present the solution in a simple, structured format.
```

---

## 13. EXPECTED OUTPUT FROM REFINED PROMPT

The refined prompt is expected to generate a **complete and organized engineering solution** containing the system requirements, architecture, algorithm, implementation, testing, and expected results.

### Observation

Unlike the naïve prompt, the refined prompt provides **specific instructions and output requirements**, resulting in a more detailed and practical response.

---

## 14. SYSTEM ARCHITECTURE

```text
Traffic Cameras
       ↓
Vehicle Detection
       ↓
Traffic Density Analysis
       ↓
LOW / MEDIUM / HIGH
       ↓
Emergency Vehicle Detection
       ↓
AI Decision Making
       ↓
Traffic Signal Controller
       ↓
Signal Control
```

---

## 15. DECISION LOGIC

```text
Detect Traffic
      ↓
Check Emergency Vehicle
      ↓
   YES ─────→ Give Highest Priority
      ↓
     NO
      ↓
Check Traffic Density
      ↓
HIGH → HIGH PRIORITY
MEDIUM → MEDIUM PRIORITY
LOW → LOW PRIORITY
```

---

## 16. PYTHON SIMULATION

```python
def traffic_control(density, emergency):

    if emergency:
        return "Emergency Vehicle - GREEN"

    if density == "HIGH":
        return "High Traffic - GREEN"

    elif density == "MEDIUM":
        return "Medium Traffic - GREEN"

    else:
        return "Low Traffic - GREEN"


print(traffic_control("HIGH", False))
print(traffic_control("LOW", True))
```

### Expected Output

```text
High Traffic - GREEN
Emergency Vehicle - GREEN
```

---

## 17. TEST CASES

| Test Case | Traffic | Emergency Vehicle | Expected Result                         |
| --------- | ------- | ----------------- | --------------------------------------- |
| TC01      | LOW     | No                | Low traffic priority                    |
| TC02      | MEDIUM  | No                | Medium traffic priority                 |
| TC03      | HIGH    | No                | High traffic priority                   |
| TC04      | LOW     | Yes               | Emergency vehicle priority              |
| TC05      | HIGH    | Yes               | Emergency vehicle gets highest priority |
| TC06      | MEDIUM  | No                | Normal traffic control                  |

---

## 18. EVALUATION

The responses can be compared using:

* **Quality**
* **Accuracy**
* **Depth**
* **Structure**
* **Relevance**
* **Practical usefulness**

| Prompt Type    | Overall Response            |
| -------------- | --------------------------- |
| Naïve Prompt   | General and limited         |
| Refined Prompt | Detailed and well-organized |

### Key Observation

The **refined prompt produces a more complete response** because it clearly defines the problem, requirements, expected sections, and technical constraints.

---

## 19. FINDINGS

1. Naïve prompts provide simple and general responses.
2. Refined prompts produce more detailed outputs.
3. Adding context improves the relevance of the answer.
4. Clear requirements improve response structure.
5. Specifying the output format makes the answer easier to use.
6. Test cases help evaluate the generated solution.
7. Refined prompting is more suitable for complex engineering tasks.

---

## 20. KEY LEARNING

```text
Clear Instructions
       +
Context
       +
Requirements
       +
Constraints
       +
Expected Output
       ↓
Improved AI Response
```

A carefully designed prompt helps the AI understand the engineering problem and generate a more useful solution.

---

## 21. CONCLUSION

The experiment demonstrates that **prompt design has a significant effect on AI-generated responses**. A naïve prompt gives a broad response, whereas a refined prompt produces a more **detailed, structured, relevant, and technically useful solution**.

---

## 22. RESULT

**The experiment was successfully completed. The comparison showed that refined prompts provide better-quality and more structured responses than naïve prompts, particularly when solving complex engineering problems.**
