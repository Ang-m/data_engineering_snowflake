# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Data Engineering learning and career development project. The goal is to master SQL, Python, ETL pipelines, BI tools, data warehousing, and automation through a "Build to Learn" approach (70% building pipelines, 30% coursework/certifications).

## Repository Structure

- `aiproject/` - Primary working directory for the project
- `Ex_Files_Intro_Modern_Data_Engineering_Snowflake/` - Snowflake course materials
- `Ex_Files_Intro_Intro_Snowflake_Devs/` - Snowflake developer course materials
- `repo/` - Snowflake Git testing repository
- `.github/workflows/` - Gemini-based GitHub automation (review, triage, dispatch)

## Planned Tech Stack

- **Containerization:** Docker
- **Database:** PostgreSQL (local via Docker)
- **Language:** Python (pandas, requests)
- **Visualization:** Metabase (via Docker)
- **Cloud/Orchestration:** Terraform, GCP, Airflow, Spark, Kafka (later stages)

## Current State

Early-stage project. The `package.json` in `aiproject/` is empty (`{}`). No Python dependencies, tests, or build commands are configured yet. The project follows the Data Engineering Zoomcamp (DataTalks.Club) curriculum as its primary resource.

## Context

See `GEMINI.md` for the full mentorship roadmap and learning plan. The immediate focus is a 3-day foundation sprint: Docker + Postgres setup, Python ETL scripting, and BI visualization with Metabase.
