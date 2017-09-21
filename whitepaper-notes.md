## Notes: Section 4: Peer Review

> If the submitter requests the article be peer reviewed a call will go out to reviewers

Are reviewers selected by submitters ? How? i.e. is there a searchable directory of peers ?

Should it not be open to anyone to review? 

I realise that this is a long term vision, but I would suggest that it should be completely open for review from anyone, and that initially "the call to reviewers" is not handled by Aletheia.

Kade - The peer review section is being reworked. The final peer review functionality is currently envisaged to be a choice for the submitter between letting anyone peer review and letting people from their academic field to review. Choice is key here, people should have the option to choose. Most researchers I've spoken to feel the peer review process should be stricted to those with qualifications, they will have the ability exercise their choice and others will have the ability to choose differently. 

> Until the article has been peer reviewed and approved it won’t be downloadable through the client. Reviewers will see through the Aletheia client all the articles they can review and reviewing will be incentivised through reputation 

I don't understand this statement. How would anyone review it without downloading it first?

Again, I cannot think of a reason why an article should not be completely public, immediately after submission. 

Kade - the reason it was initially designed that the article wasn't available from the search function until the peer review process is finished as because the paper isn't ready yet, it's still effectively a draft. But on having researched further into preprints its now acknowledged holding back the paper serves no purpose, when the peer review section is amended this section will be removed.

> a portion of any available funds will be routed to the user as payment on successful completion of the task once the community verifies by a vote that the review was legitimate

Nitpicking... but this implies that a submitted article is given a peer review "bounty" (in ether?) on submission. It's just not explicitly stated anywhere.

Kade - This is another section that's looking at being reworked, we had a contributor who was an academic themselves and had experience with publishing papaers who had sketched out an incentivisation system for peer review. However I've not heard from them in a little bit so I'm unsure if that particular iteration will be implamented. This section is still under review.

## Section 5: Acceptance onto the Blockchain

> A quorum will be calculated from the number of recent logins to Aletheia

Would an Ethereum Dapp have the concept of a "login"? this would imply a "session". Maybe my misunderstanding, but I would have thought that all interactions with the blockchain are done statelessly, via your wallet, and ethereum contracts.

Kade - this is my poor use of terminology, the calculation will be made off active users. We still need to set the parameters for what an "active" user is, what the calculation actually is and all that.

## Section 6: The rights to content shared via Aletheia and takedown orders

> Content that has not been published elsewhere that is submitted to Aletheia...

This wording may be a bit confusing. I think it implies that Aletheia is an organisation that stores data. Surely this is not the case. Is Aletheia simply a vehicle for storing data in a decentralised database? Thus only controllable by those who submit the article ?

Kade - yes and no. The Aletheia Foundation is a not for profit bein set up so there is a legal entity that can hold money from donations and fundraising, I don't want the funds being held by a person. The codebase of Aletheia (and by extension the decentralised distributed database) is technically owned by the free software foundation through being open source. But Aletheia doesn't exist in the sense of an organisation that owns data. The database isn't controlled by anyone, its administered as a DAO.

> Aletheia takes no responsibility for the actions of users, but will comply with takedown orders ...
and
> In the event Aletheia receives a takedown order a notification will be sent to the community through the Aletheia client

This implies that the Aletheia foundation is 'special' or has a special level of control over the whole system. This makes the Aletheia foundation a central point of failure for the entire system - which is what we are trying to avoid. I think it should be clear that the Aletheia software is simply a mechanism for submitting data to a public database.

By providing a mechanism to send notifications to client, we are in fact taking responsibility for our users actions.

In any case, as we are just an open source codebase, there is nothing stopping someone modifying the code and contracts to ignore the takedown orders.

In my opinion, the mechanism for complying with takedown orders should be firmly on the hands of the submitter.

Kade - there are a few distinctions to be made here and again this comes to my poor usage of terms. People think in terms of "Kade and Roo founded Aletheia and run the project, they must own it" because that's how software has largely worked up to now. Roo and I do not own Aletheia at all, but what is intended by saying Aletheia takes no responsibility is that Roo and I don't take responsibilty, the community takes no responsibility, no one takes responsibility, if you use Aletheia and you break the law as in you upload copyrighted content, that's on you. I'm trying to not get sued because even though I don't own Aletheia I'm the most likely person to be sued because people just assume if you build something you must own it. As the Aletheia community administers the database through a DAO, the community votes on takedown notices. You can't leave the only mechanism for revesing an illegal act in the hands of the person who comitted the act because they wanted to commit the act, they will not correct it. The morality of copyright can be debated but ultimately Aletheia must remain on the right side of the law if it's to gain wide acceptance from academics. We had something to the debate around open access by being legal as welll, we become a legal version of Sci-Hub and paywall publishers can't level accusations of criminality at us to smear us, they have to choose another tactic and in so doing the debate advances.


