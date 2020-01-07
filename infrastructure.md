### AWS

Please see the [AWS guide](00-aws-setup-guide) for setting AWS and instances. You will receive an invitation for the class.

### Google Colab

We will use google colab in the class. Start at https://colab.research.google.com/github/ and link your github account. Selectincl private repos. Start with https://github.com/vu-bigdata-2020/example-notebooks for example analyses.

### Accessing Homeworks

Repositories will be created for each student through github classroom. You will get a url to accept the assignment.  You should see yours at 

    https://github.com/vu-bigdata-2020/homework-2-<GITHUB USERNAME> 

Clone the repository to your home directory on the cluster using:

    git clone https://github.com/vu-bigdata-2020/homework-2-<GITHUB USERNAME>.git

I may push updates to this homework assignment in the future. To setup an upstream repo, do the following:

    git remote add upstream https://github.com/vu-bigdata-2020/homework-2.git

To pull updates do the following:
    
    git fetch upstream
    git merge upstream/master

You will need to resolve conflicts if they occur. 
