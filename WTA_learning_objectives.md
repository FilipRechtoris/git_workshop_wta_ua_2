# Introduction to testing
# Session-based testing
# Jira and Bug
# Test management
# Software development models
# Test design techniques 
*Olena Chornobryvets homework*

It was hard and voluminous lecture, therefore we had two lectures. It was lectured by _Maroš Kutschy_.

The process of test development consists from such parts: analysis, traceability, design, expected results, implementation. Test techniques support the tester in test analysis (what to test) and in test design (how to test).
Different techniques are implemented for testing. These techniques could be devided on three categories:
- Black-box Test Techniques (BBTT)
- White-box Test Techniques (WBTT)
- Techniques based on the experience

[**BBTT**](#bbtt) are implemented when we don't know the internal structure of tested object. And are based on an analysis of
the specified behavior of the test object. Therefore, the test
cases are independent of how the software is implemented.

[**WBTT**](#wbtt) are implemented when we know the internal structure of the object (for example, the code). They are based on an analysis of the test object’s internal structure and processing.

[**Techniques based on the experience**](#experience-based-test-techniques) effectively use the knowledge and experience of testers for the design and implementation of test cases. The effectiveness of these techniques depends heavily on the tester’s skills. Experience-based test techniques can detect defects that may be missed using the BBTT and WBTT.

## BBTT

There are such BBTT:

- *Equivalence partitioning* (divides data into partitions (known as equivalence partitions) based on the expectation that all the elements of a given partition are to be processed in the same way by the test object)
- *Boundary Value Analysis* (is a technique based on exercising the boundaries of equivalence partitions)
- *Decision Table Testing* (are used for testing the implementation of system requirements that specify how different combinations of conditions result in different outcomes)
- *State Transition Testing* (a state transition diagram models the behavior of a system by showing its possible states and valid state transitions)
- Use Case Testing

## WBTT
There are such WBTT:
- *Statement Testing and Coverage* (the coverage items are executable statements. The aim is to design test cases that
exercise statements in the code until an acceptable level of coverage is achieved)
- *Decision Testing and Coverage* (the coverage items are decisions (branches) and the aim is to design test cases to exercise
branches in the code until an acceptable level of coverage is achieved.)

## Experience-based Test Techniques
There are such Experience-based Test Techniques:   
- *Error Guessing* (is a technique used to anticipate the occurrence of errors, defects, and failures, based on
the tester’s knowledge)
- *Exploratory testing* (tests are simultaneously designed, executed, and evaluated while the tester learns about the test object)
- *Checklist-based testing* (a tester designs, implements, and executes tests to cover test conditions from a checklist. Checklists can be built based on experience, knowledge about what is important for the user, or an understanding of why and how software fails)

And also the very important thing is the selection of the test techniques. Each technique is good at finding a particular type of defect. The selection depends of a lot of different factors:
- Type of system or type of the application
- Client’s requirements
- Regulations/standards
- Risk
- Time and budget
- Availability of the documentation
- Tester’s skills
- Software Development Lifecycle

There were used such literature:

[AjTy v IT Presentation][1]

[Syllabus v4.0](https://istqb-main-web-prod.s3.amazonaws.com/media/documents/ISTQB_CTFL_Syllabus-v4.0.pdf)

[1]: https://docs.google.com/presentation/d/1O9MfWWE4l3chD4VtqHez4rH5zySoC7kq/edit#slide=id.p10

# HTML, CSS, JavaScript 
# Testing tools
# API testing 
# SQL
# Lily HomeWork
# SELECT syntax in SQL (Svitlana Homework)
# Lily HomeWork
