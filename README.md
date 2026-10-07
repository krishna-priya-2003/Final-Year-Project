# Dream Plan AI

Proposed System: AI-Based Building Plan Generation System

The proposed system is an AI and Machine Learning based application designed to automatically generate building plans based on user-defined requirements. The system reduces dependency on manual architectural drafting and provides fast, accurate, and optimized building layouts suitable for residential and commercial use.

System Overview

The system accepts inputs such as plot size, number of rooms, number of floors, budget constraints, and design preferences. These inputs are processed by an intelligent requirement analysis module. Using trained machine learning models and rule-based validation, the system generates optimized building plans in both 2D and optional 3D formats.

Proposed System Architecture (Modules)
1. User Input Module

Collects plot dimensions (length × width)

Number of floors

Room requirements (bedroom, kitchen, bathroom, etc.)

Budget range

Design preferences (modern/traditional)

Optional constraints (Vastu, ventilation)

2. Requirement Analysis Module

Converts user inputs into structured design parameters

Checks feasibility of requirements based on plot size

Normalizes constraints for AI processing

3. Dataset & Training Module

Uses real-world building plan datasets

Plans are labeled with room sizes, layout patterns, and connections

Data is preprocessed for training ML models

4. AI Layout Generation Module

Uses generative AI models to create floor layouts

Predicts optimal room placement

Ensures logical connectivity between rooms

Generates multiple layout variations

5. Rule Validation & Compliance Module

Ensures minimum room size standards

Checks ventilation and lighting conditions

Validates safety and building regulations

Rejects invalid layouts automatically

6. Optimization Engine

Optimizes space utilization

Minimizes construction cost

Improves functional flow of rooms

Selects best layout based on scoring metrics

7. Output Generation Module

Generates 2D floor plans (blueprint style)

Optionally creates 3D building models

Allows download in image or PDF format

Features of the Proposed System
🔹 Core Features

Automated building plan generation

AI-driven room layout design

Rule-based validation system

Optimized space utilization

Budget-aware planning

🔹 Advanced Features

Multiple layout suggestions

3D visualization of building design

Design customization (style-based layouts)

Cost estimation (optional)

Feedback-based plan improvement

🔹 User-Friendly Features

Simple input interface

No architectural knowledge required

Fast plan generation

Editable and downloadable outputs

Advantages of the Proposed System

Reduces design time significantly

Minimizes human errors

Cost-effective solution

Scalable for different building types

Useful for architects, builders, and common users

Applications

Residential building planning

Commercial building design

Real estate and construction firms

Smart city planning

Academic and research use

Conclusion

The proposed AI-based building plan generation system provides a smart, automated, and efficient solution for modern construction planning. By integrating machine learning, rule-based validation, and optimization techniques, the system delivers accurate and reliable building designs while saving time and cost.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
