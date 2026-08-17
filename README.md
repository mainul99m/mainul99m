<div align="center">

# Kazi Mainul Islam

### Geospatial Software Engineer · Full-stack Research Software Engineer

I build offline-first mobile, web, and geospatial systems for environmental monitoring and scientific research.

Berlin, Germany · Open to geospatial and research software roles in Germany

[![Portfolio](https://img.shields.io/badge/Portfolio-0a192f?style=for-the-badge)](https://mainul.me)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kazimainul/)
[![Google Scholar](https://img.shields.io/badge/Google%20Scholar-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=fG91tKgAAAAJ&hl=en)
[![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/0009-0002-3631-360X)

</div>

---

## About

I am a software engineer and geospatial researcher based in Berlin. I am currently pursuing an **M.Sc. in Geodesy and Geoinformation Science** at **Technische Universität Berlin**, following a **B.Sc. and M.Sc. in Geography and Environment** from Shahjalal University of Science and Technology in Bangladesh.

At TU Berlin's Chair of Entrepreneurship and Innovation Management, I work as a Student Assistant and the sole developer responsible for **[TripleLens](https://triplelens.io)**. I took over an externally developed codebase, stabilized the inherited product, and now maintain its application, backend, testing, and deployment workflows.

From 2020 to 2024, I was Co-Founder and CTO of Olik, where I developed software for environmental research and field data collection. My work sits where geospatial data, offline mobile systems, web applications, and environmental science meet.

## Selected work

### [TripleLens](https://triplelens.io)

**Student Assistant and sole developer · Technische Universität Berlin · 2025–present**

A configurable assessment platform for entrepreneurship and incubation programs. TripleLens compares evaluations from founders, coaches, and external experts to reveal differences in perception and support structured coaching discussions.

- Took ownership of an inherited codebase and resolved more than 20 issues involving authentication and row-level security, assessment calculations, application UI, and PDF exports.
- Reworked the survey experience with explicit-selection controls, preventing untouched slider defaults from being submitted as intentional answers.
- Implemented researcher-defined weighting rules and a consistent scoring scale across assessment results, with around 20 Vitest tests covering survey, API/data, and permission logic.
- Supports approximately 15–20 active pilot users. The TypeScript/Next.js frontend runs on Vercel, while a self-hosted GitLab Runner builds and deploys prebuilt artifacts against a self-hosted Supabase backend.

**Stack:** TypeScript, Next.js, Supabase, PostgreSQL, Vitest, GitLab CI/CD, Vercel, Docker

### [Citizen for Coastal Ecosystem Monitoring — C4CEM](https://www.c4cem.org/)

**Sole software developer · 2020–2024 · Operational**

An offline-first citizen-science system for collecting georeferenced observations on fisheries, environmental conditions, plankton, plastic pollution, and other coastal resources in Bangladesh.

- Designed and implemented the Android application, research dashboard, backend, offline-data workflow, and public information site.
- Supports more than 250 citizen scientists and over 10,000 submitted datasets from coastal communities in Chattogram, Cox's Bazar, Barguna, and Kuakata.
- Built offline observation capture with SQLite, OpenStreetMap, GeoJSON layers, GPS data, and cached map tiles; records and photographs synchronize when connectivity returns.
- Developed Bengali and English interfaces, a Flutter dashboard for researchers, and a Firebase platform using Authentication, Firestore, Storage, Cloud Functions, Crashlytics, and Hosting.

**Stack:** Dart, Flutter, SQLite, Firebase, Flutter Map, OpenStreetMap, GeoJSON, WordPress

### SAROB — Bengal Elasmo Lab

**Sole software developer · University of Dhaka research collaboration · 2024–present · Pre-release field testing**

A field-data system for research on sharks, rays, and guitarfish in Bangladesh. It is designed to replace paper collection followed by manual Excel transcription with structured digital capture, review, and preparation.

- Built a Flutter mobile application for recording species data, biological measurements, GPS coordinates, and photographs in locations with unreliable connectivity.
- Implemented an SQLite-backed offline workflow that retries failed synchronization and removes local images only after the remote upload and database record succeed.
- Designed role-based workflows for administrators, laboratory assistants, researchers, and data collectors, replacing paper-to-Excel re-entry with structured review and preparation.
- Built the Supabase backend and am replacing the earlier Flutter dashboard with a Next.js interface. The mobile application is being field-tested against a hosted test backend; the new dashboard remains in pre-release testing.

**Stack:** Dart, Flutter, SQLite, TypeScript, Next.js, Supabase, PostgreSQL

*The source code is private and institution-owned.*

### [Lunar VR](https://2018.spaceappschallenge.org/challenges/universe-beauty-and-wonder/virtual-space-exploration/teams/olik/)

**UI and interaction developer · Five-member team · 2018**

An educational Google Cardboard experience that lets users explore the Apollo 11 landing site, view a lunar eclipse from the Moon, and orbit the Moon with the Lunar Reconnaissance Orbiter.

- Designed the VR interface and implemented C# scene navigation across the three lunar experiences.
- Created the text-to-speech guided narration used by the in-app assistant.
- Worked with NASA 3D models, lunar imagery, and Lunar Reconnaissance Orbiter resources in Unity. The project received the **Global Winner — Best Use of Data** award at the 2018 NASA International Space Apps Challenge.

[Award record](https://2018.spaceappschallenge.org/awards/global-finalists/) · [Source code](https://github.com/asmahdi/lunarvr)

**Stack:** Unity, C#, Google Cardboard SDK, Blender, NASA open data

## Additional geospatial work

- **[CesiumJS Weather App](https://github.com/mainul99m/CesiumJS-Weather-App):** A three-person web project combining Google Photorealistic 3D Tiles, camera navigation, and Weatherbit data. Live weather conditions trigger Cesium particle effects for rain and snow.
- **Inundation modelling — Meghna Estuarine Basin:** Developed a Python workflow that combined elevation data with observations from the Bangladesh Water Development Board, applied linear interpolation, and generated `.xyz` bathymetry inputs for Delft3D.

## Research

**Selected publication**

Sarker, S., Krug, L. A., **Islam, K. M.**, et al. (2024). *An integrated coastal ecosystem monitoring strategy: Pilot case in Naf-Saint Martin Peninsula, Bangladesh.* **Science of The Total Environment, 913**, 169718. [https://doi.org/10.1016/j.scitotenv.2023.169718](https://doi.org/10.1016/j.scitotenv.2023.169718)

For this study, I developed the C4CEM software system and wrote Section 2.2 describing the mobile application. My complete publication record is available on [Google Scholar](https://scholar.google.com/citations?user=fG91tKgAAAAJ&hl=en) and [ORCID](https://orcid.org/0009-0002-3631-360X).

## Technical toolkit

| Area | Technologies |
| --- | --- |
| Languages | TypeScript, Dart, Python |
| Application development | Next.js, Flutter |
| Backend and data | Supabase, PostgreSQL |
| Geospatial | QGIS |

Project-specific experience also includes Firebase, SQLite, CesiumJS, GeoJSON, OpenStreetMap, Docker, GitLab CI/CD, Vercel, and Vitest.

## Github Stats

<p align="center">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=mainul99m&theme=dark&hide_border=false" alt="GitHub Streak" />
</p>
