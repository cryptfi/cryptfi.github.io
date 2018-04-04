#### This is a guest post written by [Sh1ttyKids](https://twitter.com/Sh1ttyKids), named Awesome Darkweb Research. You can find the original at https://hackmd.io/s/rJ-3VKNPG.

# Awesome DarkWeb Research

Writer: [Sh1ttyKids](https://twitter.com/Sh1ttyKids)

**Introduction** In recent years, Cybercriminals is increased on the DarkWeb. But several agents cannot be tracking much. I thought it would be better for more people to tracking the DarkWeb. So I write what is important on the DarkWeb research. The target reader is those who are interested in dark webs and have Internet literacy with a degree of Computer usage. As a criterion for judging you have Internet literacy or not, I thought it is good that Kaspersky 's [Cyber Savvy Quiz](https://blog.kaspersky.co.jp/cyber-savvy-quiz/) got high scores and so on.

On the DarkWeb, there is overwhelmingly illegal content. I would like you to should have a settled conviction for research. Even in investigating, I would like you to set your own rules. What I would like you to be most conscious about is OPSEC (identity security). if you don't know the word OPSEC, you cannot even be at the start of research. I want you to think again before starting research. It also has the possibility of being killed if your identity is found. I recommend you should read Mr.the_grugq's [OPSEC for Hackers](https://grugq.github.io/presentations/Keynote_The_Grugq_-_OPSEC_for_Russians.pdf) once.

## What is DarkWeb?

It is a group of websites constructed with the Hidden Service which is the function of Tor. You can not access without using Tor. Darknet refers to an IP Address that is not assigned to the host computer, but in the DarkWeb Area, there are also Darknet used by the meaning of the DarkWeb.

## You must protect this rules.

Here we describe the rules you should observe when researching the Dark Web.

**1. Do not wiretap using Tor node.**
Holy fxxxing shit.
In addition to cybercriminals, it is shit for users who use it with good intentions, so you should never do it.

**2. Protect your information by separate the handle name as much as possible during research.**
Since requests for Murder are also done on the DarkWeb. So as not to be killed even if your personal data found by cybercriminals, don't tie it with your own information. We recommend that you associate information on the fake with that handle.

**3. Keep constant distance feeling between you and cybercriminals.**
When you want to hear information or want to interview to cybercriminals, you have to maintain a certain sense of distance. if you are too close to CyberCriminals, you will be doing a crime(LOL), or conversely, if the distance feeling is too much you cannot hear information.

**3. Always encrypt messages and emails between you and cybercriminals.**

It is very cautious because your partner is a cyber criminal. Be sure to encrypt the message whenever you want to do a questionnaire or interview. It is recommended to use it also to protect yourself.

## Preparation for Research

There are several things to prepare for investigating the dark web.

### OS preparation

When accessing the dark web it is recommended not to prepare your own PC that you use all the time but prepare another Computer or use a virtual machine.

- [Tails OS](https://tails.boum.org)
- [SubGraph OS](https://subgraph.com)
- [Qubes OS](https://www.qubes-os.org)
- [Whonix](https://www.whonix.org)

Although there is a possibility of posting in the future, But now I wrote how to use it only, I would like to omit it this time. By the way, I use Qubes OS.

### Browser settings

When you using the Tor browser, set the security level to the maximum safest from the security setting. 

Besides setting torrc not to go through servers in dangerous countries such as Five Eye and any countries that have signed the Cybercrime Treaty as necessary. Regarding torrc setting method, it seems to be good that TorProject publishes materials and so you can refer to that.
Tor Manual

### Establish communication method

As mentioned earlier, since cybercriminals encrypt messages and emails, they use these services to exchange messages.

- [XMPP](https://ja.wikipedia.org/wiki/Extensible_Messaging_and_Presence_Protocol)
    The server recommends [xmpp.is](https://xmpp.is) and [exploit.im](https://exploit.im). Clients recommend Pidgin or Coy.

- [Telegram](https://telegram.org)
    It is necessary to register using the SMS service which can be paid by Bitcoin although a telephone number is required at the time of registering the account.

- [ProtonMail](https://protonmail.com)
    In the mail service, it encrypts with End to End.

- [Tutanota](https://tutanota.de)
    Same as above

Encrypt with PGP when using regular mail service.

## For investigation

- [Google](https://google.com)
    Everyone can use it enough for surveying that service, DarkWeb which you know well.
    Example) [inurl:server-status AND inurl:onion.to](https://www.google.co.jp/search?q=inurl%3Aserver-status+AND+inurl%3Aonion.to)

- [DNSTrails](https://dnstrails.com)
    Use it when researching websites that exist on Clearnet for advertising to the dark web

- [DomainBigData](https://domainbigdata.com)
    Same as above

- [Shodan](https://shodan.io)
    I often use it when looking for IP leaks.
    Example) [.onion](https://www.shodan.io/search?query=.onion)

- [Censys](https://censys.io)
    Same as above

- [Fofa](https://fofa.so)
    Same as above

- [ZoomEye](https://zoomeye.org)
    Same as above

- [Onion Investigator](https://oint.ctrlbox.com)
    Sites that are scanning and publishing sites on the dark web. It is compatible with various ports, easy to use.

- [DeepDotWeb](https://deepdotweb.com)
    You can find out what is happening on the dark web at a site that is writing news on the dark web. You can also find information on protecting your privacy, interviewing the darknet market manager and arresting on dark web related. We also conduct VPN service reviews.

- [Reddit](https://reddit.com)
    Bulletin board, there is a sub bulletin board dedicated to DarkWeb. The following information can be gathered.
     - Review of drug dealers
     - Dark web news
     - A message from the administrator of the site on the dark web
    - Information on scammer
    - Services related to the newly launched dark web
    - Tutorial on how to maintain anonymity
etc.

- I always see this SubReddit
    - [/r/DarkNetMarkets](https://www.reddit.com/r/DarkNetMarkets/)
    - [/r/onions](https://www.reddit.com/r/Onions/)
    - [/r/HiddenSerivce](https://www.reddit.com/r/HiddenService/)
    SubReddit etc. for other market
    
## Things to keep in mind during an interview

When you need information, and interview to cybercriminals, but there are a few things to keep in mind, so write below.

- Encrypt all messages

- You don't interrogate the person's personal information

- I recommend you to talk to trusted guy for cybercriminals

- Explain why you would like to interview, how you use the information you got, and clarify where and how it will be published

## About De-Anonymize

The most important anonymity for Tor users, sometimes it is revealed. This time I will write about the method of finding the IP leakage of the site on the dark web constructed by Hidden Service. From now on I will write down the way to remove the user's anonymity.

## Threat Model

There are four, but each plays an important role. Absolutely this order is nothing.

1. reconnaissance
In this phase, we collect information gained from the outside. For example, the site's source code and header, the administrator's mother tongue.

2. Assemble information
We drop the obtained information along with the syntax for searching using web services such as Shodan, censys, zoomeye, fofa, which scan the address space of ipv 4 into a database.
Example) When you want to search by specifying OS by censys
**metadata.os_description: Debian**

3. Search
We will actually look for IP leaks using information gained through reconnaissance.

4. Verification
Because phishing scams are often rampant, we will verify that it is a real server.

"The site is leaked IP! !" Even though I thought it was a fake thing. They may be distinguishable by checking the source code and header.

## De-Anonymize's method

- SSH fingerprint
- Keyword search
- Survey on Clearnet side
- header

## What De-Anonymize brings

The leakage of IP address stays in the eyes of the law enforcement agency, and it seizes the location of the server based on the IP address and seizes (takedown) and analyzes it. Arrest the manager and the information of the other person who was conducting the transaction there is handed over to the institution. It seems that there are many flows of the arrest of related persons.

## The situation of the future dark web

- Darknet market is expected to shift to a decentralized market like OpenBazaar in the future due to successive darknet market fraud and hacking. In OB 2.0 it corresponds to Tor.

- Information such as installation method has already begun to appear with Reddit and others.

- The virtual currency used for trading has also moved to things like DASH, Monero, Zcash which are highly anonymous.

- It is necessary to think about a method to remove anonymity from another angle without embedding and eavesdropping illegal code.

## Point

- There is no perfect website even on the dark web. There is something missing.

- There is little information on the dark web, it is important to combine like puzzles by drawing information one by one.

- In particular, there is a need to think about which drugs are popular in which country, why.

- OSINT of this hand can be used for C2 panel search of malware.

### Document
[Deanonymizing Tor Hidden Service Users Through Bitcoin Transactions Analysis](https://arxiv.org/abs/1801.07501)

[Deanonymize tor hidden services](https://www.slideshare.net/AndreaBissoli/deanonymize-tor-hidden-services-76327684)

[Ultrasound Tracking Could Be Used to Deanonymize Tor Users](https://www.bleepingcomputer.com/news/security/ultrasound-tracking-could-be-used-to-deanonymize-tor-users/)

[Deanonymizing tor](https://www.defcon.org/images/defcon-16/dc16-presentations/defcon-16-evans-grothoff.pdf)

[An Overview of Modern Tor Deanonymization Attacks](https://www.deepdotweb.com/2017/09/12/overview-modern-tor-deanonymization-attacks/)

[The Most Dangerous Town on the Internet - Where Cybercrime Goes to Hide](https://www.youtube.com/watch?v=CashAq5RToM)

[Crystal Meth and Cartels in the Philippines: The Shabu Trap](https://www.youtube.com/watch?v=eJ0I7HyZNiI)

[About DarkWeb](http://sh1ttykids.hateblo.jp/entry/2017/11/19/110026)


[Anonymous Interview with Drug Buyer on the DarkWeb](http://sh1ttykids.hateblo.jp/entry/2017/12/16/153256)

[IP exposes on the ElHerbolario](http://sh1ttykids.hateblo.jp/entry/2017/11/16/182001)

[IP exposes on the Italian Darknet Community](http://sh1ttykids.hateblo.jp/entry/2017/10/29/152042)



# Donate to [Sh1ttyKids](https://twitter.com/Sh1ttyKids)

Bitcoin:      14xynNexMYP6kyKmNUchcGSTfgkCHGaGgr
Bitcoin Cash: qpx57mqju870ajr8gf2zrjnmhcd5sgzgwgnuemrtaz
Mona:         MAuY2Wk9pQH6AHFvCVMoTCeaA7dKAc5Wmt
Monero:       47CdMXnDg7TBeskdJed5SWFTJ5xr33jJDdb37Q6jEoLnHt1qkXo65p6P7Aq8npoNy2Uevme9ZHo2RWNjC8hvmZPiHFiWfTf
Zcash:        zcMQnMdwiRkB4gbTv1Y7JELQ3ucAybFt5SdWCYcKQa4TNmjUdky4iyynFiXY8fBkG9MBPWf5PymANGFhfweCUFKQ4DD5V6p
