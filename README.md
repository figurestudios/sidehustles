# sidehustles

> `sidehustles` was initially crated during the [Activate x Wormhole](https://www.activate.build/miami) hackathon to increase online financial inclusion with the help of providing infrastructure to open platforms.

## About

With wealth being as inequally shared around the globe, something must be done to help give people a chance for a Universal Basic Income (UBI). `sidehustles` is targeting a global freelancing market where users all over the world can work online on tasks such as writing, drawing, and programming. Regardless of where you come from or who you are, you will be able to sign up for a task within your skillsets. Do you know how to write? Maybe someone is looking for a ghost writer... But `sidehustles` cannot be perfect. Just as wealth is not equally distributed, certain skills, internet access, and education paths do have correlation with how wealthy ones community is. Not everyone has access to computers or the internet, not even in libraries or similar locations.

With the help of Polygon, both parties can feel safe and not be dependent on one frontend. Workers and requestors are assured by the security of smart contracts. DAOs and escrows can both be utilized to handle disputes between the parties in case they cannot agree on whether to pay out or not. By basing everything off smart contracts, there is no need for one platform to handle everything. The smart contracts include information regarding everything, which includes a description of the job, work files, communication between the two parties, and more.

Everything regarding files is made possible with Skynet. Here, we can have the requestor set up a skylink (34 bytes) with all the relevant data. It's important for this data to follow standards for multiple platforms to be able to display the same work contracts. A requestor should not be able to change data during the contract because that would allow someone to, for example, change a work description from "create a 150 word article," to "create a 150**0** word article." But mutable data is also required for communication, which can be done by allowing certain fields to include public keys (64 bytes/ea) that point towards registry entries. Similarly, the worker can utilize the same technology to ask questions or give details on their finished work.

## Branch repositories
 - [sidehustles-frontend](https://github.com/figurestudios/sidehustles-frontend) - An example frontend that makes use of the sidehustles trusted functionalities.
 - [sidehustles-contacts](https://github.com/figurestudios/sidehustles-contracts) - A repository with the smart contracts that helps make these trusted work contracts possible.
