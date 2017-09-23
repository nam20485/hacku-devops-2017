# HackOregon DevOps 2017 Course
Finished Project Exemplars will be hosted here
## See the [Wiki](https://github.com/hackoregon/hacku-devops-2017/wiki) for syllabus

Changes needed from fresh install of LM 18.2:

1.) install git

sudo apt-get install git

2.) docker-ce (https://coytar.wordpress.com/2017/03/23/docker-ce-on-linux-mint-18-1/)
    a.) gpg key

    curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -

    b.) add repo to apt (LM 18.2 derived from Ubuntu Xenial)
    
    sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu xenial stable"

3.) install vagrant 1.8.1 (stable for LM 18.2)
    
    use synaptic to install 'vagrant'

4.) install ansible 2.1.1.0 (stable for LM 18.2)
    
    use synaptic to install 'ansible'

Alternatively:

Execute devops-assign1-setup shell script


