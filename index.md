---
layout: default
---

# Home Page

Hi! I am Nico, a researcher taking interest in applied cryptography and privacy-enhancing technologies.
My work focuses on zero-knowledge proofs, their security and applications.
I also dabble in related topics such as threshold cryptography and MPC.

Aside from my own research, I enjoy writing educational content, explainers and technical summaries for all levels of understanding.
You can find some of these articles in the *Technical Writing* section below.

Currently, I am a Research Associate at [Geometry](https://geometry.xyz).
I am also a recurring co-host on the [ZeroKnowledge Podcast](https://zeroknowledge.fm). 

# Projects

## papers
- *Arke*: Scalable and Byzantine Fault Tolerant Privacy-Preserving Contact Discovery Scheme.
([ePrint](https://eprint.iacr.org/2023/1218), [code](https://github.com/asonnino/arke))
> Nicolas Mohnblatt, Alberto Sonnino, Kobi Gurkan, Philipp Jovanovic. Aug 2023.

- *Sangria*: a Folding Scheme for PLONK. ([technical note](https://github.com/geometryresearch/technical_notes/blob/main/sangria_folding_plonk.pdf))
> Nicolas Mohnblatt. Apr 2023.


## talks and panels
- Modular ZK Systems Panel, *with Benedikt Bünz, Christopher Goes, and Zac Williamson, moderated by Anna Rose*. ([recorded talk](https://youtu.be/G7qzkQj7HJI))
> Modular Summit (Paris). Jul 2023.

- Panel on Folding Scheme, *with Benedikt Bünz and Justin Drake*. ([recorded talk](https://youtu.be/2ieRxS9STFs))
> ZK Paris. Jul 2023.

- *Sangria* is Relaxed PLONK: a Nova-like Folding Scheme for PLONK. ([recorded talk](https://youtu.be/D7rQbHpxl7Q), [slides](https://github.com/nmohnblatt/talks/blob/main/2023_04_ZKSummit9_Sangria.pdf))  
> ZKSummit 9. Apr 2023.

- Enabling Decentralised Card Games with Zero-knowledge Proofs. ([slides](https://github.com/nmohnblatt/talks/blob/main/2022_11_IngoGaming_Mental_Poker.pdf))
> ZKProof 5, Ingonyama side event. Nov 2022.

## technical writing

**[ZK Jargon Decoder](https://nmohnblatt.github.io/zk-jargon-decoder/)**: I write (and try to maintain) informal definitions for jargon commonly found in technical writing.

**Mental Poker in the Age of SNARKs**, [Part 1](https://geometry.xyz/notebook/mental-poker-in-the-age-of-snarks-part-1) and [Part 2](https://geometry.xyz/notebook/mental-poker-in-the-age-of-snarks-part-2).
We revisit the famous *mental poker* problem with the efficient proving techniques that emerged between 2010-2022.

**Paper Speedrun** series.
A series of short and accessible paper summaries for the [Geometry blog](https://geometry.xyz/notebook).

## development
Most of the cryptographic code I write are proof-of-concept implementations using Rust.

- Arke cryptographic library.
This library contains the cryptographic primitives needed for our implementation of Arke (see papers above).
These include Shamir secret sharing, an identity-based key exchange, a SNARK-based protocol for blind signature verification and a secret handshake.
Built with [arkworks](https://github.com/arkworks-rs). ([code](https://github.com/asonnino/arke/tree/main/code/arke/crypto))

- An experimental implementation of function-hiding functional commitments from the Marlin pre-processed SNARK, *with Andrija Novakovic*. Based on the [paper](https://eprint.iacr.org/2021/1342) by Boneh, Nguyen and Ozdemir. ([code](https://github.com/geometryresearch/functional-commitment), [blog post](https://geometry.xyz/notebook/functional-commitments-zk-under-a-different-lens))

- A field-agnostic library for Mental Poker using threshold encryption and NARKs, *with Andrija Novakovic and Kobi Gurkan*.
Built with [arkworks](https://github.com/arkworks-rs). ([code](https://github.com/geometryresearch/mental-poker), [intro documentation](https://hackmd.io/@nmohnblatt/SJKJfVqzq))

- Proof-toolbox. A collection of common tools used in ZK applications, *with Andrija Novakovic, Kobi Gurkan and Koh Wei Jie*. Built with [arkworks](https://github.com/arkworks-rs). ([code](https://github.com/geometryresearch/proof-toolbox))

# About me

I am also a musician, my main instrument is the bass.
Since 2015, I have been writing, recording and touring as part of [HMLTD](https://www.hmltd.org).

When I am not proving things or making music, I like to play chess.
Happy to play some games online or in person when we cross paths.

# Contact

Email: `nico [at] geometry [dot] xyz`

---

![](https://imgs.xkcd.com/comics/actual_progress.png)
[Actual Progress](https://xkcd.com/2797/), comic by xkcd