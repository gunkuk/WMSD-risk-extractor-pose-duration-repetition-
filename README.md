# WMSD-risk-extractor-pose-duration-repetition

This module is developed for technical paper, working title "Automated Ergonomic Risk Assessment Through Occlusion-Aware Pose Estimation and LLM-based Risk Interpretation".
This module consist module #2 of the paper.

This module is built to extract WMSD risk in terms of posture, duration, and repetition.
Input of this moudule is 3D skeleton joint series.

Posture risks are built upon the principles of Rapid Entire Body Assessment.
Duration risks rely on rolling standard deviation of joint angular velocity.
Repetition risks incorporate self similarity matrix to detect local maxima of periodicty.
