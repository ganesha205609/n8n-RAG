Supabase DB:
supports vector store RAG: uses pgvector
uses Postgres for vectorDB

RAG AI agent: using n8n + supabase: cost effective, no-code
handles any updates to gdrve file
upload file: RAG generates summary of the content provided

generates:
id, content, metadata: id of file stored in gdrive, embedding vector

save it/ import it as: json file
make changes to flow, add creds for supabase & gsheet