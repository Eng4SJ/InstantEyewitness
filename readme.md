# InstantEyewitness Project Proposal

## Background

As has been seen over and over and over thanks to recordings by bystanders, encounters with the police can be obscenely dangerous, liable to spontaneously blowing up into violence and murder based entirely upon the particularities of the cop, even if the person in question is absolutely perfectly cooperative. One less commonly-visible story about such cases is that when the bystander is publicly identified, they often face extensive abuse by the cops, including being specifically targeted arrested, and beaten. These instances are not random; their commonality varies immensely on the skin color of the citizen. 
While the video recordings have infrequently actually resulted in judicial consequences for the cop, they provide concrete proof of the dynamics of the interaction, and can help inform the surrounding community about the patterns of racist violence of each individual cop in their neighborhood.


Current efforts to address this have largely been unintentional, like Facebook enabling streaming video from your phone, with the primary exception being the ACLU's videostreaming app that goes straight to their servers. However, groups like Facebook routinely comply with police requests to remotely disable the stream of particular users regardless of the moral obligations that come along with the role they play in the visibility of individuals, and the ACLU apps are region-specific. Both of these require a witness as well, which provides a target for future police harassment if their identity becomes known.

## Objective 

By creating a low-cost open-source semiautonomous microUAV which goes a distance away when commanded to and streams video of the interaction to multiple cloud locations via the user's cell phone connection, the civilian can hopefully benefit from video coverage of the interaction without a local witness becoming a target as well.

## High Level Requirements

### Minimum Requirements
+ *Portability & Size:* If the device is to be used when pulled over by cops, immense size requiring exiting the car is prohibitive.
+ *Low Cost:* The cost will have immense impact on adoption rates in the most vulnerable communities, such as the homeless or the disabled.
+ *Open-Source & DIY-possible:* Don't profiteer off the people whose interests you're seeking to protect by treating this as a 'market need' with a capitalistic profit-centric mentality. Adopting the approach of the wildly successful [OpenBCI](http://openbci.com/) helps to align the interests of the engineers with those of the users.
+ *Sufficient Recording Duration:* The device must last long enough to document such interactions.
+ *Easy to Recollect:* After a false-alarm interaction, the UAV should be easily recollected and recharged for future use.

### Basic Requirements
+ *Record Audio as well:* Whether from the UAV or phone, audio is crucial in understanding the interaction.
+ *Well-Documented:* Tutorials on the creation of and setup of the UAV-app-cloud system is crucial.
+ *Multiplatform:* Support across multiple mobile operating systems is crucial.
+ *Multiple Cloud Platforms:* Ideally, distributing such video across multiple storage locations for the sake of avoiding police efforts to block its propogation is crucial.
+ *Ease of Deployment:* The moments of deployment are crucial for the safety of the user. The process of deploying the UAV and starting the whole system **must** be as automated as possible- such as simply tossing the UAV out of the sidewalk-side car window, perhaps a single unsighted cell phone button press, and trusting it to do the rest.
+ *Obstacle Avoidance:* Try not to get hit by passing cars, smack into a tree, or anything like that.

### Ideal Capabilities
+ *Beginner-Level Tutorial:* If the project can be replicated by a complete novice to computer engineering, this project can also serve as a suitable project for engineering outreach purposes.
+ *Smaller Person-portable Version:* A smaller version intended to be carried on ones' person would provide this coverage even in non-vehicle situations.
+ **_Clever Longevity Methods:_** Finding local surfaces with good views to land on, a fixed-wing UAV, or even techniques like perching, could greatly extend the lifetime (and thus recording-time) of the UAV. This would be exceedingly valuable.
+ *Ensure Optimal Camera Angles:* The face of the cop is particularly important for public knowledge of who to avoid.
+ *Distributed Filesystem Usage:* Distributed Filesystems like IPFS could make the video effectively impossible to remove or block regardless of level of cooperation of major cloud platforms. Such implementation would likely require additional architecture to ensure the videos are indeed actively priorized by other computers to preemptively distribute the video.
+ *Streaming Encrypted Video:* By streaming encrypted video unlockable with predesignated private keys in the hands of trusted friends, the video can be kept secret until after the police release an official report of the incident. This prevents the police from simply tiptoing around the limitations of the footage.
+ *Pigindex:* Create repository/index of such videos involving violence, for use in future projects in the public interest where the criminal justice system has failed.
+ *Find-your-own-wifi:* This fancy stretch goal would entail the UAV seeking out nearby free wifi networks it could connect to on its own in order to upload the video in a situation where the phone loses connection.

## Ethics/Social Justice Concerns

+ Intuitively, the duration of the most crucial police stops is likely significantly different than the duration of the average stop faced by an individual of the project proposer's background.
+ What constitutes suitably low cost is very dependent on socioeconomic status of the user. This will require further investigation.
+ There is a risk the cop observes the UAV and uses it as an excuse for abuse. This is a factor that requires further investigation.

## Provided Materials & Recommended Research Topics

+ Alternative deployment methods-such as a roof docking station- may be worth investigating.
+ Of course, investigating the racial and inter-community dynamics at play that underlie these interactions will likely provide crucial context. Of particular relevance off the top of my head is the percentage of police of low income areas that actually live in those areas. Also of relevance is the ongoing KKK infiltration of law enforcement spaces, as [famously documented by investigations by the FBI](http://www.pbs.org/newshour/rundown/fbi-white-supremacists-in-law-enforcement/).

## Questions for Reflection

+ Why has this problem not been addressed substantivelty by now?
+ What underlying commonly-shared mythos in America drives ideas that somebody should be allowed to be a public official despite explicitly endorsing hate groups?

