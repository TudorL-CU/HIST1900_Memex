March 13
 prune these notes 

Time for the internet?
Competences
- existence of digital computers, telecommunications networks, information theory
	- ideas around flow control, logic, algorithms
- remember that information theory allows us to separate the meaning of a message from its 'information'
	- without this insight, digital communications cannot work

timesharing is a technique for using the speed of the computer to present the appearance of multiple simultaneous users
-  remember that computers were very fast in their computations, so a lot of the time computers were just sitting there doing nothing
	- have a terminal connected to the machine
		- if the terminal and machine are not very close together, you need to have a way of connecting the two together
			- this is the modem
IBM 2741, 1965
- direct connection in adjacent rooms, then on local phone lines
	- long distance rates(high cost of communication) makes users work fast, which undermines purpose of timesharing

once you could connect terminals to computers, people started asking how you could connect two computers
- packet switching(originally called 'distributed adaptive messaging blockswitching' until donald davies from the uk gave it a better name)
- developed independently in the US and UK at the same time
Paul Baran of the Rand corporation begins thinking about secure communications
- original system was go/no go via am radios to commanders in the field
- develops 'distributed communication'
	- uses nodes and switches in a way so that if one node is cut off, other nodes can still communicate with each other
Baran's system was not hierarchical, any individual node could look out at different paths

There were distributed networks before Baran
- T&T built their own system 
	-  messages with different priorities
		- the node control was not autonomous, there was a central control system

In the UK
- Harold Wilson fears of losing out on tech
	- Donald Davies, National Physical Laboratory
- UK had initially shot themselves in the foot because they wanted everything to be centralized and have an immediate economic impact
Davies unveils packet switching in 1966
- learns from a British military officer afterwards that it was already invented by Baran
	- Davies reads Baran's work and says we don't need messages like 'kill', 'target', 'survivable' in a civilian context
So he goes and proposes his idea to the post office
- Post Office says absolutely not
	- they don't see a value in this


Back to the USA
- SAGE computer, 1950's
	- Lyndon Johhnson in 1965 directed agencies to support basic university research, and that centers of excellence should be created throughout the university
		- Early computer science centres
			- UCLA, SRI, Illinois, MIT
	- Lawrence Roberts, ARPANET project, 1966
ARPA calls a meeting in 1967 of computer scientists with an interest in computerized communications
- idea of computers that would act as a translators between the main processing computers
	- you would only need to control communications between translators rather than between the larger computers
	- here arises the need for packet switching
- these translators and communicators are called IMPs(interface message processors)
	- the thing that gets designed is a fusion of Baran and Davies's designs
	- fewer of the cold-war survivability features, more of the high-speed transmission and adaptive features
Because the UK wanted everything to have an immediate impact, it stalled their progress and the ARPANET overtook them

SRI(Stanford Research Institute), 1968, Douglas Englebart demonstrates the NLS online system
- 'mother of all demos'

By focusing on the IMPs and how to automatically read the network for congestion and figure out the best route, a lot of local mainframe people are sidestepped
- allows them to evade possible cultural backlash
IMPs were built by BBN(Bolt Beranek and Newman, inc)
- SRI comes up with the 'login' command

October 29, 1969, the 'birth' of the internet
- message between Charles Kline and Bill Duvall
- really just depends on perspective, where do you want to define something as 'beginning'
	- this date is not really the actual birth of the internet, but is just a handy date to have if you were forced to pick one

the problem with building a history of the internet is that most versions of history are a whig history
- told with an end goal in mind, simplistic explanation from beginning to end


the 'birth' of the internet
- it was a network, but one network does not make an 'inter'network


In France
- US and UK have bombs, France needs bombs too wtf
	- French are a bit irritated because french computer companies get bought out by American companies
- 1966 set up a research agency to compete with these other national agencies like ARPA
	- lots of infrastructure set up
- CYCLADES(1971), demo'd in 1973, fully operational in 1976
	- named after the cyclades islands, 'islands' isolated in an ocean of data, brought together by networks to communicate with each other
	- project was led by Louis Pouzin
	- coins the term 'datagram' (data + telegram)
