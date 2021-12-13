# POAPathon.app

POAPathon.app will be an application that will help facilitate organizations with the ability to create design bounties on-demand that enable artists from anywhere to participate in competing for these bounties.


### Product Overview

POAPathon.app will be a web3 enabled application that facilitates “sponsors” and “artists” from anywhere to source and compete on bounty based design work such as creating a POAP. The bounties will facilitate competitive design so that anyone has the opportunity to participate. The bounty sponsor will then select from the designs to choose and pay a winner. 

#### The Bounty Sponsor Persona
I need high quality POAPs in a reasonable time and I’m willing to pay for the best designs

#### The Artist
I am looking for new opportunities to expand my skills, find new design opportunities, learn from other designers and make some cash. 



### POAPathon.App Authentication

The application will have 2 authentication requirements. The first is to authenticate using Discord so that we can easily track participants within the POAPathon community. The second requirement is an ethereum based wallet using a method that incurs no gas cost. This wallet address will be used for sponsors paying bounties and artists receiving bounties. 


### Posting a Bounty - Sponsors
In order to submit a bounty on POAPathon.app a sponsor will authenticate into the application and choose to create a bounty. We want to make this as easy as possible which means keeping information requirements minimal. 

Bounty Details Needed
Bounty Sponsor Name: Text Field (60 characters)
POAP Design Name: Text Field (100 characters)
Design Brief/Assets: Text Paragraph
Reward Amount: Number Field (USDC/MAI or ETH)
Submission Due Date/Time: (Selection preferably)
POAP Event Date: 
Type: Animated, Image or Either

Bounties should immediately show in the Bounty explorer once submitted. A sponsor should be able to edit them. Once the submission date is complete, no new work should be able to be submitted. 

### Browse Bounties

Anyone should be able to browse bounties without authentication into the DAPP. This is where anyone will be able to see all active bounties. 


###Submitting a Design on a Bounty - Artists

In order to submit a POAP design, artists will need to authenticate using their discord and their web3 wallet that is L2 Matic compatible. Artist submissions should be incredibly easy, accepting files up to 10MB for now that are GIF, PNG or APNG. Alternatively we could support a public link to the work. Keep in mind that we may expand file types in the future. Other than the image files we only want to require a text field to add any commentary on the design. Designs can only be submitted until the sponsor due date on a bounty and all submissions will be publicly available to all.

###Selecting a Design - Sponsors

When accessing any bounty in the explorer, all submissions should be visible and accessible to all. Making it easy for sponsors to select and choose their winning design. The sponsor will then be responsible for making the bounty payment directly to the artist.


### Bounty Payments - Sponsors > Artists

Bounty payments will not require any escrow and will not be made through or by POAPathon at this time. The sponsor will need access to the award winners discord name and wallet address  to send the funds themselves. 


## Bonus Features

Notifications within a discord channel:
* New Bounty Posted
* New Submission made with design work posted in the discord channel
* Approval of new bounty posting from a discord channel
* Support for payment of ERC-20 token w/ calculation output in USD
