# Basics_of_ethical_hacking

## Cyber threat intelligence
Unlike data intelligence is something that we need to process and infer from data.
Cyber threat intelligence is the analysed information about the hostile intent, capability and opportunity of an adversary that satisfy the requirement
cycle - planning and direction --> collection --> processing and exploration --> analyse --> dissemination
preventative function: security operations center support, alerting and triage
- traiging alerts
- enriching IOCs and artifacts
- providing informations to vulnerabilities and risk management
Response functions: Incident response support
- enriching IOCs and artifacts
- facilitating information sharing
Strategic supoprt function
- supporting business decision
- Informing resource prioritization
CTI can influence any dep of an organisation
- Intelligence req : objective that analyst can satisfy, find out what the consumer really want - is russia targetting us?
what business unit are most risk to cyber crime - strategic
what activity groups are currently active our industry - operation
what adversary behaviour should security focus on to identify threats that are the most likey  to breach our organization - tactical

- threat model - knowing what you have in your organisaiton that the adversaries want and bring them to as a model and knowing the adversary 

- which adversary is targetting what part and try to bring them together as a single model

Collection management framework - understand the data and realise what analysis we can make from them


## Collect 
### Intrusion analysis: the lockheed martin kill chain
- look at your own internal informations what all adversary action that the internal network has faced so far
- desribe stages of the single intrution
- and create a seven stages to prevent it (five stages
### malware collection
- malware info can contribute a lot and it is not everything 
- it is an stupendous valuable collection of source
- malware zoos are something we can understand more about the malware by uploading informaiton about them
eg: virustotal, hybrid-analysis, joe sandbox
- make the data available to others including adversaries
- it is a useful CTI collection source
- identify all the relevant indicators --> start with a single indicator --> pivot (through each data source and add relevant data points) --> validate ensure the link contain the context and the links are meaningful
- pivoting a great skill to cti analyst to have
- data pivoting example c2 domain (suspicious domain) --> registrant data (who is the owber of the domian) --> IP resolution --> samples calling back to it
while doing pivoting we could end up with kevin bacon effect everythins connected to everything else
- so try to find more and more pivots so that we can get a confidence towards the adversary
- external data threats : usually exists in the form of IP, digital hashes,  file names, and other atomic and computed threat indicators
- ask these questions 1. where the data coming from? is the threat data applicable to the type of the threats your organization cares about? how is the threat data going to be used?
- Highly trusted sources threat data can be plugged directly into many organizations security architecture to actively identify or block validated threats, but be cautious

TLS certificates - secure host to host previously called ssl- can be used to find c2 infrastructure  censys.iom, scan.io etc sometimes the adversaries uses the same certificates and we can track them based on that

- 
