# MAITRI: Emotion Assistant for Astronaut Well-Being

## Introduction
MAITRI is a multimodal AI assistant designed to monitor and support the psychological and physical well-being of astronauts during long-duration space missions. By analyzing facial expressions and speech, it provides adaptive, evidence-based interventions to help maintain emotional balance in isolated environments.

## Problem Statement
Astronauts on long-duration missions face isolation, disrupted sleep, and physical stress, which can trigger serious health issues. This project addresses the need for an AI companion that monitors astronauts via audio-video inputs, detects emotional or physical distress, and provides brief counseling or support to maintain their well-being.  
(Source: [SIH 2025, ISRO](https://www.sih.gov.in))

## Proposed Solution
- **Emotion Detection:** Detects human emotions accurately from voice tone and facial expressions.  
- **Supportive Interaction:** Offers brief, evidence-based interventions or counseling messages.  
- **Offline AI Model:** Operates standalone without requiring continuous internet connectivity.  
- **Open Data Usage:** Leverages publicly available datasets for model training and real-time data for evaluation.  


## Quick Start
1. Install required Python packages listed in `requirements.txt`.  
2. Download datasets as specified in `datasets/README.md`.  
3. Run the demo:  
```bash
python src/main.py
