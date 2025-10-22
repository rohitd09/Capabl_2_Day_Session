# Update Log

## Update Date: 22/10/2025

## Version Standardization

### Changes

- Standardized all package versions across modules for compatibility and stability.
- All packages and modules are compatible with langchain v0.3.*.

---
## Update Date: 15/10/2025

## Retriever Module Updates

**File:** `D1S6Retrievers.ipynb`

### Changes
1. **Embedding Model Upgrade**
   - Updated embedding model reference from:
     ```
     models/embedding-001 → models/gemini-embedding-001
     ```

2. **LLM Model Update**
   - Updated model version from:
     ```
     gemini-1.5-pro → gemini-2.5-flash
     ```

---

## Scholarship Assistant Updates

**File:** `ScholarShipAssistantS12.py`

### Changes
1. **Google API Key Setup in Load and Process PDF**
2. **Google API Key Integration in LLM and RAG Chain**

---

## LangChain Agent Updates

**File:** `D2S3agents_in_langchain.ipynb`

### Changes
1. **Added Stopping Condition in Predefined Prompt**
   - Implemented a termination rule to prevent infinite or recursive prompt loops in agent execution.

2. **Enabled Parsing Error Handling**
   - Added parameter:
     ```
     handle_parsing_errors=True
     ```
   - **Impact:** Prevents crashes from malformed or unexpected model outputs, ensuring smoother error recovery and response generation.

---

## To Do

- Update all the code to LangChain v1.0.* after stable release.