# Quantifying the Security of Graphical Passwords: The Case of Android Unlock Patterns

* study with 584 participants and 2.900 patterns
* interviewd 105 people on what strategy they use to chose pattern
* 113 particiant as part of a game


## Related Work
* *password rules* have limited effects (cite: Komanduri:2011:PPM:1978942.1979321)
* graphical paswords, which have the potential to offer better usability because the human brain is particularly well-suited to remember graphical information
* graphical password are classified as *recall-based*, *recognition-based*, *cued recall-based*, andoird unlock is recall based (Biddle:2012:GPL:2333112.2333114)
* Graphical Passwords: Learning from the First Twelve Years (Biddle:2012:GPL:2333112.2333114) (separat zusammengefasst)

## Study
* offensive and defensive patterns
* recall after 20 minute break
* study resulted in too strong passwords
* pen and paper study to collect data about real android unlock patterns (105)

## Study results
* starting point in corners 75% (pre study?)
* top left point 38%
* average pattern length 5.63 (I think for prestudy?)
* user study with 113 participants
* average length defensive pattern 6.59
* average length ofensive pattern 6.33
* top left point 43%
* security here means absolute password length

## Formal notation of strength
* Markov Model, training and test set, complicated
* training set and testset a subsetof defensive patterns 
* offensive set is additional training data

## Pattern stregth
* on a hight level we can distinguish approaches: resistance against a specific password cracker, distribution of passwords
* number of possible measues can be found in Bonneau (bonneau2012science)
* partial guessing entropy estimate, can be used to measure the strength of a password distribution
* guessing entropy, it measures the average  number of guesses that the optimal attack needs in order to find the correkt password
* partial guessing entropy, attcker usually satisfies with breaking a certain fraction of accounts

## Results
*  with 10 guesses 4% of defensives are guessed and 7% of offensive patterns
*  with 30 guesses 9% defensive and 19% of offensive patterns
*  who sais what number is bad?
*  close to entropy od 2-digit PIN nubers (6.64) and 3-digit PIN numbers (9.97), here is has 8.72 (defensive), and 7.56 (offensive)

## Findings and alternative patterns
* bias of starting point towards top left corner
* choosing adjacent points with euclidian distance 1, then diagonaly adjacent points
* tendency to stay at the border, avoiding middle point
* tendency for straight lines and right angles
1. Leftout small pattern (removeing upper left point)
2. Leftout large pattern (adden bottom line with missig bottem right dot)
3. circle pattern
4. random pattern (no three point are on one line)

### Findings in Study
* circle performes best, bias of first point is similar to orgininal one
* random very week
* chose still thinght like letters even in random they try to find patterns
* memorability - no data on long term development
