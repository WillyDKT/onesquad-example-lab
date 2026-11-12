# OneSquad update 1.2.0 -> 1.3.0

Draft: resolve every conflict and obtain human review. The integrated version has NOT advanced.

## AGENTS.md

Overlapping text changes or unsupported binary content

### Old OneSquad base

    # Project contribution guide
    
    ## Documentation
    
    Keep related project documentation aligned with changes and link it to the feature.
    
    ## Review
    
    Ask a project maintainer to review changes before merging.
    
    ## Local conventions
    
    Document the adopting team's local conventions in a dedicated section before merging updates.

### Current project

    # Project contribution guide
    
    ## Documentation
    
    Keep related project documentation aligned with changes and link it to the feature.
    
    ## Review
    
    Ask a project maintainer to review changes before merging.
    
    Client-specific rule: payment-related changes require a payments maintainer review.
    Client-specific rule: do not modify production configuration during documentation work.
    
    ## Local conventions
    
    Document the adopting team's local conventions in a dedicated section before merging updates.
    
    ## Agentic routing
    
    For payment-related tasks, start with the payments maintainer and the client API.
    For incident analysis, consult docs/run/ before changing application code.
    Keep our client-specific routing rules; do not replace them with generic defaults.

### New OneSquad release

    # Project contribution guide
    
    ## Documentation
    
    Keep related project documentation aligned with changes and link it to the feature.
    
    ## Review
    
    Ask a project maintainer to review changes before merging.
    
    ## Local conventions
    
    Document the adopting team's local conventions in a dedicated section before merging updates.
    
    ## Agentic routing
    
    Start from the requested task and load only the relevant project context.
    For product requirements, consult docs/project/ before proposing changes.
    For technical decisions, consult docs/architecture/ and the affected application.
    For operational questions, consult docs/run/.
    Use optional skills when relevant; agent routing does not authorize automatic merges.

