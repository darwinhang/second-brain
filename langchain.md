# langchain
> Framework for developing applications powered by language models

## Background References
Long and Short Term Memory via [memprompt](https://memprompt.com)

## Terminology
 - `Tool`. A function that performs a specific duty, such as making API call
 - `LLM`. language model powering agent. [Getting Started](https://python.langchain.com/en/latest/modules/models/llms/getting_started.html)
 - `Agent`. use LLM to determine which actions to take and in what order. [Getting Started](https://python.langchain.com/en/latest/modules/agents/getting_started.html)

## concepts
### Example Selectors

### Indexes
Structure documents so llms can interact with them

#### Text Splitters
Some pieces of texts are too long, so need to chunk them

Sample workflow: Split -> create embeddings from chunks -> store vectors -> set embeddings as retriever

### chains
This is probably where the `chain` in `langchain` comes from. But basically looks like composing inputs and outputs of llm interactions
