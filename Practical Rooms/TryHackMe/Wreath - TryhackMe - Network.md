# Wreath - TryhackMe - Network
> [!infobox|wikipedia]+
> ![[wreath-image.png|cover hsmall]]
> # Wreath  - TryhackMe - Network
> ## **Tools Used**
> | Name of Tool | Type of Pentest | 
> | ------ | -------- |
> |  | | 
> | |  | 
> |   |  | 
> | | | 
> |  | | 
> ---
> ## If any please add flags
> | User Flag  | Root Flag |
> | ------ | -------- |
> |  | | 
> | |  | 
> |   |  | 
> | | | 
> |  | | 

> [!infobox|wikipedia]+
> ## Wreath TryhackMe - Network - Usernames and Passwords
> ## **Usernames Found**
> | What usernames found | What type of user are they | 
> | ------ | -------- |
> |  | | 
> | |  | 
> |   |  | 
> | | | 
> |  | | 
> ---
> ## User Passwords
> | Username | User Password in Argon2  | 
> | ------ | -------- |
> | Temp | temp |
## Introduction 
Learn how to pivot through a network by compromising a public facing web machine and tunnelling your traffic to access other machines in Wreath's network.

## Backstory and Brief

#### Backstory

_Out of the blue, an old friend from university: Thomas Wreath, calls you after several years of no contact. You spend a few minutes catching up before he reveals the real reason he called:_

> **_"So I heard you got into hacking? That's awesome! I have a few servers set up on my home network for my projects, I was wondering if you might like to assess them?"_**

_You take a moment to think about it, before deciding to accept the job -- it's for a friend after all._

_Turning down his offer of payment, you tell him😀

#### Brief

Thomas has sent over the following information about the network:

---

_There are two machines on my home network that host projects and stuff I'm working on in my own time -- one of them has a webserver that's port forwarded, so that's your way in if you can find a vulnerability! It's serving a website that's pushed to my git server from my own PC for version control, then cloned to the public facing server. See if you can get into these! My own PC is also on that network, but I doubt you'll be able to get into that as it has protections turned on, doesn't run anything vulnerable, and can't be accessed by the public-facing section of the network. Well, I say PC -- it's technically a repurposed server because I had a spare license lying around, but same difference.  
_

---

From this we can take away the following pieces of information:

- There are three machines on the network
- There is at least one public facing webserver
- There is a self-hosted git server somewhere on the network
- The git server is internal, so Thomas may have pushed sensitive information into it  
    
- There is a PC running on the network that has antivirus installed, meaning we can hazard a guess that this is likely to be Windows
- By the sounds of it this is likely to be the server variant of Windows, which might work in our favour  
    
- The (assumed) Windows PC cannot be accessed directly from the webserver

This is enough to get started!

_**Note:** You are also encouraged to treat this Network like a penetration test -- i.e. take notes and screenshots of every step and write a full report at the end (especially if you're not already familiar with writing such reports). Keeping track of any files (e.g. tools or payloads) and users you create would also be a good idea. Reports will not be marked, but the act of writing them is good practice for any professional work -- or certifications -- you may do in the future. There will be more information on the actual report writing in the_ `Debrief & Report` _task, but for now just focus on extensive notes and screenshots. If you are not already comfortable taking notes, have a look into [CherryTree(opens in new tab)](https://www.giuspen.com/cherrytree/) or [Notion(opens in new tab)](https://www.notion.so/) as hierarchical notetaking applications and focus on documenting every step of the process. This room is written in a way that encourages easy note taking, so note down your kill-chain as you go along, and take lots of screenshots! Reports can be submitted to the room as writeups (in the format specified in the questions of  the_ `Debrief & Report` _task) -- the first five high-quality writeups submitted to the room are featured here!_
