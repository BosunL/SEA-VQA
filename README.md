# SEA-VQA: Visual Question Answering for Kenyan Cultures

A localized benchmarking framework designed to evaluate and audit modern Vision-Language Models (VLMs) on culturally grounded visual content across **Swahili, English, and Ateso**. 

This project is a joint research initiative between **Princeton University** and **Maseno University**, developed by Ashley Meier, Olatunbosun Lapite, and Amakalu Vitalis.

---

## About the Project

While state-of-the-art Vision-Language Models (VLMs) demonstrate remarkable capabilities in Visual Question Answering (VQA) for widely spoken Western and Asian languages, their ability to reason about localized cultural context—particularly in under-represented African languages—remains drastically underexplored. Web-scale pretraining datasets frequently omit regional cultural knowledge and native African languages, leaving a massive digital gap in AI technologies.

**SEA-VQA** addresses this disparity by auditing six prominent open-source VLMs:
* BLIP-VQA-Base
* BLIP-VQA-CapFilt-Large
* Gemma-3-4B-IT
* Pangea-7B
* Phi-3-Vision-128k
* Aya-Vision-8B

To achieve this, our team traveled across Kenya for six weeks to curate a specialized dataset of over 1,000 culturally relevant images. From this dataset, we built a multilingual, multiple-choice evaluation pipeline featuring fine-grained captions and complex distractor logic to evaluate cross-lingual transfer and localized visual reasoning.

---

## Project Objectives & Expectations

When launching this project, our primary focus was to quantitatively expose the boundary lines of modern multimodal models. We were hoping to extract several key outcomes from this research:

* **Audit Cultural Competency:** We aimed to evaluate whether modern VLMs can identify and reason about fine-grained cultural nuances (e.g., traditional attire like *owalo* sisal skirts, regional tools, or local landscapes) when paired with image descriptions.
* **Assess Multilingual Transferability:** We sought to measure performance degradation when moving from a digitally high-resource language (English) to a regional lingua franca (Swahili), and finally to a digitally under-resourced language (Ateso).
* **Establish a Baseline for African VQA:** By creating a robust dataset of over 50 deeply specialized, translated evaluation questions from our field imagery, we intended to set a benchmark for future open-source multimodal research in East African contexts.
* **Expose the Inequities of Web-Scale Data:** Our ultimate goal was to provide data-backed evidence showing that current "global" models underperform significantly (often hovering near random 25% guess-rates) without local dataset curation, highlighting the urgent need for inclusive AI representation.

---

## Evaluation Metrics & Key Findings

* **Baseline Performance:** Traditional baseline models (such as BLIP variants) performed close to random guessing (~25% accuracy), indicating that language variations were less of a bottleneck than the foundational lack of cultural visual data.
* **Top Performers:** Advanced models like Gemma-3 and Phi-3 demonstrated stronger reasoning capabilities, though only Gemma-3-4B-IT managed to exceed a 50% average accuracy mark across the evaluation.
* **The Takeaway:** Mainstream VLMs struggle heavily with regional African cultural data, stressing a critical requirement for expanded, locally sourced datasets.

---

## Acknowledgments

This research was conducted as part of GLS 347 (July 2026) and was generously supported by the Princeton Institute for International and Regional Studies (PIIRS). We extend our deepest gratitude to the faculty and student collaborators at both Princeton University and Maseno University who made this field research possible.
