# Replication Package

This is the replication package of "*_Refactoring Deep Learning Code: A Study of Practices and Unsatisfied Tool Needs_*"

## Labeled Dataset

1. **commits.zip**: code change of refactoring commits, named by SHA.

2. **commits_list.csv**: label list of refactoring commits, consist of:
   * SHA
   * URL
   * Parent commit url
   * Independency: 1 for refactoring applyed in current commit; 0 for refactoring applyed in current commit and parent commit.
   * Pure: 1 for pure single refactoring practice; 0 for multi-type refactoring practice; 2 for refactoring with fix/update.
   * Location
   * Src
   * Dst

3. **Manual mining heuristic.xlsx**: The final standards we used to manually detect refactoring practices from commits. You can also combine that with the commits_list.csv for other refactoring-related research

## Survey
1. **questionnaire**: The questionnaire and response of online survey.

