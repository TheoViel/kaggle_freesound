# Kaggle : Freesound Audio Tagging 2019

## On the competition 

See https://www.kaggle.com/c/freesound-audio-tagging-2019/

> One year ago, Freesound and Google’s Machine Perception hosted an audio tagging competition challenging Kagglers to build a general-purpose auto tagging system. 
This year they’re back and taking the challenge to the next level with multi-label audio tagging, doubled number of audio categories, and a noisier than ever training set. 
If you like raising your ML game, this challenge is for you.

![freesound](https://storage.googleapis.com/kaggle-media/competitions/freesound/task2_freesound_audio_tagging.png)

> An existential problem for any major website today is how to handle toxic and divisive content. Quora wants to tackle this problem head-on to keep their platform a place where users can feel safe sharing their knowledge with the world.
Quora is a platform that empowers people to learn from each other. On Quora, people can ask questions and connect with others who contribute unique insights and quality answers. A key challenge is to weed out insincere questions -- those founded upon false premises, or that intend to make a statement rather than look for helpful answers.
In this competition, Kagglers will develop models that identify and flag insincere questions. To date, Quora has employed both machine learning and manual review to address this problem. With your help, they can develop more scalable methods to detect toxic and misleading content.
Here's your chance to combat online trolls at scale. Help Quora uphold their policy of “Be Nice, Be Respectful” and continue to be a place for sharing and growing the world’s knowledge.

Additional important informations:
- No pretrained models were allowed
- No external data was allowed
- Training can be made anywhere, but the inference had to be made in Kaggle kernels in less than one hour.
- Only few samples were manually labels, and a lot more were automatically labeled (and approximatively), 
therefore one of the challenges was to find

## Metric

See https://www.kaggle.com/c/freesound-audio-tagging-2019/overview/evaluation

> The primary competition metric will be label-weighted label-ranking average precision (lwlrap, pronounced "Lol wrap"). 
This measures the average precision of retrieving a ranked list of relevant labels for each test clip (i.e., the system ranks all the available labels, then the precisions of the ranked lists down to each true label are averaged)

## Results

I had the chance to team-up with three very talented people in this competiton, namely Maxim Shugaev, Lehan Yang, and Khoi Nguyen. 
It was a pleasure working with them and neither of us would have performed so well alone.
We ended up **9th** out of 880.

The competition took place from  April, 4 2019 to June, 11 2019. I joined quite late (early May), and merged with my teammates about 3 weeks before the end.

## Repository 

- `DCASE2019_Challenge_technical_report.pdf` : Technical report submitted to the [DCASE 2019 Challenge](http://dcase.community/)
- `modeling-kernel.ipynb` : Notebook that contains almost all our work, i.e. the training of different models. Also available [on Kaggle](https://www.kaggle.com/kernels/scriptcontent/15609045)

## Data

Data can be downloaded on the official Kaggle page : https://www.kaggle.com/c/freesound-audio-tagging-2019/data
If you wish to rerun the notebook, the easiest way is to fork the Kaggle kernel.
