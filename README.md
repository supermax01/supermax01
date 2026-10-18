<h1 align="center">Chandra Vikram</h1>

<p align="center">
  <b>Healthcare AI engineer — clinical LLMs, retrieval &amp; evaluation, HL7 FHIR interoperability</b>
</p>

<p align="center">
  <a href="https://chandravikram.com">chandravikram.com</a> ·
  <a href="https://www.linkedin.com/in/chandra-vikram">LinkedIn</a> ·
  <a href="mailto:chandravikram10@outlook.com">chandravikram10@outlook.com</a>
</p>

I build and evaluate AI systems for clinical care: retrieval-augmented and fine-tuned language models, benchmarks
that pin every claim to a published baseline, and the HL7 FHIR plumbing that gets model output back into the record.
Pharmaceutical sciences by training, health informatics by degree (MS, Indiana University Indianapolis), engineer by
practice. I think the most useful clinical AI is built by people fluent in both the clinic and the codebase, with
clinicians firmly in the loop.

## Focus areas

- **Clinical retrieval and evaluation** — local and hybrid RAG for medical question answering, citation
  faithfulness, adversarial robustness of clinical retrieval pipelines.
- **Model training and alignment** — fine-tuning open models (Qwen3, Gemma / MedGemma) for clinical reasoning;
  constitutional, safety-first alignment for decision support.
- **Interoperability** — HL7 FHIR R4, SMART on FHIR (OAuth 2.0 + PKCE), HAPI FHIR, OpenEMR, REDCap;
  SNOMED CT, LOINC, RxNorm, UMLS.
- **Agents in care delivery** — triage, telehealth, and post-discharge agents with calibrated uncertainty and
  explicit clinician oversight.

## Selected work

| Project | What it is | Stack |
|---|---|---|
| [**MediRAG**](https://github.com/supermax01/MediRAG) | Local, privacy-preserving RAG for medical question answering with source attribution | Python · LangChain · Ollama · sentence-transformers · Pinecone · Streamlit |
| [**TPN-RAG**](https://github.com/Supermax101/TPN-RAG-Public) | Clinical-nutrition RAG benchmark: 5 frontier LLMs × 5 prompting strategies, hybrid BM25 + dense retrieval with cross-encoder reranking, NLI citation grounding, bootstrap CIs and agreement statistics | Python · ChromaDB · LangGraph · pytest |
| [**Carepal**](https://github.com/supermax01/Carepal) | AI companion for liver-cirrhosis patients: Gemini assistant with provider-ready summaries, PROMIS-29 patient-reported outcomes written to REDCap | Flutter · FastAPI · Gemini · REDCap |
| [**carepal-emr**](https://github.com/supermax01/carepal-emr) | Patient-facing OpenEMR client over SMART-on-FHIR OAuth 2.0 (PKCE) reading FHIR R4 resources through a FastAPI proxy | Flutter · FastAPI · OpenEMR · FHIR R4 |
| [**hapi_flutter**](https://github.com/supermax01/hapi_flutter) | FHIR `Patient/$everything` demo against a HAPI FHIR server, typed Dart models, SNOMED / LOINC sample data | Flutter · HAPI FHIR · Docker |
| [**Clinical Frontier**](https://chandravikram.com) | Working notebook of 18 preliminary manuscripts: FHIR infrastructure, clinical benchmarks, safety and alignment, voice and telehealth agents, knowledge graphs, retrieval evaluation | — |

**Recognition:** finalist, HL7 FHIR App Showcase at the AMIA 2024 Annual Symposium (San Francisco).

## Toolbox

`Python` · `PyTorch` · `Hugging Face Transformers` · `LangChain / LangGraph` · `Ollama` · `Apple MLX` ·
`ChromaDB / FAISS / Pinecone` · `FastAPI` · `Streamlit` · `Flutter / Dart` · `Swift` · `Docker` ·
`HL7 FHIR R4` · `SMART on FHIR` · `HAPI FHIR` · `OpenEMR` · `REDCap` · `MIMIC` ·
`SNOMED CT / LOINC / RxNorm / UMLS` · `SQL` · `R`

## Currently

- Writing up the [Clinical Frontier](https://chandravikram.com) notebook, one preliminary manuscript at a time,
  with failure modes named before any number is claimed.
- Exploring on-device clinical LLMs (MedGemma on Apple MLX) for privacy-first patient apps where health data never
  leaves the phone.

Open to research collaborations in clinical NLP, LLM evaluation, and FHIR-native AI tooling.
