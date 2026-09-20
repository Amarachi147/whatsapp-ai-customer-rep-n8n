# WhatsApp AI Customer Rep (n8n + Claude)

An AI-powered customer service representative for WhatsApp, built for a cosmetics business, combining a RAG product knowledge base with human fallback for cases the AI can't handle.

## How it works
- **Channel:** WhatsApp Cloud API
- **Orchestration:** n8n
- **AI model:** Claude
- **Knowledge base:** RAG-based product knowledge base — answers questions accurately from real product data
- **Rich responses:** can send product images directly inside the WhatsApp chat
- **Human fallback:** escalates to a human agent when the AI can't confidently resolve a query

## Architecture

## Scope delivered
- Full WhatsApp AI customer rep setup and deployment
- Product knowledge base ingestion and retrieval
- Testing and go-live support

*(Note: automatic WhatsApp Status posting was excluded from this build, as the official WhatsApp Business Platform doesn't support it reliably.)*

## Stack
n8n · WhatsApp Cloud API · Claude · RAG / vector store

## Files
- `workflow.json` — exported n8n workflow (client-identifying details replaced with placeholders)
