# ATS Resume Analysis API

**AI-assisted resume analysis and experience-letter processing for HR workflows.**

## The problem

A resume arriving as a PDF does not make it ready for an HR system. Someone still has to read it, structure it, and assess it. A scanned PDF adds one more small surprise: sometimes there is no extractable text at all.

This service puts that document-processing work behind an API so downstream workflows can use the result.

## The solution

A Python resume-analysis service with structured model output, scanned/image PDF handling, and an experience-letter route. Later work modernized the model integration and deployment dependencies.

## What it does

- API-based resume analysis.
- Structured outputs for downstream processing.
- Scanned/image PDF handling through a visual processing path.
- Experience-letter processing/generation.
- Containerized runtime and route-level regression checks.

## Engineering highlights

Modernized the service with Responses-based model requests, structured outputs, and a dedicated scanned-input path. Route-level checks and container/runtime validation connect the AI processing pipeline to a reproducible deployment environment.

## Technology

Python, FastAPI, Pydantic, OpenAI Responses, PDF processing, Docker.

## Source code

This repository documents the project, its capabilities, and the engineering behind it. The application source code is maintained privately.
