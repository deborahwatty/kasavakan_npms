# Dataset for Kasavakan Puyuma Noun Phrase Markers 

This dataset contains 377 sentences collected from 5 speakers of the Kasavakan dialect of the Puyuma language. Each sentence is annotated for the following features: 


### Column: Rating

| Value | Meaning    |
|-------|------------|
| 1     | Elicited   |
| 2     | Accepted   |
| 3     | Rejected   |


### Column: Ambiguity

| Value       | Meaning                                                |
|-------------|--------------------------------------------------------|
| A-U         | Actor vs. Undergoer ambiguity                          |
| A-B         | Actor vs. Beneficiary ambiguity                        |
| A-U-L       | Actor vs. Undergoer vs. Location ambiguity             |
| A-POSS      | Actor vs. Possessor ambiguity                          |
| A-B-POSS    | Actor vs. Beneficiary vs. Possessor ambiguity          |
| POSS-POSSD  | Possessor vs. Possessed ambiguity                      |
| none        | No ambiguity                                           |


### Column: Voice

| Value      | Meaning                                                |
|------------|--------------------------------------------------------|
| AF         | Actor focus                                            |
| AF-UPOSS   | Actor focus, undergoer possessed                       |
| CF-UPOSS   | Conveyance focus, undergoer possessed                  |
| LF         | Location focus                                         |
| LF-UPOSS   | Location focus, undergoer possessed                    |
| PASS       | Passive                                                |
| PF         | Patient focus                                          |
| PF-UPOSS   | Patient focus, undergoer possessed                     |
| n/a        | Other                                                  |
| n/a-POSS   | Other, contains possessed noun


### Column: Order

| Value     | Meaning                                                       |
|-----------|---------------------------------------------------------------|
| AV        | Actor – Verb                                                  |
| AVBU      | Actor – Verb – Beneficiary – Undergoer                        |
| AVPdP     | Actor – Verb – Possessed – Possessor                          |
| AVPPd     | Actor – Verb – Possessor – Possessed                          |
| AVUVL     | Actor – Verb – Undergoer – Verb – Location                    |
| AVUL      | Actor – Verb – Undergoer – Location                           |
| AVVUL     | Actor – Verb – Verb – Undergoer – Location                    |
| AVUVXB    | Actor – Verb – Undergoer – Verb – other – Beneficiary         |
| AVUX      | Actor – Verb – Undergoer – other                              |
| AVLVU     | Actor – Verb – Location – Verb – Undergoer                    |
| AVUB      | Actor – Verb – Undergoer – Beneficiary                        |
| ALVU      | Actor – Location – Verb – Undergoer                           |
| PdP       | Possessed – Possessor                                         |
| PdPPr     | Possessed – Possessor – Predicate                             |
| PdPV      | Possessed – Possessor – Verb                                  |
| PdPVAB    | Possessed – Possessor – Verb – Actor – Beneficiary            |
| PdPVBA    | Possessed – Possessor – Verb – Beneficiary – Actor            |
| PPrPd     | Possessor – Predicate – Possessed                             |
| PPd       | Possessor – Possessed                                         |
| PPdPr     | Possessor – Possessed – Predicate                             |
| PrPdP     | Predicate – Possessed – Possessor                             |
| PrPPd     | Predicate – Possessor – Possessed                             |
| UVA       | Undergoer – Verb – Actor                                      |
| UVAB      | Undergoer – Verb – Actor – Beneficiary                        |
| VA        | Verb – Actor                                                  |
| VU        | Verb – Undergoer                                              |
| VAU       | Verb – Actor – Undergoer                                      |
| VUA       | Verb – Undergoer – Actor                                      |
| VAUB      | Verb – Actor – Undergoer – Beneficiary                        |
| VUAB      | Verb – Undergoer – Actor – Beneficiary                        |
| VAUL      | Verb – Actor – Undergoer – Location                           |
| VAUVL     | Verb – Actor – Undergoer – Verb – Location                    |
| VUVLA     | Verb – Undergoer – Verb – Location – Actor                    |
| VULA      | Verb – Undergoer – Location – Actor                           |
| VUAL      | Verb – Undergoer – Actor – Location                           |
| VUX       | Verb – Undergoer – other                                      |
| VUXA      | Verb – Undergoer – other – Actor                              |
| VUAX      | Verb – Undergoer – Actor – other                              |
| VUAXB     | Verb – Undergoer – Actor – other – Beneficiary                |
| VLXU      | Verb – Location – other – Undergoer                           |
| VLXUA     | Verb – Location – other – Undergoer – Actor                   |
| VTU       | Verb – Theme – Undergoer                                      |
| XVUA      | other – Verb – Undergoer – Actor                              |


### Columns: Actor_Type, Undergoer_Type, Beneficiary_Type, Location_Type, Poss_Type, Theme_Type

| Value       | Meaning                      |
|-------------|------------------------------|
| common_def  | Common definite              |
| common_indf | Common indefinite            |
| prsn_sg     | Personal singular            |
| prsn_pl     | Personal plural              |
| possessed   | Possessed → no marker       |
| n/a         | Not applicable               |


### Columns: Actor_Case, Undergoer_Case, Beneficiary_Case, Location_Case, Poss_Case, Theme_Case

| Value | Meaning           |
|--------|-------------------|
| NOM    | Nominative        |
| OBL    | Oblique           |
| GEN    | Genitive          |
| n/a    | Not applicable    |

