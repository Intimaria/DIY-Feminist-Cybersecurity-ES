---
title: "Anonymity"
bg: blue
color: black
style: left
fa-icon: eye-slash
---

<h2 class="text-white">Be invisible to malicious threats.</h2>

Your casual internet browsing yields a treasure trove of personal data for anyone who can see what you're doing. Websites often track your activity across the internet so they can collect marketing data: demographics, what your interests are, where you spend your time, and so on. As you can imagine, if this data is valuable to companies, it’s valuable to hackers and trolls too; it’s very easy to capture sensitive information like credit card data, physical location, or account data just by being able to monitor someone’s web browsing. So what do you need to know to fight these jerks?

<strong>If your internet activity is not encrypted, it is NOT private and you should assume that someone or something could see it.</strong>

As you browse the web, think of it as constantly sending a multitude of open letters: anyone that positions themselves correctly can simply read them before passing them on to their intended destination. They can know where it came from, where it’s going, and everything contained within. This is where encryption is handy: encryption is like sealing the letters in envelopes, it guarantees that only the desired recipient can read the letters’ contents. And thanks to a lot of ingenious technologies, we can obscure the information about the sender and recipient as well.

<strong>Left unchecked, your cookies will feed personal data to private companies.</strong>

Cookies are an integral part of browsing the web: small pieces of data are stored on your computer by websites to keep track of persistent data such as whether you're logged in or what your user preferences may be. However, it has become very popular for websites to not only store data about your user experience, but also track data about <em>you</em>. These cookies (as well as their ugly cousins like LFOs that perform similar functions) are especially valued by marketing companies that build intimate profiles of your personal information and web habits to be mined and sold for advertising purposes. Often acccumulating for months and even years, malicious cookies can expose vast amounts of personal information about you that companies should not have. This data's existence and dissemination without your knowledge means it's very possible for your data to fall into malicious hands, be it by hacking, leaking, or just invasive advertising.

<strong>Public wifi is so very, very insecure.</strong>

