# Evaluation and Alignment of Movie Events Extracted via Machine Learning from a Narrotological Perspective

> **Abstract:** We combine distant viewing and close reading to evaluate the usefulness of events extracted via machine learning from audio description of movies. To do this, we manually annotate events from Wikipedia summaries for three movies and align them to ML-extracted events. Our exploration suggests that computational narratology should combine datasets with events extracted from multimodal data sources that take into account both visual and verbal cues when detecting events.

This repository contains data and code associated to the paper ["Evaluation and Alignment of Movie Events Extracted via Machine Learning from a Narrotological Perspective"](link). If you use any of the following contents, please cite our paper.

## ML Extracted & Human Annotated Movie Events Number Comparison 

Details of the events data can be found on [Data](https://github.com/Marina-Zhou/Movie_Event_Alignment/tree/main/Data).

| Movie Name                                                      | 500 Days of  Summer(2009) | The Social Net- work(2010) | Flight(2012) |
|-----------------------------------------------------------------|---------------------------|----------------------------|--------------|
| Number of ML-extracted events from AD                           |            436            |            260             |     449      |
| Number of manually-annotated events from sum-  maries           |             80            |             43             |      64      |
| Average number of ML-extracted events aligned to summary events |            3.68           |            1.58            |     4.00     |
| Inter-annotator agreement (Krippendorff’s alpha)                |            0.93           |            0.67            |     0.83     |
 
## Cumulative distribution of movie summary events and aligned video clips for three sample movies

<div align="center">
  <img src="https://github.com/Marina-Zhou/Movie_Event_Alignment/blob/main/images/img2.png" width="100%"/>

### Events Alignment Visualization

<div align="center">
  <img src="https://github.com/Marina-Zhou/Movie_Event_Alignment/blob/main/images/img4.png" width="100%"/>
 
**Figure4** Time length and distribution of manually-annotated events successfully aligned with ML- extracted events for the movie Flight

<div align="center">
  <img src="https://github.com/Marina-Zhou/Movie_Event_Alignment/blob/main/images/img5.png" width="100%" />
 
**Figure5** Time length and distribution of ML-extracted events successfully and unsuccessfully aligned with manually-annotated events for the movie Flight

### Reproducing the Analysis and Plots

Follow along the [Events Alignment Visulisation](DataVisulisation_Duration_Length_EventType.ipynb) and [Plot Coverage Visualization](Plot_coverage_visualization.ipynb) notebooks to reproducing the analysis and plots in this paper.

### Dataset

For any problem or question regarding the data, please raise an issue in this repository.