- unlike ARPANET, where the router was responsible for the delivery of the data, CYCLADES made the hosts responsible	


Meanwhile in the Pacific
- ALOHANET, goes into use June 1971
	- University of Hawaii, has campuses on each island
		- instead of wire, 1968 department of Electrical Engineering begin planning a way to broadcast data over radio
		- permits sharing of the main campus computer
	- instead of always broadcasting, if terminals wait between broadcasts, you can send signals without interference

SATNET
- proposal from Larry Roberts in 1970 to connect ARPANET to UK National Physical Laboratory network
	- comes intro fruition by 1973, but connects to University College London instead

PRNET
- Packet Radio Network
	- inspired by ALOHANET, but aims to make things mobile
	- a van with radio receiver/broadcaster that can use packets, is essentially a mobile router
		- obviously the military is interested 

European Informatics Network
- share resources, promote computer science, testbed for techniques, proposed in 1971 and up and running in 1976


Elizabeth 'Jake' Feinler
- develops a 'handbook' as a network databse for ARPANET
- resources at every host
- 1000 pages, record of every node, institution, and individual who worked together to make ARPANET
- then goes on create a new directory with every person on ARPANET and how to find them 
- registers all new hosts, new documentation, new how-to's

History of the internet isn't necessarily a history of technology, but a history of people

Unintended users of the ARPANET, ones that the Department of Defense didn't want on the ARPANET
- help contribute to internet culture
	- games like Zork
		- people sneaking into computer labs at night to communicate with their friends elsewhere

Around this time Xerox Palo Alto Research Center adapts Alohanet's method of communication
- implements wired communication around its facilities
	- Ethernet

Vint Cerf, Robert Kahn
	- oversee a series of meetings and seminars
		- datagrams from cyclades
		- error correction and random access from ethernet/alohanet
		- no more IMP's or network control protocol, the host itself has to handle this
	- Transmission Control Protocol(TCP) hammered out by 1973

1978 TCP gets split into TCP/IP

there are other protocols out there
	- ex. X.25

Now the REAL birth of the internet as we know it is Nov. 27 1977
	- three separate networks passing a message seamlessly between each other
- internet emerges roughly from 1973 to 1983

BBN starts packaging TCP/IP into Unix operating system
	- but most hosts on the ARPANET continued to putter along with the original specifications, they were happy just talking to themselves

Decision from up high that everyone must shift to TCP/IP by Januray 1983 or be cut out of ARPANET entirely


Online Culture of the 1970s and early 80s
- evolution of personal computers and miniturization
	- homebrew computer club
		- members include steve wozniack and steve jobs
		- had a bulletin board for computer equipment
	- ALTAIR 8800
		- kicks off so much because you could tinker with it, open it and do things with it
	- VIC-20 (1980)
	- commodore 64 (1982)
		- one of the best-selling machines of all time
- community and culture of sharing tech and tinkering
phonephreaks
	- figured out how to mimic control sounds that controlled automated switches
	- devices built to help phreakers make things more convenient

WarGames movie scares the hell out of politicians and gets their knickers in a bundle
	- laws start getting framed to deal with hackers and unmitigated access to computers
		- wire fraud, etc.
		- computer fraud and abuse act, after 9/11 got put together with the patriot act

Bulletin board services explode after WarGames
	- exchange public messages and files
		- some bulletin boards were for specific topics
	- you might make use of multiple bulletin boards depending on the things you were interested

apple macintosh comes in 1984 with a GUI(graphical user interface)
	- crucial cultural moment, personalization to a computer screen

first multiplayer type game comes with MUD(multiple user dungeon)
	- can interact with multiple people and create things in game


so the history so far:
	- emergence of personal computers
	- emergence of BBS and other online services that are not the internet
	- the other 'kind' of computer people would be familiar with is the atari game console
		- playing games leads to a desire to connect
		- wargames leads to regulatory climate
		- playing games leads to technological innovation
- early communities give people a sense of how to be
	- early games were about being a place to experience, your physical body may be at home but your mind transported someplace different

where the people go, capitalism is sure to follow
	- Dan Nott, 'Hidden Systems' 



Sliding into hypertext and the web

