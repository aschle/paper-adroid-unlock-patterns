# Understanding Visual Perceptions of Usability and Security of Android's Graphical Password Pattern

* pairwise prefernce, usability and security preference
* we find that visual features that can be attributed to complexity indicated a stronger persecption of security, while spatial features, such as shifts up/down or left/right are not so strong indicators for security or usability
* building a logistic model to predict perception preferences by training on features used in the suryey and other related work
* stongest feture is password distance (total lenght of all lines)
* 70% of predicted preference
* imsight into the internal visual calculus of users
* the ultimate goal of this work is to leverage the visual calculusto design systems where inherent perception of usability coincides with a known metric of security

# Introduction
* like any password system, graphical password suffer from many of the same issues as text based passwords, users select week and insecure passwords (cite, lot of studies on text based ones)
* study design attemps to measure the visual perception that influences secure and usable choices.
* by carefully selecting the password pairs, visual features of the password can be isolated, and the impact of the features on users perception of security and usability can be measured
* survey with 384 participants on AmazonMechanicalTurk
* 1.100 password pairs with 19.6 ratings on each
* rating on 2000 passwords averaging 4 ratings per password

## findings
* lenght is the strongest separator of usability and security preferences
* crossing patterns as the most secure patterns
* perceived symmetrie negatively correlated with security
* pattern distance, the total lenght of all lines was the strongest predictor of a preference

## background
* 389.112 possible paterns
* entropy same as 3-digit PIN
* but numer of patterns to enter easyly/usable, entered without repetition is far less


## Related work
* password study methodologies: study of leak or survey based studies
* leaked passwords not likely for graphical passwords
* surveys only use university settings and in-lab studies, online studies are better
* Zhao et al. security of pictures
* andriotis - smudge attacks
* Uellenbeck - partial guessing entropy (results not available befor this survey started!)

## Features and study
* length - number of points
* crosses (exes 90 degree cross)
* non-adjacent 
* knight-moves, 30 degree swipes
* height
* side
* patterns selected randomly
* need to read again very complex selection process

## Results
* usability and security reverse related
* the fact that perceptions should not be interpreted as a metric for security or usability
* while perceptions may correlated witj security metrics, unfortunately we are currently unable to directly compare perceptional metrics with those of a true security metricm which is in part a consequence of the system being anayzed
* there are currently no standard metrics for the password strength of the android password pattern.
* non-adjacent, crosses, kmoves, length reverse related security and usability
* the most strongly preferred secure feature is length, password distance even stronger
* total distance of a pattern, which is measured the length is a good indicator of visual complexity because to add any of the tested features, such as non-adj, kmoves, crosses and leght requires increasing the distance of the patternx
* spatial features had little impact on the preffered pattern
* distnce feature is very good indicator

# Comparison of Data Collection Methods for Android Graphical Pattern Unlock
* in lab via pen and paper
* online via selfreporting 

# Do bigger Grid Size Mean Better Passwords? 3x3 vs 4x4 Sizes for Android Unlock Patterns
* only password space is bigge, but people dont change behaviour
1. common start and end point
2. recall and compromise
3. length measures
4. common patterns


