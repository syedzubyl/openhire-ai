# OpenHire AI

> An open-source, privacy-focused AI assistant for analyzing resumes against job descriptions using an open-weight language model.

![Status](https://img.shields.io/badge/status-under--development-orange)
![License](https://img.shields.io/badge/license-MIT-green)
![Java](https://img.shields.io/badge/Java-21-orange)
![Spring%20Boot](https://img.shields.io/badge/Spring%20Boot-3.x-brightgreen)
![MySQL](https://img.shields.io/badge/MySQL-8.x-blue)
![AI](https://img.shields.io/badge/AI-Open--Weight-purple)

---

## Overview

**OpenHire AI** is an open-source AI-powered job and resume analysis platform designed to help job seekers understand how their resume relates to a specific job description.

The project uses an **open-weight language model running locally through Ollama** as a core component of the application.

Instead of treating AI as a simple chatbot, OpenHire AI is designed to transform unstructured resume and job-description text into structured, useful information that can be consumed by a backend application.

The planned system can identify:

- Skills found in a resume
- Skills requested by a job description
- Potentially missing skills
- Relevant experience
- Areas for improvement
- Technical interview topics
- Suggested interview questions

The project is being developed with **Java, Spring Boot, MySQL, REST APIs, and an open-weight AI model**.

---

# Project Status

> 🚧 **Under Development**

This repository is being developed as a learning and open-source project for **Hacktoberfest 2026** and the **Hacktoberfest Hack Day Krishnagiri × Flexiroaster**.

The implementation will be developed incrementally, starting with the local AI workflow and backend API before adding database, application tracking, and frontend functionality.

---

# Problem

Job seekers frequently apply to many different positions where each company uses different requirements and terminology.

A candidate may have the required knowledge but still need to manually compare:

```text
Resume
    +
Job Description
    ↓
Required Skills
    ↓
Candidate Skills
    ↓
Missing / Related Skills
    ↓
Interview Preparation
