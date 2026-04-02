# Abstractive Text Summarization (BART)

Built a summarization system using a BART encoder–decoder transformer to generate concise summaries from long-form text.

## Abstract
Fine-tuned a pretrained BART model for text summarization on a limited subset of data, where the encoder captures contextual information and the decoder generates summaries using attention mechanisms. The model is trained using cross-entropy loss and evaluated with ROUGE metrics to measure summary quality. It effectively identifies key information and produces coherent summaries from multi-sentence inputs. Due to limited fine-tuning data, the model exhibits partially extractive behavior, while still demonstrating abstraction through compression and paraphrasing.

## Output
- Produces coherent and grammatically correct summaries  
- Identifies and retains key information from input text  
- Performs compression by reducing multiple sentences into fewer lines  
- Demonstrates partial abstraction with some rephrasing, along with extractive tendencies  

## Limitation
Limited training data leads to partially extractive summaries