1983- Domain Names system devised
	- 1984 it comes into effect with .gov, .mil, .edu, .org, .net, and .com(what about .ca?)
- 1986 NSF backbone is built, limits use to 'approved' users
- 1988 commercial email allowed to be transported over NSFNet, commercialization begins
- 1990 ARPANET shuts down
- Al Gore proposes the high performance computing act

1991 the web as we know it comes into existence, 1993 explodes in popularity


the first 'viruses' and 'worms' were written mostly as experiments
	- 'Creeper' designed by Bob Thomas t BBN, would copy itself onto connected computers. Wasn't malicious
	- 'Reaper' designed by Ray Tomlison, made to seek out and eliminate Creeper
- ANIMAL, 1975, John Walker, the first Trojan virus
	- was a 20 questions style game, 'what animal am i thinking of?'
	- secret program included in it called PERVADE, when the game ran PERVADE would examine system for directories
	  and copy ANIMAL to empty directories
- lots of viruses/worms/trojans emerge 
- BRAIN BOOT SECTOR VIRUS, IBM PC virus, 1986
	- would essentially crash the machine during boot-up

The Morris Worm, 1988
	- within 24 hours approximately 1/10th of connected machines were infected
		- massively disruptive, emails delayed for days on end
		- however no computers were destroyed


Hypertext
	- in computerized hypertext
		- some act of selection enables you to pass to another level or related concept
		- formalization and action based on a relationship
- Ted Nelson, Xanadu
	- template for channeling imagination
	- structure information and build relationships between data that help you see them across contexts and clarify understanding
	- argued you needed to see where the link was going to before clicking on it
- Nelson says "HTML is precisely what we were trying to PREVENT— ever-breaking links, links going outward only, quotes you can't follow to their origins, no version management, no rights management."
	- the web today links only one way, Nelson wanted a two way link
lots of hypertext systems emerged in the 1960s


Intermedia- connected 5 different applications into a 'scholars workstation' 
	- Nicole Yankelovish, Nancy Garrett, Karen Caitlin
Link Service(Sun Microsystems)
	- Amy Pearl
Xerox- NoteCards, Cathy Marshall, 1984
	- these notecards provide linking, information management
	- a very similar product becomes bundled with Apple in 1987, 'hypercard'

Tim Berners-Lee
	- proposes a system in 1989 to work mostly within CERN about stringing documents together
	- thinks about linking memos and other documents together
	- the software is working by 1990
- goes to San Antonio, Texas, in 1991 to show off his hypertext idea at a conference


World Wide Web project
	- wide area hypermedia information system aiming to give universal access to a large universe of documents
	- is what we know as the web today
- Mosaic browser 1993
	- released for all popular systems
	- for all intents and purposes this is when the web is born

Hypermedia
	- constructive, to navigate it was to also forge the links that made things meaningful
Web
	- passive, to navigate it is to go where the paths have been made for you



Web History in the 90s

Browser Wars
	- Mosaic, was hit with a lawsuit almost immediately
	- Netscape goes public in 1995
		- incorporated email, users, had plugins
		- javascript, enables dynamic webpages
	- Windows 95
		- has a huge impact
- lots of different companies stealing from each other and publishing their own products
- browsers became platforms where you could do anything
	- different manufacturers would bundle browsers with their products
- internet explorer became integrated with windows OS
	- became bundled together, you couldn't get rid of internet explorer if you had windows os

Netscape can't go head to head with micrcosoft, they suffer big losses
	- due to internet explorer being bundled with microsoft products so people just used that

