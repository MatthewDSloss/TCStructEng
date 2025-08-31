# TCStructEng
"Do what two can"

## Motivations
Structural engineering workflows are really data flows. Loading data is analytically carried through a structure, which is in turn designed by carrying that data through series of standardized checks. Existing workflow accelerations take the form of bespoke "programs," which are pre-assembled dataflows and design checks for common scenarios. These excel at covering "the 95%" of cases but come with two critical tradeoffs.
### 1. Transparency
The flow of data and implementation of code checks are considered proprietary and thus obscured from the end user. The engineer fundamentally cannot guarantee the outputs of these programs.
### 2. Flexibility
Existing solutions are extremely narrow in scope and are unable to be extended effectively. This often results in hybrid calculations, where the engineer picks up the torch after their software can take them no further.

## Solution
TCStructEng aims to provide the engineer with the ability to build their own dataflows by discretizing checks into transparently implemented, documented, and tested modules which can be strung together into a complete program.
