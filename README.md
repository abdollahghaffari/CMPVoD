# CMPVoD
## CMPVoD is an architecture for P2P video on demand streaming.It is simulated by OMNET++ 4.1.
### This is simulation code of CMPVoD. CMPVoD runs on OMNET++ 4.1. If you use upper versions of OMNET++, you need to change the code. CMPVoD needs to build inet (this is exists in the attached packages- add and built it). CMPVoD consists of three basic components: tracker, multiple CDN video servers, and multiple clients. CDN servers store the videos. CMPVoD maintains a randomly connected and managed overlay (i.e., a managed mesh overlay). It uses the tracker to cluster peers concerning their playback point and size of each cluster.  CMPVoD tries to optimize peers' resources usage by proposing a distributed method to locate peers with more upload capacity closer to the CDN servers.To perform interactive, such as jumping forward or backward, each peer is assigned to a cluster based on their playback point. In CMPVoD each cluster can establish several direct links to CDN video servers. CMPVoD that we named it in the code "TMVoD" has two main mesh structure: 1-TMVoD and 2-CTMVoD (taht is abbreviation of Connected TMVoD). in TMVoD peers can establish connection to other peers only in its cluster. but in CTMVoD peers in each cluster can establish links to previous clusters by getting some neighbors in the previous cluster. In this topology, clusters are connected to each other. for more information, read following papers.

## CMPVoD is simulation codes of the following papers:
### [1] An adaptive buffer-map exchange mechanism for pull-based peer-to-peer video-on-demand streaming systems
### [2] A free-riding resiliency incentive mechanism for VoD streaming over hybrid CDN-P2P networks
### [3] CMPVoD: A cluster mesh-based architecture for VoD streaming over hybrid CDN-P2P networks
### [4] A study on repeat-request chunks in pull-based peer-to-peer video-on-demand streaming

https://github.com/abdollahghaffari/CMPVoD/blob/master/oversim.rar
https://github.com/abdollahghaffari/CMPVoD/blob/master/inet.rar
