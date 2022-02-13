# f**k forensic
Explanations on how to be invisible from digital forensic experts

#### This project is not affiliated with anyone, all the tools shown here are for education purpose only (with the objective of understanding how digital forensic work)
# Summary
1. [Summary](#summary)
2. [On the web](#on-the-web)
- [Proxies and VPNs](#proxies-and-vpns)
- [Tor browser](#tor-browser)
- [Communication](#communication)
- [Digital identity](#digital-identity)
- [Emails](#emails)
- [Protection](#protection)
- [Domain registration](#domain-registration)
3. [On your computer](#on-your-computer)
- [Operating system](#operating-system)
- [Disk encryption](#disk-encryption)
- [Hard drive wiping](#hard-drive-wiping)
- [Files](#files)

# On the web
## Proxies and VPNs
Foremost, let's talk about VPNs. They are very effective at hiding your IP address from servers, but they are run by private companies and even though they claim to have a "No log" policy, they can record your activity to sell personal information or give it to law enforcement, so you can't trust them 100%.

Proxies are a very good option, but it's the same thing, companies can record your activity.
However, you can create your own VPN or proxy server by yourself or use those administered by individuals.

https://openvpn.net/community-resources/how-to/
## Tor browser
Tor is a very good browser, you need to use it every time you want a private browsing and you can access to .onion domains, but use it with a VPN and a Proxy, some Tor exit nodes (servers that make tor work) are under the supervision of the law enforcement. Don't use it for everyday life because it is very slow.

https://www.torproject.org/

## Communication
There is some application that provide you private, encrypted, anonymous and secure communication:
- Telegram (Secret chat only and with proxy)
- Signal
- Cryptoip


https://telegram.org/

https://www.signal.org/

https://github.com/DrayNeur/cryptoip

## Digital identity
First, don't use your real identity and personal email address. Whenever a website asks you for personal information, use a fake identity and several email addresses.

Use randomly generated passwords, you can store them on LastPass with 2FA.

https://fauxid.com/

https://www.lastpass.com

## Emails
Use multiple emails... A lot !

These are some free private emails:
- Protonmail
- Tutanota

Paid but 100% anonymous:
- Lavabit

https://protonmail.com

https://tutanota.com

https://lavabit.com

## Protection
Some important step that you need to do:
- Use a strong, randomly generated password longer than 16 characters
- Use 2FA
- Use different emails

## Domain registration
You can register domains on namecheap because they keep you anonymous because they're located in Iceland.

https://www.namecheap.com

# On your computer

## Operating system
I recommend using a Linux distribution because on Windows, you are tracked by Microsoft and most Linux distributions allow LVM disk encryption

If you want to use Windows either you use a windows ISO or you can emulate windows on Linux with high performance.

If you want to use a windows ISO, uncheck every tracking options and GPS option.

If you want to use Linux and emulating windows follow the GPU pass-through KVM.

https://gitlab.com/risingprismtv/single-gpu-passthrough

## Disk encryption
To encrypt disk you have multiple choices the first based on your operating system and the second on which method you want to use.

YOU NEED TO WIPE ANY DATA LEFT ON THE DISK.

### Windows
You can use Bitlocker but you need Windows 10 Pro or Enterprise.

https://www.windowscentral.com/how-use-bitlocker-encryption-windows-10

### Linux
You can use LVM disk encryption at installation or if your system is already installed then use cryptsetup

https://dev.to/lobo_tuerto/how-to-setup-full-disk-encryption-on-a-secondary-hdd-in-linux-4047

## Hard drive wiping
When wiping a hard drive uncheck the fast wiping option and use full wiping (delete data). But I recommend using a tool called wipedicks to be safe.

https://github.com/Drewsif/wipedicks (Will annoy digital forensic experts)

## Files
If you want to delete files without leaving a trace, encrypt them and then delete.

You can use these tools:
- https://github.com/Drewsif/wipedicks
- https://github.com/r3nt0n/wiper
