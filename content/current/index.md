---
title: Current
show_meta: no
---

Here's what I'm currently working on. To see past projects (complete, on hold,
or otherwise check the [archive](archive/)):

## [Wayland](https://wayland.fyi/)

Building [bswc](https://codeberg.org/binkd/bswc), a master-stack style dynamic
wayland compsitor, and many other related todos/side-projects such as
[neuipc](https://codeberg.org/binkd/neuipc).

## Operating Systems

Really enjoying learning more about operating systems, and thinking of ways to
incorporate distributed operating systems into real life
([9front](https://9front.org), ambient computing, etc.).

Specific topics:

- Distributed memory hierarchy
- Userspace drivers and microkernels
- MicroVMs
- Minimalist Linux as IDE ([derive](https://derivelinux.org) and
  [alpine](https://alpinelinux.org))

## [verso_2](https://git.chappelle.dev/verso2/log.html)

A minimal, unix-centric, and easy static site generator. It's what this site is
built on

Currently:

- Working out the kinks as I create posts, add content, and expand the
  capabilities
- Exploring ways to integrate my [stagit](https://git.chappelle.dev) instance
  into the site, as well as other cool bonuses

Current bugs:

- RSS feed is not really up to snuff
- Date/Timestamp management needs to be thought about harder

## TODOs

#### Wayland

- [ ] Herbe style notifications
- [ ] Monocle and full screen in bswc
- [ ] Btree layout in bswc
- [ ] Some bug fixes around focus and master width (diff per workspace)
- [ ] Monitor switching controls
- [ ] Per-monitor layouts
- [ ] Hotplug frees on monitors
- [ ] Focus/float rules
- [ ] Cursor and maybe decorations?
- [x] [Per-monitor workspaces](https://codeberg.org/binkd/bswc/commit/84545588d5554ea813f4fc445a1b61d598aad2d3)
- [x] ~~Find bard/ipc/neumenu regression/crash~~
- [x] ~~Figure out why neumenu not showing up~~
  - ~~Seems like launching Xwayland has something to do with it.~~
  - ~~Impossible to bug hunt atm~~

#### Infra

##### Security

- [ ] Install Tailscale on hetznerbsd
- [ ] Restrict SSH to Tailscale interface only (remove open SSH port from
      pf.conf)
- [ ] Restrict ZNC (port 1026) to Tailscale only

##### Git

- [ ] Add Codeberg → git.chappelle.dev push mirror
- [ ] Git hosting is currently fragile — pushes only work from
      `binkd@hetznerbsd`
  - Consider setting up a dedicated `git` user with authorized keys so any
    machine can push
  - stagit is read-only presentation; all write access needs to go through a
    proper auth layer ok

#### LuaBrow

- See [TODO](https://codeberg.org/binkd/luabrow/TODO.md)
