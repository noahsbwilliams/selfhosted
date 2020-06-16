# Self Hosted

*Apps & tools that run great on-prem.*

Criteria for Inclusion:

- [ ] Must run on both x86-64 and ARM64 CPUs (Intel/AMD machines & Raspberry Pi).
- [ ] Must be core useful functions must be open-source.
- [ ] Must come packaged in a public container registry.

[K3s](https://github.com/rancher/k3s), a tiny, certified, production-ready Kubernetes distribution.

- Super easy to init and configure.
- Much smaller binary than regular Kubernetes - strips out deprecated APIs, alpha features, and vendor-specific code.
- Much more flexible system requirements.
  - Supports ARM devices as first-class citizens.

[Inlets](https://github.com/inlets/inlets), an open-source and self-hostable ingress/firewall-buster proxy.

- Perfect for exposing services on your LAN without actually opening ports on your router. All you need is a single publicly-accessible server somewhere like a [DigitalOcean droplet](https://m.do.co/c/608be2b71903) or a [Linode](https://www.linode.com/?r=a0e610b5d050b99292c8dc2b4b6da0e8b63405ed) (<-- referral codes that give you some free signup credit).
- Big shoutout to [BattlePope](https://www.reddit.com/user/BattlePope) on Reddit for suggesting this to me as I was banging my head against the wall trying to use SSH port-forwarding.

[Ceph](https://github.com/ceph/ceph), a distributed storage system.

- Useful for creating shared storage pools between networked machines.
- Works with or without containers/Kubernetes.
- Treats ARM devices as first-class citizens.
- Good alternative to NFS shares on Raspberry Pi clusters.

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
- ARM64 first-class support - runs well on a Raspberry Pi.
- Supports SSO with LDAP and 0Auth.

[OpenFAAS](https://github.com/openfaas/faas), serverless functions on Kubernetes with no cloud vendor lock-in.