Prompt Engineering Session 08: Prove Fixes with Specification-Driven Tests
Overview
This directory contains the classwork and homework for Session 08. The module focused on Test-Driven Development (TDD) principles, executing a strict "Red Before Green" workflow, and proving bug fixes through specification-driven tests.

Objectives Achieved
Red Stage Execution: Wrote specification-driven unit tests that successfully failed (Red Stage) against flawed baseline code, proving the tests' validity.
Bug Mapping: Utilized chain prompting to identify Arithmetic, Boundary, and Unreachable Branch bugs without letting the AI fix them prematurely.
Green Stage Resolution: Implemented targeted fixes and achieved a fully passing test suite (Green Stage), including student-designed extreme boundary tests.
Rejecting False Confidence: Identified and documented the "Misleading Green" phenomenon, proving that AI-generated tests based on broken code will falsely validate bugs.
Repository Contents
Source Code & Tests
student_utils.py & test_student_utils.py: Classwork scripts featuring fixes for boundary logic and unreachable grade branches.
discount.py & test_discount.py: Homework scripts implementing an E-commerce Discount Calculator with specs for VIP bonuses and maximum caps.
Documentation & Evidence
Terminal Outputs: Captured evidence of both Red Stage failures and Green Stage passes.
Bug Mapping Logs: Documentation tracking identified bug classes to their corresponding specification tests.
AI Experiment Reflection: Conclusion detailing the dangers of generating tests from implementation rather than specification.
