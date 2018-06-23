# Regularisation Across Linguistic Levels: experimental data sets [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1296779.svg)](https://doi.org/10.5281/zenodo.1296779)


This text file explains the supporting data files for the experiments in the submitted manuscript ’Is regularisation uniform across linguistic levels? Comparing learning and production of unconditioned probabilistic variation in morphology and word order'. You can find the code and stims used to run the experiments in `Experiment.zip` [`Python 2.7`, `PsychoPy v1.82.01`]

## In `Saldanaetal2018LLD_experimental_data.csv’ (experimental data), the descriptions of the column headings are as follows:<br />

- `Experiment` : type of production task, isolate production ('ISO') or dyadic interaction ('DYAD')<br />
- `Condition` : experimental condition ('Morphology', 'Word Order', 'NoL1 Word Order', 'Morphology Dyads' and 'Word Order Dyads')<br />
- `DyadID': the ID number of a Dyad (applicable to 'DYAD' only)<br />
- `ParticipantID` : the ID number of each individual participant. In 'DYAD' experiments, ParticipantID is the same as the Dyad ID with an additional number at the end, either 1 or 2, that indicates each of the participants within the dyad.<br />
- `Phase` : the experimental phase (analyses of output languages are run in 'testing_all' data)<br />
- `Meaning` : the object displayed<br />
- `InputSentence` : the description displayed along the object during training<br />
- `RT` : reaction time (the time passed between initial display and button click)<br />
- `MeaningSelection` : the object selected in the picture-selection tasks during training and/or matching trails during communication<br />
- `OutputSentence` : description entered<br />
- `CorrectedOutput` : proposed correction of output sentence to match input lexicon (corrected output was only used to replace identifiable typos)<br />
- `Grammatical` : presence of the displayed description in the input language<br />
- `GrammaticalityJudgment` : participants's judgment of whether the displayed description was present in the input language during training<br />
- `Timestamp` : time of data collection<br />
 

## In `Saldanaetal2018LLD_questionnaire_data.csv’ (post-experimental questionnaire data), the descriptions of the column headings are as follows:<br />

- `Experiment` : type of production task, isolate production ('ISO') or dyadic interaction ('DYAD')<br />
- `Condition` : experimental condition ('Morphology', 'Word Order', 'NoL1 Word Order', 'Morphology Dyads' and 'Word Order Dyads')<br />
- `ParticipantID` : the ID number of each individual participant<br />
- `InputMajNumOnly` :  participant's estimated input frequency for majority Num Only variant (actual input was 0.6)<br />
- `InputMajAdjOnly` : participant's estimated input frequency for majority Adj Only variant (actual input was 0.6)<br />
- `InputMajTwoMod` : participant's estimated input frequency for majority two-modifier variant (actual input was 0.6)<br />
- `OutputMajNumOnly` : participant's estimated output frequency (i.e. in production) for majority Num Only variant <br />
- `OutputMajAdjOnly` : participant's estimated output frequency for majority Adj Only variant <br />
- `OutputMajTwoMod` : participant's estimated output frequency for majority two-modifier variant <br />
- `CommentsChoice` : participant's comments on the strategy they use to choose variants<br />
- `LanguagesSpoken` : languages spoken by the participant<br />
- `Timestamp` : time of data collection<br />


`NB` Estimates for output proportions are not used in the analysis in the paper; they were collected to check that participants do not introduce the same proportions for input and output estimated frequencies systematically. 
