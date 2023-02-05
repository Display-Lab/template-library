# Precision Feedback Knowledge Base

The Precision Feedback Knowledge Base is a collection of pathways through which feedback influences human behavior. Each pathway specifies the influence of motivating information, such as performance comparisons, trends, achievement, and loss as the key information content of feedback interventions. The elements of motivating information are represented pragmatically as models of factors affecting the success of feedback interventions. These models for feedback intervention success serve dual purposes of 1) explaining how we believe feedback interventions influence behavior (i.e. program theory), and 2) configuring a precision feedback system that uses the models to generate feedback messages that can be delivered in emails, quality dashboards, feedback reports, or other digital interventions. 

Each pathway is represented in a causal pathway diagram that links the motivating information in performance data with message text and visual displays that can be used to deliver the information. The models are implemented semantically in a computer-processable format using a linked-data approach (JSON-LD), based on the Performance Summary Display Ontology and the Causal Pathway Ontology.

The knowledge base contains vignettes that illustrate how a pathway is used by a precision feedback system to deliver motivating information to one or more feedback recipients, based on their performance data, their preferences, and a collection of message templates that determine a minimal set of possible feedback interventions.
 
The knowledge base can be used by a precision feedback system to prioritize motivating feedback messages. For example, if a person (the feedback recipient) is performing below average but is improving, a precision feedback system could use information about the recipient's preferences to determine whether or not to prioritize and deliver one of the following messages: "You are not a top performer", "Your performance is improving", "Your performance is approaching the benchmark", or "You may have an opportunity to improve."

This project is supported by a grant from the National Library of Medicine: "A knowledge-based message tailoring system" (1K01 LM012528-01).

## Causal pathways

The causal pathways are located under the /causal_pathways directory.
Each pathway is described in a corresponding vignette directory.


## Version
1.0.1




