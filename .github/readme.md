This is a hard fork of Drone CI.

The upstream project is at https://github.com/drone/drone

This project pulls in upstream manually every week or two.

## What's the goal?

Drone is a heavily forked project mostly because of its engineering qualities. Several companies I know forked Drone for their own purpose, either tp patch something that doesn't get merged in upstream, or incorporating Drone in their product.

This fork has different motivations.

**It is meant to distribute and improve upon the Drone OSS version.**

The fork's is distributed on Docker Hub with the image tag of `laszlocloud/drone-oss`. Builds are running on Drone Cloud https://cloud.drone.io/laszlocph/drone-oss

This project is not associated with the company behind Drone.

## Why fork?

The company behind Drone no longer distrobutes the OSS version.

They make several gestures for hobbyists (using Gitea, Gogs, etc), and small companies under a certain revenue or yearly build count but users commercial users of 0.8 are left behind.

Since Drone 1.0 the licensing model has changed, several used to be open source feature were removed from 0.8 and now part of the enterprise version of Drone.

- No TLS
- No agents
- No Postgres or MySQL backends, only SQLite

This renders the open source version close to useless and it's a setback for happy users of version 0.8. I wrote about this a bit more while I discovered the limitations here: https://laszlo.cloud/drone-community-edition-what-is-included

## Roadmap

The Github issues show what's planned.

I'm not looking to implement all missing features as of now. Just distributing the OSS image and fixing tests is a good baseline what in my mind could have been a curtsy from the company behind Drone.
