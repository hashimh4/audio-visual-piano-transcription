# audio-visual-piano-transcription
Near state-of-the-art audio-visual piano transcription. See the code at: [audio-visual-music-transcription](https://github.com/CognitiveComputingLab/audio-visual-music-transcription)

## Abstract
Aims - To develop and publicly release the first joint audio-visual piano transcription (AMT) model, introducing a novel
application including advanced deep learning techniques for automatic audio-visual piano transcription.
Methods - We designed three models by integrating the “Skipping the Frame Level” audio model with the “Piano-Vision” visual model.
The audio model utilized semi-conditional random fields (semi-CRFs) for direct pitch extraction, contrasting with traditional bidirectional
long short-term memory (LSTM) networks to enhance precision in pitch detection. To improve key detection, deep keyboard
segmentation was employed alongside a fallback corner detection mechanism to mitigate segmentation errors. Hyperparameter tuning
was performed, optimizing the audio model with a batch size of 32 and a hop size of 24.
Results - The resulting audio-visual model achieved an F1 score of 72.24% on the OMAPS dataset and 60.21% on the OMAPS2
dataset, demonstrating competitive performance against established models such as ”MT3-Piano,” ”ByteDance,” and ”Basic-Pitch.” The
“Skipping the Frame Level” model outperformed these audio-only models in computational efficiency and error management.
Additionally, while the model exhibited an F1 score of 82.07% and 85.74% on the respective datasets, it was approximately 5-10%
below state-of-the-art precision scores. Further analysis revealed that the ”Onsets and Frames” model outperformed ”Skipping the
Frame Level” with an F1 score of 85.17%, highlighting the need for deeper examination of model selection and performance
discrepancies.
Conclusions - The models developed in this study significantly enhance existing audio and visual transcription systems, offering a
comprehensive and innovative solution for automatic piano transcription. Despite challenges such as dataset limitations and variability
in audio quality, the audio-visual model successfully integrates advanced deep learning methodologies, yielding accurate and reliable
transcriptions. The predicted model application achieved a state-of-the-art precision of 88.29% for the OMAPS2 dataset, positioning it
competitively against other existing models. Future work will focus on refining corner detection and expanding key detection algorithms
to further improve model performance and robustness. Specifically, the implementation of advanced segmentation techniques and
exploration of the integration of transformer architectures will enhance the model’s adaptability to diverse piano setups and playing
styles. By addressing these areas, it is anticipated that the next iteration of the system will not only improve accuracy but also broaden
its applicability to a wider range of real-world scenarios.

## Example of Improvement

## Future Work
Updates in progress in a separate project.

## Contact
Please send me an email at [hashimhussain4242@gmail.com](mailto:hashimhussain4242@gmail.com) for further information and the full paper completed for my MEng Dissertation.
