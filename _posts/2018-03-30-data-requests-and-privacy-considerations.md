# Data Requests and Privacy Considerations

**Most** of the services mentioned will be **free**, however they'll be the odd recommended service that isn't, an example of this is VPNs, they're not something you want to cheap out on. This is still currently being added to hence it not being linked on my sites frontpage

## Request Your Data

This'll be a small segment, listing sites which allow you to easily request your data for free. If you have any additions to this list i'll add them along with a link to your social media saying you helped under a section at the bottom.

 - [Facebook](https://www.facebook.com/help/contact/180237885820953)
 - [Snapchat](https://accounts.snapchat.com/accounts/downloadmydata)
 - [Tinder](https://www.help.tinder.com/hc/en-us/articles/115005626726-How-do-I-request-a-copy-of-my-personal-data-)
 - [Twitter](https://help.twitter.com/en/managing-your-account/how-to-download-your-twitter-archive)

## Email

Emails are the foundations of most online identities, every service you'll want to use will likely require one.

I have **two** personal recommendations:

 1. [Tuta**nota**](https://tutanota.com)
 2. [Cock**Li**](https://cock.li)

You'll likely notice that i've left out protonmail, this is based on the fact that they usually push for verification when registering from Tor or a VPN. Aswell as this they actively block throwaway mails for that verification and push for phone numbers, which are then stored as hashes by them.

Cock**Li** - Won't push for verification of any kind no matter whether you're using Tor, or a VPN. The downfall is they don't offer encryption, your emails are readable by the owner, but you're pushed to use PGP.

Tuta**nota** - Tuta have been known to push for verification, but this is rarely intrusive and usually just requires waiting 24 Hours before your email is usuable. It's also why i've left cock**li** has a recommendation.

## VPN

A VPN is quite honestly a must, I have 1 paid recommendation here, then 2 free ones. The free ones are purely there as a last resort.

#### Paid:

 1. [MullVad](https://mullvad.net) - Based in Sweden they offer a token based payment system, an email isn't necessary for signup and there's plenty of anonymous payment options including cash. Obviously they have a no-logging policy. An Open-VPN Client and Wireguard servers are both offered. I've used them in the **past**.

#### Free:

Both of these services offer paid services.

 1. [CryptoFree](https://github.com/cryptostorm/cryptostorm_client_configuration_files/tree/master/cryptofree) - Offered by a trusted provider [CryptoStorm](https://cryptostorm.is), their speeds are throttled, however a no-logging policy is present and they're the most trustworthy free VPN you're going to find.
 
 3. [ProtonVPN](https://https://protonvpn.com/) - Offered by the creators of ProtonMail and ProtonVPN based in Switzerland. Again obviously a no logging policy is present. However you're given access to limited and slow speed servers.

## Tor

Most people will scream at you to use Tor, but since this is just about some basic level privacy, it's not going to be worked in-to our threat model. Pushing everyday users to only use Tor is something which will likely leave them burnt out.

That being said, if you want a free and an even more anonymous alternative to a VPN then Tor is your best bet. Just understand that you're going to get stopped at every sign-up form, that's after they've finally loaded.

## Twitter

Come join the community,  interact and socialise. Leave you full name at the door though and pick a generic handle. If you're ever pesked about giving in your phone number for 'Human Verification' go bitch at support and they're pretty understanding. 

FYI: They're going to be an ass at signup and reject your [@]cock.li email.

After sign-up the first thing you'll want to do is go-to [Settings](https://twitter.com/settings/account) and toggle on "Require personal information to reset your password", this'll stop your email being leaked via the forgotten password field.

## Google

Do you have any old alias' or names that leave clues as to your real identity? Do your best to get a Google account (You can make one without making a gmail.com email, ridding the need for Phone Verification in that aspect), you can then use the ['Outdated Content Removal Console'](https://www.google.com/webmasters/tools/removals?pli=1) to remove search results. Presuming you've already deleted those previous accounts.


# Secure Messaging

I'm not going to ramble on about how you could use Signal, Wire, Threema, Telegram or any other mobile E2EE messaging service. Anything that requires a phone number is a pain in the ass and should probably be avoided. Wire allows just email signup via their web version, however this isn't usable in the Tor Browser.

Why not go for [**XMPP**](https://xmpp.is) and [**Tor Messenger**](https://blog.torproject.org/tor-messenger-beta-chat-over-tor-easily), or [**Ricochet**](https://ricochet.im). Both Encrypted aswell as routed via Tor. No personal information required.



## Encryption

If you're not using full disk encryption, then you're doing something wrong.

[VeraCrypt](https://www.veracrypt.fr) -  A TrueCrypt successor usable on Windows.

If you're on Linux you may want to check out [LUKS](https://gitlab.com/cryptsetup/cryptsetup/), do some google-fu and work out what you need to do.

## Keybase

I've gained some newfound respect for [Keybase](https://keybase.io/) over the last few weeks, they bring simplicity to PGP and act as a good verification system; The downside being exactly that, having all your accounts and likely an email connected to your PGP public in one centralised place makes OSINT super easy.

It's up to you to weigh out the pros and cons.

## Uploading Files

When uploading files you don't really want to have to go through the hassle of a sign-up form. I'm going to give you three sites, two temporary file upload services and one lifetime one (Requires Signup).

****Temporary****:

[***Uguu***.se](https://uguu.se/) - Compatible with ShareX uguu.se allows you to upload files of up-to 100mb for 24 hours, after that they're deleted from the server and become inaccessible via the original download link.

[***Firefox Send***](https://send.firefox.com/) - Send files through a safe, private, and encrypted link that automatically expires. The max file size is 1GB.

****Lifetime****

[***Mega***.nz](http://mega.nz) - Perhaps one of the most well known file upload services, with a free 50GBs of storage space, they also boast that everythings encrypted. 


## Njalla

Brought to you by a group of privacy activists, [***Njal***.la](https://njal.la) aren't like any other Domain Registrar, you pay them and they actually buy the domain for themselves whilst giving you full access to it. 

They accept a wide range of payment methods including Bitcoin, Litecoin, Monero, DASH, Bitcoin Cash and PayPal. They support PGP for emails or you can sign-up with with an XMPP address and use XMPP + OTR.

Aswell as having a clearnet site, you can find them on tor at [njalladnspotetti.onion](http://njalladnspotetti.onion/). 

Here's how they've handled legal requests in the past - [https://njal.la/blog/about-those-threats/](https://njal.la/blog/about-those-threats/).


# Helped 

Below you'll find the individuals who've helped gather information about various resources.
