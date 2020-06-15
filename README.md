# Noah's Stack

Cool tech I use or like for a variety of different uses

## Cloudy Tech (Kubernetes, Functions etc)

[K3s](https://k3s.io/), a tiny, simple, certified, production-ready Kubernetes distro supporting ARM devices as first-class citizens

## Self-hosting

[Inlets](https://github.com/inlets/inlets), an open-source and self-hostable ingress/firewall-buster proxy.

- Perfect for exposing services on your LAN without actually opening ports on your router. All you need is a single publicly-accessible server somewhere like a [DigitalOcean droplet](https://m.do.co/c/608be2b71903) or a [Linode](https://www.linode.com/?r=a0e610b5d050b99292c8dc2b4b6da0e8b63405ed) (<-- referral codes that give you some free signup credit).
- Big shoutout to [BattlePope](https://www.reddit.com/user/BattlePope) on Reddit for suggesting this to me as I was banging my head against the wall trying to use SSH port-forwarding.

[Nextcloud](https://github.com/nextcloud/server), "Most of G Suite in a Box".

- Deluxe collaborative office and communications suite meant for self-hosting on Linux servers.
- Plays nice with Microsoft office and Active Directory
- Client apps available for macOS, Windows, Linux, iOS, Android.
  - Treats Desktop Linux & ARM processors as first-class citizens.
- Offers optional Enterprise support.
  - Deployed in production by the German government.

[Gitea](https://github.com/go-gitea/gitea), a painless, self-hosted Git service.

- Ultra-lightweight GitHub analog.
- Written in Go and performs like it.
- ARM64 first-class support - runs well on a Raspberry Pi
- Supports SSO with LDAP and 0Auth