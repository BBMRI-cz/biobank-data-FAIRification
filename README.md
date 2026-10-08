# Biobank Metadata Orchestration Engine
An end-to-end framework for multimodal biobank data FAIRification (clinical, NGS, RADIO, WSI), using AI-assisted extraction and ontology mapping to support cohort discovery at the data.bbmri.cz metadata catalogue.


The Engine is designed around a **privacy-by-design, federated architecture**. Instead of exporting sensitive patient data outside the hospital perimeter, a turnkey Dockerised appliance is deployed within the local biobank network. It connects locally to raw data, executes AI-assisted extraction and ontology grounding on-premise, and securely pushes harmonised metadata records to the national catalogue.