Mozilla(moz://a)
	- mosaic + godzilla
	- eventually settled on the name 'mozilla firefox'

Yahoo
	- 1994
	- managing and organizing information was worth a whole lot of money
		- females that were doing it previously get pushed out and tech bros swoop in
	- had people organizing websites
		- gained their economic value by being able to direct internet traffic
	- in 2000 yahoo signed a deal to use Google's technology
		- Google uses page ranking system
			- if one site is pointed to by many other sites that must mean it is reputable
- dot com crash caused Yahoo to lose a large amount of stock value

lots of personal sites popped up, passion projects
	- these passion projects were the backbone of the web

The web is a place

geocities shifted the web from something that was passively viewed to something that you actively partook in 
	- was kind of a web within the web, based on user content

Yahoo buys geocities and kills geographical aspect of it
	- turns geographical identifiers into username based identifiers
	- later shuts down geocities with close to no warning, one of the largest losses of internet history
		- some of it was able to be salvaged by internet archive

homesteading creates a community where there was none before
	- digital colonialism, eventual outcome is strip mining

The more a service did moderation on the content it provided, the more liable they would be for that content
	- as a result there is no incentive to moderate content

Section 230 of the Communications Decency Act of 1996
	- "no provider or user of an interactive computer service shall be trated as the publisher or speaker of any information provided by another information content provider"(47 U.S.C. 230(c)(1))

section 230 applies regardless of how much content moderation gets done, but lots of people treat it as if it does


AI Essay
	- 'flooding the zone'
	- it takes a lot more effort to debunk something than it is to make a false claim
	- AI are garbage generators, and it takes a lot more effort to detect the garbage than it takes the AI to create it




Transition through the dot com boom

first let's go back to the 1720s
	- South seas bubble
		- british gov needed refinancing of its debt after various wars
		- south seas company has a promised monopoly on trade to south america
	 	- arrangement to buy gov debt
	- shares rises from 124 pounds to over 1000 in 1720s value
	- price collapses by december 1720, ruins several fortunes
	- the scandal brings the first modern prime minister to power, Robert Walpole, and is the beginning of regulation

A long time later
	- Jeff Bezos, comp sci and engineering degree from princeton
	- joins a hedge fund which uses computers, automating rapid trades
	- leaves the company to do his own thing making money on the web in washington state(no sales tax in washington state)
		- decides to go into the book industry, large industry($25 billion in annual sales), large number of book publishers
		- the business is fragmented, he figures he can solve that
	- starts amazon.com
		- at first, you buy your book on amazon, they go buy the book from the warehouse across the street, they repackage it and mail it to you
		- they lose money at first, the business doesn't work unless you have lots of money put into it
		- this is where venture capitalists come in
		- give money to you in exchange for a stake in the company
			- for the vc's to make big money, they want the company they invest it to have its stock inflated, so they can offload their shares onto others for money
	- 16 May 1996 Amazon gets a front page article on the Wall Street Journal
		- hugely important for Amazon, their sales boom
		- amazon is still losing money, but Bezos is becoming incredibly popular in the media

This is the strategy of the dot com boom
	- have an idea doesn't matter if it's good, persuade a venture capitalist who doesn't want to lose out on the internet to invest in it
	- burn that money to become as popular as possible, inflating the value of your company
	- use the initial public offering(IPO), cash out for huge gains

March of 2000, NASDAQ suddenly starts crashing
	- all the fake money and options that employers were using to pay their employees, eventually the employees went to cash out
		- companies have to pay out
some survivors of this crash included
	- amazon, ebay

Internet Archive becomes really important

CV parsing software by companies to look for embedded phrases 

Google comes and creates a search engine using parsing software to link stuff to your search
	- clickthrough rate: ratio of how many people click your link vs how many people see your link

promoting a site to give it more traffic

Google cofounders Brin and Page were originally against advertising 

search engine optimization
	- safiya noble 'as users engage with technologies like search engines, they dynamically co-construct content with the technology itself'


in 2007 metaweb launches a project called freebase
	- semantic web, authoritative source for content
		- makes sure content from 2 different people with the same name is separated
	- was an important part of user generated web 2.0 content

if you have enough information about something but in 2 different language, you can use language models to compare two different things and see how they change from one language to the other, effectively translating it
	- with these large amounts of info, you can take something without attribution, essentially infringing copyright
		- ai ethics researchers fired from google because with the amount of money involved in ai, they don't want to be cumbered by ethics


'enshittification'
	- Cory Doctorow
		- 'here is how platforms die: First they are good to their users, then they abuse their users to make things better for their business customers; finally they abuse those business customers to claw back all the value for themselves. Then they die.'

the concept of enshittification was understood from the beginning, even by Page and Brin in 1998
	- "advertising funded search engines will be inherently biased towards the advertisers and away from the needs of consumers"
