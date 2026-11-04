# Course Information

[Repository Guide](README.md) | [English](Course-Information.md) | [한국어](Course-Information.ko.md)

> **Last Updated:** 2026-11-04

## Table of Contents

- [1. Instructor and Research Lab](#1-instructor-and-research-lab)
- [2. Schedule and Class Format](#2-schedule-and-class-format)
- [3. Assessment](#3-assessment)
- [4. Course Policies](#4-course-policies)
- [5. Weekly Plan and Progress](#5-weekly-plan-and-progress)
- [6. References](#6-references)

---

<br>

## 1. Instructor and Research Lab

- **Instructor:** Prof. Unggi Lee
- **Office:** Room 401, Industry-Academic Cooperation Building
- **Office Hours:** Thursday 14:00 ~ 15:00

---

<br>

## 2. Schedule and Class Format

- **Department:** Department of Autonomous Mobility
- **Shared Course:** The course is offered as a shared course, so there are syllabi under two codes, `DAMO335-00` and `DSC-211031`. The `DSC-211031` syllabus lists the course category as major elective (211031), the operating university as Korea University Sejong Campus, the operating department as the Autonomous Driving Systems major, and the English course title as Neural Network Control Systems.
- **Type:** Major elective
- **Credits (Hours):** 3 (3) (credits/theory/lab in the `DSC-211031` syllabus: 3/3/0)
- **Intended For:** Third-year students
- **Class Time:** Tuesday 14:00 ~ 14:50, Wednesday 10:00 ~ 11:50
- **Classroom:** Science and Technology Building 1, Room 227A
- **Class Format:** The course is taught through theory lectures.
  - The lectures were distributed every week as three videos, each accompanied by lecture slides of the same title.
  - The activity type is lectures, and the `DSC-211031` syllabus allocates the class methods as 100% lectures.
  - The instructor-learner interaction plan field of the `DSC-211031` syllabus gives LMS interaction, homepages, blogs, online communities, email, social media (open chat rooms and the like), live special lectures (using CLASS), and learning counseling for students as examples, and the field for using the real-time interaction platform (CLASS) is left unchecked.
- **Course Description:** This course aims to explore the modeling of engineering systems, including mechanical and electrical systems, and control methods based on artificial neural networks. Students learn why system modeling and control are needed through feedback control system examples, and build the ability to analyze and control a given system by learning general system analysis and control methodologies as well as control methodologies that use artificial neural networks.
- **Link Between the Course Goals, Core Competencies, and Department Goals:** Students understand the modeling and control methods of engineering systems, develop expertise in system control and neural-network-based control methods, and build the ability to analyze and control engineering systems. The `DSC-211031` syllabus gives the same sentence as the main core competency and its link to other courses.
- **Learning Goals:**
  1. Understand feedback control systems.
  2. Understand artificial intelligence and artificial neural networks.
  3. Understand neural-network-based control.
- **Design Goals:** The course consists of lectures and the midterm and final exams. The lectures are given around prepared handouts, and the midterm and final exams check the level of understanding.
- **Core Competencies:** The course is very closely related to practical application, and closely related to sharing and cooperation and to creative convergence.
- **Core Competency Weights in the `DSC-211031` Syllabus:** 20% ICT skill application, 30% systems thinking, 30% convergent problem-solving, and 20% creative innovation. The competency-based learning goal field lists only ICT skill application as the core competency.
- **Prerequisites:** The recommended prerequisites are Basic Calculus and Exercises and General Calculus and Exercises (recommended prior courses).
- **Required Tool:** The assessment plan field of the `DAMO335-00` syllabus states "MATLAB 필수 (MATLAB is required)".

---

<br>

## 3. Assessment

| Item | Weight |
|:-----|-----:|
| Midterm Exam | 35% |
| Final Exam | 35% |
| Assignments | 20% |
| Attendance | 10% |

- Assessment scores are disclosed.
- **Assessment Plan:** The midterm and final exams assess academic achievement, the assignments assess the understanding of the course, and attendance and participation scores reflect engagement and learning attitude.
- **Assignments:** There were four assignments in total, and their handouts, solutions, and explanations are in [`Coursework`](Coursework/README.md).
  - HW#1 covers the conversion between forms of complex numbers and complex arithmetic, and the solution of first-order and second-order differential equations, and was due on 2025-09-26 (Fri).
  - HW#2 covers the Laplace transform and its inverse, solving differential equations with the Laplace transform, the equations of motion and transfer functions of mechanical systems, and the transfer function of a block diagram, and was due on 2025-10-14 (Tue).
  - HW#3 covers the damping type and gain design of second-order systems, poles and stability, the Routh-Hurwitz criterion, and system type and steady-state error, and was due on 2025-11-14 (Fri).
  - HW#4 covers k-nearest neighbor classification, linear regression and the coefficient of determination, RMSE, the gradients of a perceptron, input design for a discrete-time system, and neural network predictive control and NARMA-L2 control, and was due on 2025-12-05 (Fri).

---

<br>

## 4. Course Policies

- **Exam Proctoring:** Exams are not held without proctoring.
- The two syllabi list no other course policies.

---

<br>

## 5. Weekly Plan and Progress

| Week | Class Dates (Tue, Wed) | Planned Topic | Lecture Decks Covered |
|:-----|:-----|:-----|:-----|
| W01 | 9/2, 9/3 | Introduction | 1-1. 인공신경망 제어시스템<br>1-2. 제어 이론<br>1-3. 제어시스템 |
| W02 | 9/9, 9/10 | Basics of Control Systems | 2-1. 개방루프 및 폐쇄루프 제어시스템<br>2-2. 복소수<br>2-3. 미분방정식 |
| W03 | 9/16, 9/17 | Fundamental Engineering Mathematics | 3-1. 라플라스 변환 I<br>3-2. 라플라스 변환 II<br>3-3. 행렬<br>HW#1 (due 9/26) |
| W04 | 9/23, 9/24 | Control System Modeling I | 4-1. 직선 운동<br>4-2. 회전 운동<br>4-3. 전기 회로 |
| W05 | 9/30, 10/1 | Control System Modeling II | 5-1. 전달 함수<br>5-2. 특성방정식<br>5-3. 블록선도 |
| W06 | 10/7, 10/8 | Control System Modeling III | 6-1. 신호 흐름도<br>6-2. 1, 2차 상태 변수 방정식<br>6-3. n차 상태 변수 방정식<br>HW#2 (due 10/14) |
| W07 | 10/14, 10/15 | Control System Performance I | 7-1. 제어시스템 성능 개요<br>7-2. 1차 시스템의 과도 성능 응답<br>7-3. 2차 시스템의 과도 성능 응답 |
| W08 | 10/21, 10/22 | Midterm | - |
| W09 | 10/28, 10/29 | Control System Performance II | 9-1. 응답 속도 변화<br>9-2. 극점의 위치에 따른 응답<br>9-3. 제어시스템 안정도 |
| W10 | 11/4, 11/5 | Control System Performance III | 10-1. 정상 상태 성능<br>10-2. 시스템 타입 개요<br>10-3. 시스템 타입 조건<br>HW#3 (due 11/14) |
| W11 | 11/11, 11/12 | Optimization-Based PID Control | 11-1. PID 제어 개요<br>11-2. PID 제어<br>11-3. 최적화 및 PID 제어 |
| W12 | 11/18, 11/19 | Introduction to Artificial Intelligence | 12-1. 인공지능의 역사<br>12-2. 학습 타입 I<br>12-3. 학습 타입 II<br>HW#4 (due 12/5) |
| W13 | 11/25, 11/26 | Basics of Artificial Neural Networks | 13-1. 인공뉴런<br>13-2. 인공신경망 학습 I<br>13-3. 인공신경망 학습 II |
| W14 | 12/2, 12/3 | Neural Network Control System | 14-1. 인공신경망 제어 개요<br>14-2. 인공신경망 제어기 I<br>14-3. 인공신경망 제어기 II |
| W15 | 12/9, 12/10 | Final exam | - |

- The planned topics follow the weekly plans of the two syllabi. The `DSC-211031` syllabus gives the topics in Korean, and the `DAMO335-00` syllabus in English. The `DAMO335-00` syllabus sets the textbook of every week except the midterm and final exam weeks as the lecture notes (Lecture note), the core competency of those weeks as expertise, that of week 8 (midterm exam) as problem-solving, and that of week 15 (final exam) as problem-solving and creativity.
- The class dates are the dates of the Tuesday and Wednesday class times in the `DAMO335-00` syllabus. The lectures were distributed every week as videos, and the Lecture Decks Covered column gives the names of the lecture videos and slides (`week-order. title`).
- The slides carry a week title for each week: Week 1 Introduction to Neural Network Control Systems, Week 2 Basics of Control Systems, Week 3 Fundamental Engineering Mathematics, Weeks 4-6 Control System Modeling I-III, Weeks 7, 9, and 10 Control System Performance I-III, Week 11 Optimization-Based PID Control, Week 12 Introduction to Artificial Intelligence, Week 13 Introduction to Artificial Neural Networks, and Week 14 Neural-Network-Based Control Systems.
- The lecture notes form one unit (`Week##`) per week, covering the three lectures of that week in order. Weeks 8 and 15 have no lectures and therefore no unit.
- Each assignment is listed in the week where the syllabus places it, and the date in parentheses is the deadline given on the assignment handout.

---

<br>

## 6. References

| Type | Contents |
|:-----|:-----|
| Main Textbook | Class handouts (lecture notes) |
| Lecture Materials | Weekly lecture videos and slides provided by the instructor (lecture materials of the DSC shared university) |
| Reference Book | 임동진, *제어 시스템 공학*, 개정판. 파주: 생능출판사, 2019. (source of some figures and examples in the Week 7, 9, and 10 slides) |
| Reference Documents | The MathWorks Deep Learning Toolbox documentation on designing neural network predictive controllers and model reference controllers (cited in the Week 14 slides) |

- Neither syllabus lists designated books or references.
