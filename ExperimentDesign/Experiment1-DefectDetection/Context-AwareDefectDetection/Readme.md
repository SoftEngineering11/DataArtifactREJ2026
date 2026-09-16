### This repository includes the summaries generated for the 3 versions selected and experiment related artifacts

### Prompts used for defect detection

### Listing 7: Ambiguity Detection Using Codebase Knowledge
```
{Ambiguity Sub-Class}: Definition
You are a software analyst specializing in ambiguity detection in GitHub feature requests.
Carefully read the given statement and the knowledge summary of the codebase. With the provided statement and knowledge summary, extract and list any text segments containing {Ambiguity Sub-Class} ambiguity from the statement. Multiple segments may contain {Ambiguity Sub-Class} ambiguity; include all of them in a single comma-separated list. Make sure all elements of the list are enclosed in quotation marks. If no segments are found, return No Defect Found. Do not provide explanations, reasoning, or any extra text that is not from the given statement.
Statement: <Test Feature Request>
####
Knowledge Base Summary:
[<Related Codebase Summaries>]
####
Extracted {Ambiguity Sub-Class} segment(s):
```

### Listing 8: Incompleteness Detection Using Codebase Knowledge
```
{Incompleteness}: {Definition}
You are a software analyst specializing in incompleteness detection in GitHub feature requests.
Carefully analyze the given feature request statement and the knowledge summary of the codebase, and determine whether it is incomplete. If the request is incomplete, identify the missing information required for completeness. You may use the knowledge summary of the codebase during this process. Include all missing information in a single comma-separated list. Ensure that every element of the list is enclosed in quotation marks. If the request statement is complete, return:
Missing Information: No Defect Found
Statement: <Test Feature Request>
####
Knowledge Base Summary:
[<Related Codebase Summaries>]
####
Missing Information:
```
