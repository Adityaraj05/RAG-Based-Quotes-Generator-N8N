🧠 N8N Quote Orchestrator Workflow
Overview

The N8N Quote Orchestrator is an intelligent automation workflow that manages and streamlines the process of generating detailed, AI-assisted service quotes. It acts as the core orchestration layer, coordinating data intake, retrieval, and generation using AI and a Supabase vector store for advanced context management.

This workflow enables multi-step reasoning and routing, ensuring that each quote request is properly classified, enriched with contextual data, and expanded into a comprehensive, professional output.

⚙️ Key Functional Components
1. Request Routing & Intake

Captures incoming quote requests from multiple service channels (WordPress, Webflow, Ecommerce, GHL, etc.).

Classifies the service type and routes the request to the correct processing branch.

Conducts targeted intake questioning to collect detailed project requirements and objectives.

2. Data Feeding into Supabase Vector Store

Extracts relevant data, documents, and historical quotes, embedding them into the Supabase vector database.

Powers multi-pass Retrieval-Augmented Generation (RAG) by enabling semantic search and context retrieval.

Continuously updates the vector store for improved accuracy and knowledge depth over time.

3. AI-Powered Quote Generation

Uses context retrieved from the Supabase vector store to generate comprehensive quotes (1200+ words).

Produces detailed, structured content with clear reasoning and professional tone.

Includes hours estimation (no pricing) to support transparent project planning.

4. Multi-Pass RAG Retrieval Process

Executes multiple retrieval passes to refine the context for better accuracy and completeness.

Leverages similar historical projects, client data, and contextual information to improve quality.

5. Output Assembly & Delivery

Aggregates AI-generated text, retrieved insights, and metadata.

Formats the final quote into a cohesive, professional document ready for review or client delivery.

🚀 Purpose & Benefits

Automates complex quote generation with minimal manual input.

Enhances accuracy through context-rich vector retrieval.

Saves time by streamlining intake, routing, and generation.

Produces long-form, high-quality quotes suitable for client proposals.

Improves continuously via feedback and dynamic vector store enrichment.
