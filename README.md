# Welcome to the Amazon Braket challenge for QC Hack 2022.

Here is where you can find official information about the Amazon Braket challenge [QCHack 2022](https://www.qchack.io/). We are excited to see the creative solutions you come up with!

## The Challenge...

We are in the era of Noisy Intermediate Scale Quantum (NISQ) computing, and finding applications on our current noisy machines is great challenge! Your mission, should you choose to accept it, is to implement an algorithm, use case, or novel demo using Amazon Braket QPUs or simulators.

Your project:
* Must a README.md file containing include 1) a problem description, 2) results and 3) instructions on running the project.
* Must be original, i.e., not previously covered in the [Amazon Braket examples](https://github.com/aws/amazon-braket-examples)

### Judging

The Braket challenge will be entirely __community judged__, so your peers will be your audience, just like in real research! Each team should then submit their project title, along with a 1 sentence description and link to their Github repo to Google Forms (organizers will send out this link). All QCHack participants will have until Wednesday 10:00 am EDT to vote for their favorite project, also via Google Forms. 

## Submitting your solutions

To submit your solutions:
1. Fork (or duplicate) this repository to your GitHub account.
2. Work on your challenge problem.
3. Commit your work to your forked repository.  
4. To submit your project, submit the link to your repository.  
   Your repository has to be made public at the time of the Hackathon end for us to be able to judge your solutions. We don't recommend making your work public early during the Hackathon, so as not to tempt other teams to borrow from your work. Let everybody enjoy their exploration!  
   *Note that GitHub doesn't allow to change visibility of the forks. You can either fork the repository, keep it public, and push your changes at the last possible moment, or you can duplicate the repository, make it private to work on it during the Hackathon, and make it public at the end of the Hackathon. Your repo is not required to be an actual fork, it just has to follow the folder structure of this repo for Part 1 tasks.*

## Eligibility and prizes

The project with the most votes will receive $1000 in AWS credits, enabling the winning team to continue their work on Amazon Braket quantum computers and managed simulators.


## Resources



#### Logging into AWS

For this hackathon, we are using [Event Engine](https://dashboard.eventengine.run/login)  which allows users to spin up temporary AWS accounts and use resources like QPUs and managed simulators for free. If you haven't already received a hash, request one from any of the AWS mentors via DM in the QC Hack Discord. 
(P.S. please don't share your hash!)

#### Using Amazon Braket

* Check out a replay of our [Introduction to Amazon Braket](https://www.twitch.tv/videos/1449159806) Workshop on Twitch to get a walk through of the basics of the service
* Check out the  [Amazon Braket examples](https://github.com/aws/amazon-braket-examples) repo on Github. *Note: the examples are also available with all necessary libraries pre-installed if you use a managed notebook instance via the [Amazon Braket Console](https://console.aws.amazon.com/braket/).

#### Need Inspiration?
Check out a few blog posts with use cases people have implemented on Braket:
* [Using quantum annealing on Amazon Braket for price optimization](https://aws.amazon.com/blogs/quantum-computing/using-quantum-annealing-on-amazon-braket-for-price-optimization/)

* [Implementing a Recommendation Engine with Amazon Braket](https://aws.amazon.com/blogs/quantum-computing/implementing-a-recommendation-engine-with-amazon-braket/)
* [Quantum Chemistry with Qu&Co’s (now Pasqal) QUBEC on Amazon Braket](https://aws.amazon.com/blogs/quantum-computing/quantum-chemistry-with-qucos-qubec-on-amazon-braket/)
* [Exploring quantum error mitigation with Mitiq and Amazon Braket](https://aws.amazon.com/blogs/quantum-computing/exploring-quantum-error-mitigation-with-mitiq-and-amazon-braket/)

## Rules

To qualify for the Amazon Braket challenge, you must make use of Amazon Braket in the code of your project, whether using the local or managed simulators (see this [blog post](https://aws.amazon.com/blogs/quantum-computing/simulating-quantum-circuits-with-amazon-braket/) for help choosing a simulator), or using our available Quantum Processing Units (QPUs) from [D-Wave](https://aws.amazon.com/braket/quantum-computers/dwave/), [IonQ](https://aws.amazon.com/braket/quantum-computers/ionq/), [Rigetti](https://aws.amazon.com/braket/quantum-computers/rigetti/), and [OQC](https://aws.amazon.com/braket/quantum-computers/oqc/). You can access Braket through the [AWS Console](https://console.aws.amazon.com/console/home), from your local development environment (see this [blog post](https://aws.amazon.com/blogs/quantum-computing/setting-up-your-local-development-environment-in-amazon-braket/) for setup instructions).
