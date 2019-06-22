# The TREC 2019 Replicable Run Initiative (RRI)

The premise behind the TREC Replicable Runs Initiative (RRI) is that submitted TREC runs should be replicable.
That is, one team should be able to replicate another team's runs, as the prelude to further analysis, improvements, etc.
While conceptually simple, this ideal has been frustratingly hard to achieve: just ask Voorhees et al. (EVIA 2016)!
Their "Open Runs" initiative in TREC 2015 received the submission of 79 participating run ids associated with 19 distinct code repositories that yielded... _zero_ runs that successfully replicated!

The TREC 2019 Replicable Runs Initiative (RRI) represents another try at this effort in the context of the [TREC 2019 Deep Learning (DL) Track](https://github.com/microsoft/TREC-2019-Deep-Learning), building on the [infrastructure from the Open-Source IR Replicability Challenge (OSIRRC)](https://github.com/osirrc/jig), a [workshop at SIGIR 2019](https://osirrc.github.io/osirrc2019/).

All participants in the TREC DL Track are invited to participate!
In the online submission form of each run, you'll get a chance to indicate if you'd like to deliver a Docker image, conforming to the [OSSIRC jig specifications](https://github.com/osirrc/jig), that will replicate your run.
Teams can designate as few or as many submissions for this condition as they wish.
The deadline for the TREC DL Track is August 7, 2019.
The deadline for the delivery of the Docker images is August 21, 2019.

After receiving the Docker images, we (the team at the University of Waterloo) will run the Docker images to see if, _indeed_, the runs are replicable!
If we encounter errors with an image, we'll debug and consult with the teams to the extent time allows.
And yes, Docker images that require (modest amounts of) GPUs are okay (after all, this is deep learning...).

If you are interested in participating in this initiative, please email [Jimmy Lin](https://cs.uwaterloo.ca/~jimmylin/) as soon as possible so we can get a sense of the scope of these efforts and hardware resources required.

## Deadlines

+ August 7, 2019: Submission of runs (indication of participation)
+ August 21, 2019: Docker images due

## References

+ Ellen M. Voorhees, Shahzad Rajput, Ian Soboroff. [Promoting Repeatability Through Open Runs.](https://pdfs.semanticscholar.org/a517/152f2353c18f6bfd83758caef8408819cec3.pdf?_ga=2.178305762.755276023.1561206208-1740888510.1561206208) _EVIA 2016_.