When you are on a wifi network, anyone else using that network can watch your web traffic (even if it's a password-protected network). Because there can be so many people using the same network (like at a coffee shop or library), a malicious hacker could very easily collect <em>tons</em> of personal information about everyone on the network. They could intercept your traffic and feed you fake websites in order to get valuable data from you! And even if you're not using a network intentionally, just leaving your phone with wifi-enabled means nearby networks can tap into your phone and pull metadata about you without your ever trying to use their internet. To fight this invasive snooping, you have to ensure that your web traffic is encrypted: using the <a href="#tor">Tor Browser</a> and/or a <a href="#vpn">VPN network</a> as detailed below will give you great privacy. You should also disable wifi on your phone whenever you explicitly don't need it!

The goal of the section is to make your internet activity secure from nonconsensual tracking and monitoring, effectively making you anonymous (though you are never -truly- anonymous; you have an IP address and an Internet Provider after all!). The amount of protection you adopt is totally up to you: usually the trade-off is the more protection you want, the slower and more inconvenient browsing on the web can be. Fortunately, much of the basic technologies outlined require zero effort on your part and still offer a ton of protection.
<hr>
<div id="privacyextensions">
<p>
	<h3 class="text-white">Zero-Effort Privacy and Security: <strong>Browser Extensions</strong></h3>
</p>
</div>

Browser extensions are no-cost software you can install in your browser to customize your browsing experience. Listed below are extensions that help make your internet browsing safer from governments, corporations, or hackers snooping on your activity. If you don’t feel like reading, just follow the download links and install the extensions; your browser will end-up very secure! However, we recommend at least reading about each extension before you install.

It’s also worth pointing out that of the popular internet browsers (Chrome, Firefox, Safari, Internet Explorer), the only browser not developed by a for-profit corporation is Firefox. The developers of Firefox, Mozilla, have a long history of protecting users rights and are very active in fighting for a free and open internet. With the other browsers, your activity is frequently tracked by the company that owns the browser, so this guide strongly recommends using Firefox as your main computer browser.

<div class="recommend">
<h5 class="text-white"><strong>Privacy Badger</strong></h5>
<br>
'Privacy Badger is a browser add-on that stops advertisers and other third-party trackers from secretly tracking where you go and what pages you look at on the web. If an advertiser seems to be tracking you across multiple websites without your permission, Privacy Badger automatically blocks that advertiser from loading any more content in your browser. To the advertiser, it's like you suddenly disappeared.' - Electronic Frontier Foundation<br>
<br>
Install for Firefox <a href="https://addons.mozilla.org/en-US/firefox/addon/privacy-badger-firefox/">here</a><br>
Install for Chrome <a href="https://chrome.google.com/webstore/detail/privacy-badger/pkehgijcmpdhfbdbbnkijodmdjhbjlgp?hl=en-US">here</a><br>
Official page for more info can be found <a href="https://www.eff.org/privacybadger">here</a>
</div>

<div class="recommend">
<h5 class="text-white"><strong>AdBlock</strong></h5>
<br>
AdBlock blocks ads on 99% of the sites you visit. Ads can be the source of a virus, activity tracking, malware, or just plain annoyingness, so this extension will pre-emptively block these nasty things with no effort from you. Note that the recommended adblock for firefox is not developed by a marketing company, while the chrome version is. The latter will sometimes give you ads that their company has sold.<br>
<br>
Install for Firefox <a href="https://addons.mozilla.org/en-US/firefox/addon/adblock-edge/">here</a><br>
Install for Chrome <a href="https://chrome.google.com/webstore/detail/adblock-plus/cfhdojbkjhnklbpkdaibdccddilifddb?hl=en-US">here</a><br>
Official page for the Firefox extension <a href="https://bitbucket.org/adstomper/adblockedge/">here</a><br>
Official page for the Chrome extension <a href="https://adblockplus.org/en/about">here</a><br>
</div>

<div class="recommend">
<h5 class="text-white"><strong>Disconnect.me</strong></h5>
<br>
Disconnect identifies the “invisible” web, which is all the trackers, beacons, cookies, and other tools that websites and marketers use to track your activity across the internet. It blocks these malicious trackers from seeing your web activity, which in many cases will even make the site load faster. It's a great companion extension to Privacy Badger.<br>
<br>
Install for Firefox <a href="https://addons.mozilla.org/en-US/firefox/addon/disconnect/">here</a><br>
Install for Chrome <a href="https://chrome.google.com/webstore/detail/disconnect/jeoacafpbcihiomhlakheieifhpjdfeo?hl=en">here</a><br>
Official page for more info can be found <a href="https://disconnect.me/">here</a>
</div>

<div id="httpseverywhere" class="recommend">
<h5 class="text-white"><strong>HTTPS Everywhere!</strong></h5>
<br>
Many sites are set-up to encrypt (i.e. make private) your activity when you visit: it can be limited to sensitive things like making a purchase or it can be used for the whole site. This extension makes it so your browser automatically uses this encryption whenever possible.<br>
<br>
Install for Firefox <a href="https://www.eff.org/https-everywhere">here</a><br>
Install for Chrome <a href="https://chrome.google.com/webstore/detail/https-everywhere/gcbommkclmclpchllfjekcdonpmejbdp?hl=en">here</a><br>
Official page for more info can be found <a href="https://www.eff.org/https-everywhere/faq">here</a>
</div>

<div class="recommend">
<h5 class="text-white"><strong>Better Privacy</strong></h5>
<br>
This extension blocks “super cookies”, another way that websites (like Youtube or Ebay) can track your activity on the web.<br>
<br>
Install for Firefox <a href="https://addons.mozilla.org/en-US/firefox/addon/betterprivacy/">here</a><br>
Unavailable for Chrome :(<br>
Official page for more info can be found <a href="https://addons.mozilla.org/en-US/firefox/addon/betterprivacy/">here</a>
</div>

<hr>
<div id="tor">
<h3 class="text-white">Anonymous browsing: <strong>Tor</strong></h3>
</div>
The drawbacks of a browser like Firefox or Chrome is that a website, hacker, or government can still figure out your physical location and which sites you visit based on what’s being sent to your computer from where (even if they can’t read the contents of what’s being sent). In the case of the government or an internet service provider, they can even block access to a website entirely. Whenever using a normal browser, you are always open to this threat, regardless of what extensions you use. <strong>If you are ever in a position where you absolutely NEED to be anonymous, be it for safety or political reasons, then you need to use the Tor network.</strong>

The Tor network is an internet protocol that basically hides your identity by bouncing your web requests across the world in multiple layers of encryption before it is received by the website. Although you may visit a website from Boston, the website will see the request come from England or Kenya or Japan or any other country that the Tor network spits your request from; there is no way to track a web request to its origin. The network also hosts websites (called “onion sites”) that are not accessible through regular internet: this can range from political dissident websites to forums for abuse survivors to drug markets to plain ole’ boring websites. However, you can access the rest of the “normal” internet as well.

To funnel your internet activity through the Tor network, all you need to do is download the Tor Browser and you use it exactly the same as you would a regular browser. You shouldn't install extensions though, as the browser already deanonymizes you and uses HTTPS when available! The most significant drawback is that the network is fairly slow: it takes a few seconds to bounce your requests around the world.

<strong>A big disclaimer for the Tor browser is that it makes you anonymous, but not private.</strong> Although your web requests are encrypted and anonymous, if you are posting on Facebook or sending an email through Gmail, that activity is still identifiable as “you”. So a good rule of thumb is that when using the Tor browser, do not visit sites or services associated with your private information. If you absolutely need to use a site that requires that kind of information, just make it up and make sure not to use it outside of Tor. Also, try not to download anything: because tor nodes (the servers that bounce around your web requests) can be run by regular people, they could attach a nasty virus to a downloaded file if they wanted.

<div class="recommend">
<h5 class="text-white"><strong>Tor Browser</strong></h5>
<br>
Download Tor Browser from the official <a href="https://www.torproject.org/download/download-easy.html.en">Tor Project</a> site.<br>
<br>
The EFF has <a href="https://www.eff.org/pages/tor-and-https">a great interactive guide</a> for how Tor (as well as HTTPS) protects your browsing. More information about the Tor network can be found on the <a href="https://www.torproject.org/about/overview.html.en">official page for the Tor Project</a>.
</div>

<hr>
<div id="vpn">
<p>
	<h3 class="text-white">Improved Security with Some Effort + Potential Cost: <strong>VPN</strong></h3>
</p>
</div>
Tor is slow, so it tends not to be the most fun thing to use for daily internet browsing. However, there are other ways to protect your web activity through a Virtual Private Network (VPN).

<strong>A VPN creates a private, encrypted connection between you and a VPN server; all of your internet activity gets “tunneled” through this private network before leaving the VPN server into the open world.</strong> When you access a website with a VPN connection, the website will see the request coming from the VPN server, not you. Someone trying to see what was being passed between your computer and the VPN server won't be able to see what you're doing: it's all encrypted. Think of it as a private tunnel between your computer and the VPN server: the server lets whatever you want into or out of the tunnel, but no-one but you can see what’s inside. What's especially neat is that a VPN server can live anywhere in the world! If you use a VPN server in Switzerland, websites will think you're Swiss because your web requests are coming from the VPN server in Switzerland. If you use a VPN server in Japan, websites will think you're Japanese.

While some techies run their own VPN servers, most people tend to use VPN providers instead. These are companies or organizations that run and manage VPN servers so you don't have to deal with the technical details: you just use them. Some VPN providers can even deanonymize your activity further by bouncing the web activity leaving their servers through proxies (other servers). Unfortunately, VPN services are typically not free. You either have to set up your own server somewhere or, more commonly, pay for a monthly service from a VPN provider.

<div class="recommend">
<h5 class="text-white"><strong>VPN Providers</strong></h5>
<br>
There are many VPN providers out there so it can be tough choosing: generally you want someone that does not store logs of its users while implementing OpenVPN as its VPN technology (some VPN tech has been hacked by the NSA; as far as we know, OpenVPN has not). It's also great when you have choices about where the VPN server will be: being able to route your traffic through other countries is a fantastic, effortless security measure. Generally speaking, paid providers are much easier to use and can offer customer service and useful guides, but there are free providers out there as well. Here are a few providers we recommend:<br>
<br>
<ul>
	<li><a href="https://www.privateinternetaccess.com/">Private Internet Access</a> is a paid VPN provider that allows you to choose which countries to route your connections through, the ability to pay anonymously via giftcards, and does not store logs about its users' activity. It costs $3.33 a month on a yearly plan, or $7 a month on a monthly plan.</li>
	<li><a href="https://www.feralhosting.com/pricing">Feral Hosting</a> is a paid Seedbox provider that allows you to create a personal VPN server as well as other web services like torrent clients, website management, and file storage. This is a great option for the more adventurous nerds that like the idea of having their own server to play with, but with tons of installation guides, automated management, and fantastic customer support (so it's not as hardcore as having a totally independent server). It costs ~$15 a month for its cheapest plan.</li>
	<li><a href="https://www.cyberghostvpn.com/en_us">CyberghostVPN</a> has limited no-cost options: you can connect for up to 3 hours to one of their VPN networks. This is great if you can't afford a VPN but might want to be safe when working on public wifi once in a while.</li>
</ul>
</div>

<div class="recommend">
<h5 class="text-white"><strong>VPN Clients</strong></h5>
<br>
To use a VPN, you need to install a VPN client on your computer which will communicate with your VPN provider. This is what guarantees the encrypted tunnel of communication from your computer to the server. VPN clients that cost money tend to be easier to use, but the free options work fine too (maybe with a bit more installation effort on your part). Once you’re set-up, all you have to do is click a button in your VPN client and your internet activity will be tunneled to your VPN provicer. Thus, your activity will be much safer with minimal impact on browsing speeds. Set-up instructions for each VPN client would be too lengthy for this guide (We’re only human!) so follow the instructions on their respective sites to get yourself going. Make sure to do this after signing up with a VPN provider so you have the necessary VPN files ready for your client<br>
<br>
<a href="https://www.sparklabs.com/viscosity/">Viscosity</a> is a paid client for Mac and Windows<br>
<a href="https://code.google.com/p/tunnelblick/">Tunnelblick</a> is a free client for Macs<br>
<a href="http://openvpn.net/">OpenVPN</a> offers a free client for Windows<br>
</div>

<hr>
<p>
	<h3 class="text-white">Ultimate anonymity: <strong>Tails</strong></h3>
</p>

Should you ever want to use the internet with absolutely zero trace, you should consider installing the Tails operating system on a thumb drive. Tails is a Linux-based operating system that does not store <em>any</em> permanent data between sessions, while utilizing the Tor network for all internet connections. Every time you log-in, you have a clean slate with no identifying information about you! Installation is a bit advanced for the purposes of this guide, but should you ever need it, you can download the OS with set-up instructions <a href="https://tails.boum.org/about/index.en.html">here</a>.